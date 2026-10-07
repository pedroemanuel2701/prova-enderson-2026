## UC1 - Abrir bilhete
    `POST /bilhete`
    ```json
        {
            "id": 1,
            "placa": "ABC1D23",
            "entrada": "<ISO-8601 com fuso -03:00>",
            "status": "aberto"
        }
    ´´´

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
    ´´´