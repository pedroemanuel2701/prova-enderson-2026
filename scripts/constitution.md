## UC1 - Abrir bilhete
    `POST /bilhete`
    ```json
        {
            "id": 1,
            "placa": "ABC1D23",
            "entrada": "<ISO-8601 -03:00>",
            "status": "aberto"
        }
    ```

## UC2 - Encerrar bilhete

    POST /bilhetes/{id}/encerramento
    ```json
        {
            "id": 1,
            "placa": "ABC1D23",
            "entrada": "...",
            "saida": "...",
            "minutos": 95,
            "valor_centavos": 1250
        }
    ```
    
## UC3 - Listar ativos
    `GET /bilhetes/ativos`

## UC4 - Encerrar bilhete
    `GET /relatorios/diario?data=AAAA-MM-DD`

## UC5 - Cancelar bilhete
    `POST /bilhetes/{id}/cancelamento`

## UC6 - Histórico por placa
    `GET /bilhetes?placa=ABC1D23`

## UC7 - Tolerância gratuita

## UC8 - Uma vaga por placa
    `POST /bilhetes`

