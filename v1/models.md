# Models Endpoint

## Definition
Endpoint: `api/v1/models`<br>
Request Method: `GET`<br>
Request Body Struct: `None`<br>
Response Body Struct: [ApiModelsResponse](/v1/Structures/ApiModelsResponse.md)

Provides a simple response with avaible models

## Examples

```bash
curl "ailabs.clrmsg.pl/api/v1/models" \
-X GET \
-H "X-Api-Key: <Your Api Key>"
```


## Posible Errors

Refer [Common Errors](/v1/commonerrors.md)