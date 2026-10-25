# Organização e manutenção

## Critérios adotados

Os arquivos originais foram copiados sem alterar nomes ou conteúdo. A classificação foi feita pela localização e pelos nomes existentes. O DWG do transformador foi separado das referências de motores. A pasta original na Área de Trabalho foi preservada.

## Atualizações

1. Edite o arquivo na pasta correspondente à sua disciplina.
2. Quando houver alteração no memorial, revise e gere novamente seu PDF pelo editor utilizado.
3. Confira as alterações com `git status` e registre uma revisão com mensagem descritiva.
4. Atualize o inventário se arquivos forem adicionados, removidos ou alterados. Os hashes atuais documentam a importação inicial.

Evite duplicações como `final`, `final2` e `novo`: use o histórico do Git. Arquivos DWG, DOCX e PDF são binários e não permitem comparação textual útil no Git; descreva as mudanças nos commits.

## Pendências para completar o projeto

- Revisar tecnicamente os documentos e desenhos.
- Identificar a finalidade do documento DS11417441.pdf pelo conteúdo.
- Confirmar se há arquivos editáveis dos estudos de luminotécnica.
- Confirmar a revisão vigente do memorial e sua correspondência com o PDF.
- Verificar quais memórias de cálculo, quadros de cargas, diagramas, especificações e listas de materiais ainda precisam ser incluídos.
- Definir responsáveis, revisões e critérios de aprovação.
- Definir com o proprietário a visibilidade e o serviço de hospedagem antes de publicar o repositório.

## Publicação futura

O repositório pode ser conectado a um remoto após a escolha do destino. Para arquivos grandes ou revisões frequentes dos binários, avaliar Git LFS antes da publicação e conferir os limites do serviço escolhido.
