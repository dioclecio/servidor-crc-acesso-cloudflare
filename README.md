# Acesso remoto para servidor CRC

Esse serviço permite que o servidor do CRC seja acessado pelo Cloudflare

Dentro da pasta docker-compose devemos criar um arquivo .env com o conteúdo da seguinte forma:
```
TOKEN="<token passado pelo Cloudflare>"
```

No Cloudflare, devemos definir o serviço que será direcionado. Exemplo:

![Definição do Cloudflare](<img/imagem-capturada-001.png>)