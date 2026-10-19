# Casos de Teste — Ministério da Excelência

## CT-001 — Adicionar momento
**Objetivo:** verificar se é possível adicionar um momento à programação.

**Pré-condição:** aplicativo aberto na tela de programação.

**Passos:**
1. Adicionar um novo momento.
2. Verificar se ele aparece na programação.

**Resultado esperado:** o novo momento deve aparecer na programação.

**Resultado obtido:** o momento foi adicionado a programmação corretamente e apareceu na programação.

**Status:** Aprovado.

---

## CT-002 — Excluir momento
**Objetivo:** verificar se é possível excluir um momento.

**Pré-condição:** programação com pelo menos dois momentos.

**Passos:**
1. Excluir um dos momentos.
2. Verificar a programação.

**Resultado esperado:** somente o momento selecionado deve ser excluído.

**Resultado obtido:**  O momento foi excluído corretamente e deixou de aparecer na programação.


**Status:** Aprovado.

---

## CT-003 — Alterar ordem dos momentos
**Objetivo:** verificar se a ordem dos momentos pode ser alterada.

**Pré-condição:** programação com pelo menos dois momentos.

**Passos:**
1. Mover um momento para outra posição.
2. Verificar a sequência apresentada.

**Resultado esperado:** os momentos devem aparecer na ordem escolhida.

**Resultado obtido:** **Resultado obtido:** A reordenação manual não funcionou corretamente. Ao clicar nos pontos de movimentação ou tentar arrastar os momentos,
 eles se movimentavam desordenadamente.
Foi possível alterar a ordem utilizando a opção de ordenar por horário.

**Status:** Reprovado.

---

## CT-004 — Selecionar somente vídeo
**Objetivo:** verificar o comportamento da opção "Somente o vídeo (sem fala)".

**Pré-condição:** programação com um momento que ofereça essa opção.

**Passos:**
1. Selecionar a opção "Somente o vídeo (sem fala)".
2. Verificar o campo de nome da pessoa.

**Resultado esperado:** o campo de nome deve ficar desabilitado.


**Resultado obtido:** Ao selecionar a opção “Somente vídeo (sem fala)”, o campo nome de pessoasficou desabilitado 
e o comportamento apareceu corretamente na prévia do cronograma.

**Status:** Aprovado.



---

## CT-005 — Limpar programação
**Objetivo:** verificar se o sistema solicita confirmação antes de limpar os dados.

**Pré-condição:** programação com informações preenchidas.

**Passos:**
1. Acionar a opção "Limpar tudo".
2. Verificar se aparece uma solicitação de confirmação.
3. Cancelar a operação.

**Resultado esperado:** o sistema deve pedir confirmação e manter os dados se o usuário cancelar.

**Resultado obtido:** O aplicativo solicitou confirmação antes de limpar a programação. Após a confirmação, os momentos foram removidos corretamente.

**Status:** Aprovado.

## CT-006 — Verificar funcionamento offline

**Objetivo:** verificar se o aplicativo pode ser utilizado sem conexão com a internet e se os dados permanecem salvos após reabrir o arquivo.

**Pré-condição:** arquivo `index.html` disponível no computador e aplicativo aberto no Microsoft Edge.

**Passos:**
1. Abrir o aplicativo no Microsoft Edge.
2. Desligar a conexão com a internet.
3. Adicionar um momento à programação.
4. Fechar a aba do aplicativo.
5. Abrir novamente o arquivo `index.html` no Microsoft Edge.
6. Verificar se o momento adicionado continua na programação.

**Resultado esperado:** o aplicativo deve permitir a utilização sem internet e manter o momento registrado após ser fechado e aberto novamente.

**Resultado obtido:** O aplicativo abriu no Microsoft Edge sem conexão com a internet, permitiu adicionar um momento e manteve o registro após fechar e reabrir o arquivo HTML.

**Status:** Aprovado.