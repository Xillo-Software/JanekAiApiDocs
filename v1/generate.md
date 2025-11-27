# Generate Endpoint

## Definition
Endpoint: `api/v1/generate`<br>
Request Method: `POST`<br>
Request Body Struct: [ApiGenerateRequest](/v1/Structures/ApiGenerateRequest.md)<br>
Response Body Struct: [ApiGenerateResponse](/v1/Structures/ApiGenerateResponse.md)

Provides a simple, programmatically controlled HTTP Api for text Generation

## Examples

```bash
curl "ailabs.clrmsg.pl/api/v1/generate" \
-X POST \
-H "X-Api-Key: <Your Api Key>" \
-H "Content-Type: application/json"
-d "<Request>"
```


## Posible Errors

Refer [Common Errors](/v1/commonerrors.md)

|  HTTP Code  |  Error Text    |  Cause  |
|-------------|----------------|---------|
|  400        |  Invalid body  |  Generate request not folowing the [ApiGenerateRequest](/v1/Structures/ApiGenerateRequest.md) stuct
|  400        |  Prompt was empty  |  prompt field of [ApiGenerateRequest](/v1/Structures/ApiGenerateRequest.md) was empty or contained only invalid characters