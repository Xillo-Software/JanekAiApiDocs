# ApiGenerateRequest Struct

## Fields

|  Name                 |  Type    |  Required  |  Default  |  Description  |
|-----------------------|----------|------------|-----------|---------------|
|  prompt               |  string  |  yes       |  null     |  The prompt you want to tell the ai  |
|  model                |  string  |  yes       |  null     |  The model you want to use [Refer](/v1/models.md)  |
|  disable_translation  |  bool    |  no        |  false    |  Change to true if you want the raw English response  |