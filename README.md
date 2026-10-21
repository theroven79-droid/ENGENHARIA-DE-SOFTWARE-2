# 📐 Engenharia de Software II — Especificação de requisitos

Repositório acadêmico que reúne **dois documentos de especificação de sistemas**, voltados a levantar objetivos, escopo, envolvidos, viabilidade, restrições e requisitos funcionais e não funcionais.

> **Natureza do repositório:** documentação em `.docx`. Não há código-fonte nem aplicativos implementados aqui.

## 📂 Documentos disponíveis

| Documento | Escopo principal |
|---|---|
| [Modelo de documentação — aplicativo bancário](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema.docx) | Cadastro e acesso à conta, chave Pix, pagamentos e compartilhamento de comprovantes. |
| [Modelo de documentação — cadastro de receitas](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema_2.docx) | Cadastro, listagem, busca, edição e exclusão de receitas. |

## 🏦 Caso 1 — Aplicativo bancário

| Código | Requisito funcional descrito |
|---|---|
| RF-01 | Cadastrar conta com identificação e senha com critérios de complexidade. |
| RF-02 | Acessar a conta mediante CPF, senha e aceite dos termos. |
| RF-03 | Cadastrar chave Pix. |
| RF-04 | Efetuar pagamento via Pix, débito ou crédito (parcelamento especificado). |
| RF-05 | Compartilhar comprovante de pagamento. |

Entre os requisitos não funcionais descritos estão criptografia, LGPD, segurança da conta, conectividade e redefinição de senha após tentativas de acesso.

## 🍽️ Caso 2 — Cadastro de receitas

| Código | Requisito funcional descrito |
|---|---|
| RF-01 | Cadastrar título, ingredientes, preparo, tempo e categoria. |
| RF-02 | Listar receitas com miniatura e detalhes. |
| RF-03 | Pesquisar por título e filtrar por categoria. |
| RF-04 | Editar informações, inclusive imagem. |
| RF-05 | Excluir receita após confirmação. |

Os requisitos sistêmicos descritos incluem interface minimalista, funcionamento com armazenamento local, carregamento em menos de dois segundos, suporte a Android/iOS e compressão de imagens. **São requisitos propostos, não funcionalidades comprovadamente implementadas.**

## 🧩 Como ler a documentação

| Sigla | Significado | Uso |
|---|---|---|
| `RF` | Requisito funcional | Comportamento esperado do sistema |
| `RNFR` | Requisito não funcional relacionado | Restrições e qualidades vinculadas às funcionalidades |
| `RNFS` | Requisito não funcional sistêmico | Condições gerais da solução |

Os arquivos incluem descrição do cliente/público, objetivos, viabilidade, estimativas, escopo e levantamentos de requisitos. Abra-os no Microsoft Word ou editor compatível com `.docx`.

## ⚠️ Pontos de atenção dos modelos

- Permanecem campos de instrução ou exemplos a preencher, inclusive RF-06 a RF-08.
- A capa do documento `_2` ainda menciona “Aplicativo Bancário”, embora o preenchimento trate de receitas.
- Nenhum dos dois documentos, isoladamente, demonstra que as aplicações foram desenvolvidas ou testadas.

## 📚 Referências

- [ISO/IEC/IEEE 29148 — Engenharia de requisitos](https://www.iso.org/standard/72089.html)
- [Documentação de Markdown do GitHub](https://docs.github.com/pt/get-started/writing-on-github)
