# Engenharia de Software 2 — Documentação de Sistemas

Acervo de dois documentos Word de levantamento e especificação de requisitos. O conteúdo disponível é documental: não há código de aplicação, scripts de instalação ou testes executáveis neste repositório.

## Documentos disponíveis

| Documento | Conteúdo encontrado | Estado |
|---|---|---|
| [01-Modelo de Documentação de Sistema.docx](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema.docx) | Requisitos de aplicativo bancário | RF-01 a RF-05 preenchidos; outras seções ainda têm instruções de modelo. |
| [01-Modelo de Documentação de Sistema_2.docx](01-Modelo%20de%20Documenta%C3%A7%C3%A3o%20de%20Sistema_2.docx) | Requisitos de cadastro e consulta de receitas | RF-01 a RF-05 preenchidos para receitas; a capa ainda identifica “Aplicativo Bancário”. |

Os dois arquivos registram Kayky Gabriel Silvano Tomé no campo de grupo e uma versão 1.0 datada de 30/06/2026. Essa identificação do documento não elimina os campos ainda incompletos. Embora o repositório se chame Engenharia de Software 2, os rodapés dos modelos trazem “Engenharia de Software I”.

## Documento 1 — Aplicativo bancário

| Identificador | Requisito descrito |
|---|---|
| RF-01 — Cadastrar conta | Nome completo, CPF, telefone, e-mail e senha de no mínimo dez caracteres com maiúsculas, minúsculas, caractere especial e números. |
| RF-02 — Logar na conta | Acesso com CPF e senha e aceite de termos. O texto relacionado prevê redefinição de senha após cinco tentativas de login. |
| RF-03 — Adicionar chave Pix | Cadastro de chave para recebimentos; o texto também menciona depósito em agência ou loteria. |
| RF-04 — Forma de pagamento | Pagamento por Pix, débito ou crédito em até cinco parcelas sem juros. |
| RF-05 — Compartilhar pagamento | Compartilhamento de comprovante; as restrições relacionadas citam PDF e proibição de captura da tela de compartilhamento. |

As tabelas associadas registram exigências como criptografia, segurança, conformidade com a LGPD e conexão com a internet. Os requisitos sistêmicos preenchidos citam resposta rápida, Windows e uso de internet. São **requisitos escritos no documento**, sem implementação ou evidência de atendimento no repositório.

## Documento 2 — Receitas

| Identificador | Requisito descrito |
|---|---|
| RF-01 — Cadastro de Receita | Criar receitas com título, ingredientes, modo de preparo, tempo estimado e categorias. |
| RF-02 — Listagem do Repositório | Mostrar receitas em lista ou grade, com miniatura, título e tempo de preparo, da mais recente para a mais antiga, e abrir detalhes. |
| RF-03 — Busca e Filtragem | Buscar por título, filtrar por categoria e atualizar os resultados enquanto o usuário digita. |
| RF-04 — Edição de Dados | Carregar os valores atuais, confirmar alterações e permitir substituir ou remover a imagem. |
| RF-05 — Exclusão de Item | Excluir com confirmação e retornar à listagem atualizada. |

Os requisitos sistêmicos descrevem identidade visual minimalista em preto, branco e roxo; armazenamento local para uso sem internet; carregamento da lista e dos detalhes em menos de dois segundos; uma base de código para Android e iOS; e compressão de fotos antes do armazenamento.

O documento não escolhe um framework ou um banco de dados. Esses requisitos não demonstram que um aplicativo já foi desenvolvido.

## Estrutura dos modelos

Ambos incluem campos para:

1. Descrição do cliente e público-alvo.
2. Objetivos, justificativas e stakeholders.
3. Viabilidade, estimativas de prazo/custo e restrições.
4. Escopo com roteiro 5W2H e itens fora do escopo.
5. Técnicas de levantamento e necessidades dos usuários.
6. Requisitos funcionais, requisitos não funcionais relacionados e requisitos sistêmicos.

## Pendências visíveis para revisão

- Alinhar a capa do documento `_2` ao conteúdo de receitas.
- Completar cliente, objetivos, stakeholders, viabilidade e escopo; há campos vazios, instruções e exemplos de modelo.
- Definir ou remover os espaços de RF-06 a RF-08, que permanecem com texto orientativo.
- Revisar tabelas com “Escolher um item.” e restrições sem descrição.
- Revisar a repetição da categorização nos itens RNFR-01.2 e RNFR-01.3 do documento de receitas.
- Conferir a identificação da disciplina nos rodapés.

## Como consultar

Abra cada `.docx` em um editor compatível com Word para preservar tabelas e formatação. Use o nome do documento e os identificadores RF/RNFR/RNFS para localizar os requisitos resumidos acima.

Este README foi elaborado a partir do texto dos dois arquivos do próprio repositório. Os documentos foram preservados; exemplos e campos de modelo não foram tratados como decisões finais de projeto.
