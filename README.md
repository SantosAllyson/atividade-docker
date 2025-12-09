# Atividade Docker

Projeto de mini site sobre Docker com CI/CD automático.

## Como executar localmente:

```bash
# Construir a imagem
docker build -t meu-site .

# Executar o container
docker run -d -p 8080:80 meu-site

# Acessar: http://localhost:8080