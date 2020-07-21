# API 2U Epicspot

**Base URL**: http://phpstack-371980-1373330.cloudwaysapps.com/hotsite/api_2u/api/v1/index.php

# Routes

 - **Method POST**
 - Path: **/**
 - **Consumes type:** application/json
 - **Return type:** application/json
 - **Charset** utf-8
 - **Authentication**:  HTTP Header - Bearer Token
```html
Example:
Authorization: Bearer b9237dfjkdbvidfyu83
``` 
 - Query String Parameters:
 1. *id*

>  **Type**: integer  **required**: false
 2. *endereco*
> **Type**: string  **required**: false
 3. *cidade*
>  **Type**: string  **required**: false
 4. *estado*
> **Type**: string  **required**: false
 5. *bairro*
>  **Type**: string  **required**: false
 6. *cep*
>  **Type**: string  **required**: false
 7. *quartos*
>  **Type**: integer  **required**: false
 8. *valorVendaMin*
>   **Type**: integer  **required**: false
 9. *valorVendaMax*
>   **Type**: integer  **required**: false
 10. *alugar*
>   **Type**: boolean  **required**: false  **1** to TRUE, **0** to
> FALSE
 11. *vender*
>    **Type**: boolean  **required**: false  **1** to TRUE, **0** to
> FALSE
 12. *piscina*
>    **Type**: boolean  **required**: false  **1** to TRUE, **0** to
> FALSE

 Return body:
> Type: **Array**

 ```json
 {
        "id": "12",
        "titulo": "Apto 3 dorms | frente para shopping Shibata",
        "descricao": "Belíssimo Apto 3 dorms com armários planejados, suite, sala dois ambientes, ar condicionado, cozinha com armários planejados, lavabo, wc social, varanda gourmet, 2 vagas de garagem  Excelente localização em frente ao Shopping Shibata, fácil acesso a Dutra e Anel Viário.  Estuda-se permuta de menor valor.  Cauane Ribeiro| Corretora de Imóveis | Creci 199.892-F  (12) <a href=\"#\" class=\"sc-57pm5w-0 XtcoW\">9971... ver número</a> (WhatsApp 24h)",
        "endereco": "Rua Shizuko Iida",
        "cidade": "São José dos Campos",
        "estado": "SP",
        "bairro": "Jardim América",
        "numero": null,
        "complemento": null,
        "cep": "12235051",
        "pais": "BR",
        "quartos": "3",
        "alugar": null,
        "vender": null,
        "valor_aluguel": null,
        "valor_venda": "540000.00",
        "oferta": null,
        "area": "",
        "piscina": null,
        "banheiros": "3",
        "tipo_imovel": "Apartamentos",
        "latitude": "-23.2333917",
        "longitude": "-45.8969557",
        "link_imovel": "https://sp.olx.com.br/vale-do-paraiba-e-litoral-norte/imoveis/apto-3-dorms-frente-para-shopping-shibata-741277086",
        "link_img": "https://img.olx.com.br/images/82/825005635001793.jpg",
        "agente_nome": null,
        "agente_creci": null,
        "agente_img": null,
        "agente_fone": null,
        "agente_email": null,
        "ativo": "1"
    },
 ```

<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoiZXh0ZW5zaW9uczpcbiAgcHJlc2V0Oi
BnZm1cbiIsImhpc3RvcnkiOlstMTYzMTgxNjI4MSwtMTExMTk0
MjcwNywtNTk3NzYwNDUsLTUwNDYyODgsLTg2NDUzMTQzMCwxNj
Q5MjExMTkyLDc2NjAyMTcxOF19
-->