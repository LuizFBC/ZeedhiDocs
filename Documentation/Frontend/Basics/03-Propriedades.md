# Propriededas

As propriedes de widgets são algumas definições de comportamento dentro da tela de cada uma delas, uma lista delas seria:

* showOnView
    + Recebe: true/false
    + Ação: Visualiza registro no Swipe
    + Exemplo:
    
    ```json
     "showOnView": true
     ```

* showOnList
    + Recebe: true/false
    + Ação: Lista no grid
    + Exemplo:
    
    ```json
     "showOnList": true
     ```

* showOnForm
    + Recebe: true/false
    + Ação: Edita/Inclui registro
    + Exemplo:
    
    ```json
     "showOnForm": true
     ```

* readOnly
    + Recebe: true/false
    + Ação: Se é somente visivel ou passível de edição
    + Exemplo:
    
    ```json
     "readOnly": true
     ```

* isVisible
    + Recebe: true/false
    + Ação: Se o campo é visivel ou não
    + Exemplo:
    
    ```json
     "isVisible": true
     ```

* template
    + Recebe: string da localidade de um template
    + Ação: Define o template da field/widget
    + Exemplo:
    
    ```json
     "template": "field/select-multiple.html"
     ```

* validations
    + Recebe: Objeto com definições de validações
    + Ação: Diz quais validações devem ser feitas pelo campo
    + Tipos de validação:
        + Required
            + Recebe: true/false
    + Exemplos:
    ```json
        "validations": {
            "required": true
        },
    ```