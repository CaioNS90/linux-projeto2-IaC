# 🌐 Script de Deploy - Servidor Apache com Site Estático

## 📄 Descrição

Este script Bash automatiza o processo de atualização de um servidor Linux, instalação do Apache e publicação de um site estático hospedado no GitHub. Ideal para testes de ambiente ou laboratórios de infraestrutura web.

## 🔧 Funcionalidades

- Atualização do servidor (repositórios e pacotes)
- Instalação do servidor web Apache2
- Instalação da ferramenta `unzip`
- Download e extração de um site estático (exemplo educacional da DIO)
- Publicação do site em `/var/www/html`

## 🚀 Requisitos

- Distribuição baseada em Debian (Ubuntu, etc.)
- Acesso root (ou permissões sudo)
- Conexão com a internet

## 📥 Conteúdo da Aplicação

O site baixado vem do repositório:

📦 `https://github.com/denilsonbonatti/linux-site-dio`

Esse repositório contém uma aplicação estática (HTML/CSS/JS) para testes de deploy.

## 🛠️ Como Usar

1. Salve o script como `instala_apache.sh`
2. Dê permissão de execução:
   ```bash
   chmod +x instala_apache.sh
