# Critérios de Aceitação

## CA-001 — Adicionar momento
- **Dado:** o usuário está montando a programação.
- **Quando:** adiciona um novo momento.
- **Então:** o novo momento deve aparecer na programação.

## CA-002 — Excluir momento
- **Dado:** existe um momento na programação.
- **Quando:** o usuário o exclui.
- **Então:** o momento deve desaparecer, sem excluir os demais.

## CA-003 — Alterar ordem
- **Dado:** existem vários momentos na programação.
- **Quando:** o usuário altera a ordem.
- **Então:** os momentos devem aparecer na sequência escolhida.

## CA-004 — Fixar horário
- **Dado:** um horário foi fixado.
- **Quando:** outro momento tem seu horário alterado.
- **Então:** o horário fixado deve permanecer inalterado.

## CA-005 — Somente vídeo
- **Dado:** a opção "Somente o vídeo (sem fala)" está disponível.
- **Quando:** o usuário seleciona essa opção.
- **Então:** o campo de nome da pessoa deve ficar desabilitado.

## CA-006 — Limpar programação
- **Dado:** existem informações preenchidas.
- **Quando:** o usuário solicita a limpeza.
- **Então:** o sistema deve pedir confirmação antes de apagar os dados.

## CA-007 — Visualizar programação
- **Dado:** a programação foi preenchida.
- **Quando:** o usuário abre a visualização.
- **Então:** o sistema deve apresentar a programação para conferência.