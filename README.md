# 🧭 Sistema de Gestão - Zend Framework & Doctrine

Aplicação completa de **gestão administrativa**, desenvolvida com **PHP (Zend Framework)**, **Doctrine ORM**, **JavaScript** e **Bootstrap**.  
O sistema foi criado para **gerenciar membros e funcionários**, oferecendo um **CRUD completo** (criação, leitura, atualização e exclusão) com interface simples e responsiva.

---

## ⚙️ Principais Funcionalidades

- 👥 **Cadastro e gerenciamento de membros e funcionários**
- ✏️ **CRUD completo** com formulários validados e feedback visual
- 🔍 **Listagem e busca dinâmica** de registros
- 🗂️ **Organização por categorias e status**
- 🧾 **Relatórios básicos e listagens organizadas**
- 💾 **Integração com banco de dados via Doctrine ORM**
- 🎨 **Interface construída com Bootstrap**, garantindo responsividade e boa usabilidade

---

## 🧰 Tecnologias Utilizadas

- **PHP (Zend Framework 2)**
- **Doctrine ORM**
- **JavaScript**
- **Bootstrap**
- **HTML5 / CSS3**
- **Composer**

---

## 🚀 Instalação e Execução

### Clonar o projeto
```bash
git clone https://github.com/seuusuario/seu-repositorio.git
cd seu-repositorio
```

### Instalar dependências
```
composer install
```

### Rodar servidor local
```
php -S 0.0.0.0:8080 -t public/ public/index.php
```

### Acesse no navegador:
👉 http://localhost:8080

---

### 🧩 Estrutura do Sistema

- module/Application → Controladores, modelos e views principais
- config/ → Arquivos de configuração do Zend e banco de dados
- public/ → Arquivos públicos (CSS, JS, imagens, index.php)
- vendor/ → Dependências instaladas pelo Composer

---

### 💡 Destaques Técnicos

- Implementação de MVC com Zend Framework
- Uso de Doctrine para mapeamento objeto-relacional
- Camadas bem definidas de Model, Controller e View
- Separação de responsabilidades e injeção de dependências
- Design responsivo com Bootstrap
- Boas práticas de organização e segurança no backend

---

### 📌 Observações
Este projeto foi desenvolvido com foco em boas práticas de back-end com PHP, explorando a estrutura modular e flexível do Zend Framework.
Apesar de ser um projeto de estudo, ele reflete a arquitetura típica de sistemas administrativos reais.
