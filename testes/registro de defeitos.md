# Registro de Defeitos — Ministério da Excelência

## Objetivo
Registrar problemas encontrados durante a execução dos testes do aplicativo.

## Modelo de registro

### DEF-001 — Título do defeito
- **Caso de teste relacionado:** informar o código do teste.
- **Descrição:** explicar o problema encontrado.
- **Passos para reproduzir:** descrever as ações necessárias para encontrar o problema.
- **Resultado esperado:** descrever o comportamento correto.
- **Resultado obtido:** descrever o que aconteceu de fato.
- **Severidade:** Baixa, Média, Alta ou Crítica.
- **Status:** Aberto, Em correção, Em reteste ou Fechado.
- **Evidência:** inserir o nome ou o caminho da captura de tela, quando houver.

## Defeitos encontrados


## DEF-001 — Falha na reordenação manual dos momentos

**Caso de teste relacionado:** CT-003 — Alterar ordem dos momentos.

**Descrição do defeito:** Ao tentar reordenar os momentos manualmente, clicando nos pontos de movimentação ou arrastando-os com o mouse, os itens se movimentam de forma desordenada e não obedecem ao comando do usuário.

**Resultado esperado:** Os momentos devem ser movidos para a posição desejada pelo usuário, mantendo a ordem selecionada.

**Resultado obtido:** A movimentação manual apresentou comportamento desordenado. A alteração da ordem só foi possível utilizando a opção de ordenar por horário.

**Severidade sugerida:** Média — a funcionalidade de reordenação manual está comprometida, mas existe uma alternativa para ordenar por horário.

**Status:** Aberto.

**Evidência:** testes/evidencias/DEF-001.mp4

