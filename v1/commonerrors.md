# Common Error Responses

|  HTTP Code  |  Error Text    |  Cause  |
|-------------|----------------|---------|
|  401        |  Missing X-Api-Key header  |  Request is missing the X-Api-Key header
|  401        |  Invalid Api Key           |  Either Api key is not correct or you've run out of requests on this key
|  404        |  API endpoint not found    |  Request was sent ether with incorrect `HTTP Method` for this path or that api endpoint does not exist
