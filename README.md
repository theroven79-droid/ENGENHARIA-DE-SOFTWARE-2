# 📐 Engenharia de Software II — Documentação de requisitos

Este repositório reúne dois **documentos acadêmicos de levantamento e especificação de requisitos**: um para um aplicativo bancário e outro para um sistema de cadastro de receitas.

Os arquivos descrevem comportamentos e qualidades desejadas. **Não há implementação dos aplicativos neste repositório.**

## 📂 Documentos

| Arquivo | Tema | Conteúdo principal |
|---|---|---|
| [Modelo de documentação de sistema](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema.docx) | Aplicativo bancário | Cadastro, acesso, Pix, pagamentos e comprovantes. |
| [Modelo de documentação de sistema — versão 2](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema_2.docx) | Cadastro de receitas | Criação, listagem, pesquisa, edição e exclusão de receitas. |

Os arquivos estão em formato `.docx` e podem ser abertos no Microsoft Word ou em outro editor compatível.

## 🏦 Aplicativo bancário

| Identificador | Requisito funcional descrito |
|---|---|
| RF-01 | Cadastrar uma conta com dados pessoais e senha que atenda a critérios de complexidade. |
| RF-02 | Acessar a conta com CPF e senha, mediante aceite dos termos previstos. |
| RF-03 | Cadastrar uma chave Pix. |
| RF-04 | Efetuar pagamentos por Pix, débito ou crédito, conforme as condições especificadas. |
| RF-05 | Compartilhar comprovantes de pagamento. |

O documento também apresenta requisitos não funcionais relacionados à segurança, à criptografia, à LGPD e à conexão com a internet.

## 🍽️ Cadastro de receitas

| Identificador | Requisito funcional descrito |
|---|---|
| RF-01 | Cadastrar uma receita com título, ingredientes, modo de preparo, tempo e categoria. |
| RF-02 | Exibir as receitas e permitir a consulta aos detalhes. |
| RF-03 | Pesquisar por título e filtrar por categoria. |
| RF-04 | Alterar informações de uma receita já cadastrada. |
| RF-05 | Excluir uma receita após confirmação. |

Entre os requisitos não funcionais estão interface de alto contraste, armazenamento local, desempenho, suporte a Android e iOS e compressão de imagens. Esses pontos fazem parte da **especificação**, não representam funcionalidades implementadas.

## 🧩 Como interpretar os requisitos

| Sigla | Significado |
|---|---|
| `RF` | Requisito funcional: o que o sistema deve fazer. |
| `RNFR` | Requisito não funcional relacionado: qualidade ou restrição associada a uma função. |
| `RNFS` | Requisito não funcional sistêmico: condição aplicável ao sistema de modo mais amplo. |

Os dois modelos também incluem seções de objetivos, público-alvo, escopo, envolvidos, estimativas e viabilidade.

## ⚠️ Observações sobre os documentos

- Alguns campos continuam com orientações de preenchimento, inclusive as seções de RF-06 a RF-08.
- No segundo arquivo, a capa ainda apresenta a identificação “Aplicativo Bancário”, embora os requisitos preenchidos se refiram ao cadastro de receitas.
- Os requisitos registram comportamentos **propostos**. A existência dos documentos não comprova desenvolvimento, implantação ou testes dos aplicativos.

## 📚 Referências

- [ISO/IEC/IEEE 29148 — Engenharia de requisitos](https://www.iso.org/standard/72089.html)
- [GitHub — Documentação de Markdown](https://docs.github.com/pt/get-started/writing-on-github)
