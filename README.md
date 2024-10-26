# PoC do Terraform

Atividade feita em sala de aula no Mackenzie para fins academicos com terraform.<br>
Esse projeto Terraform é voltado para o ambiente em cloud da AWS.<br>
Por questões de boas praticas o arquivo contendo as secrets do projeto não foi versionado nesse repositório, entretanto, abaixo deixo o modelo de autenticação que foi utilizado para ter acesso a conta utilizada na AWS:

```
provider "aws" { 
access_key = "SUA-CHAVE-DE-ACESSO"
secret_key = "SEU-SECRET"
token = "SEU-TOKEN-DE-ACESSO"
region = "us-east-1" 
}
```