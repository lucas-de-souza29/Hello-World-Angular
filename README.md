# Hello World Angular

[![Docker Image](https://img.shields.io/docker/pulls/lucasdesouza29/hello-world-angular)](https://hub.docker.com/r/lucasdesouza29/hello-world-angular)
[![GitHub License](https://img.shields.io/github/license/lucasdesouza29/hello-world-angular)](LICENSE)

Aplicação Angular de exemplo com Docker.

## 🚀 Como Executar

```bash
# Via Docker
docker run -p 8080:80 lucasdesouza29/hello-world-angular:latest

# Localmente
npm install
ng serve
```

## 🛠 Tecnologias
- Angular 17+
- Docker
- Nginx
- SCSS

## 📂 Estrutura
```
hello-world-angular/
├── src/
│   └── app/          # Componentes principais
├── Dockerfile        # Configuração de produção
├── nginx.conf        # Configuração do servidor web
└── angular.json      # Configuração do workspace
```
