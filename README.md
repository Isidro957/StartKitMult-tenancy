# 🚀 StartKit Multi-Tenancy (Laravel)

Este repositório é um **StartKit profissional** para criação de sistemas **SaaS Multi-Tenant** usando **Laravel**. Ele serve como base reutilizável para iniciar novos projetos sem repetir configurações e estruturas comuns.

---

## 🎯 Objetivo do StartKit

* Fornecer uma base sólida para projetos **multi-tenant**
* Reduzir tempo de configuração inicial
* Padronizar arquitetura e boas práticas
* Facilitar criação de novos projetos SaaS

> ⚠️ **Importante:** Este repositório **não é um projeto final**. Ele deve ser **copiado** para iniciar novos sistemas.

---

## 🧱 Tecnologias Utilizadas

* **PHP 8+**
* **Laravel 10+**
* **MySQL / MariaDB**
* **Laravel Sanctum** (autenticação API)
* **MVC (Model-View-Controller)**
* **Multi-Tenancy** (por empresa)

---

## 🗂 Estrutura do Projeto

```
app/
 ├── Http/
 │   ├── Controllers/
 │   └── Middleware/
 ├── Models/

config/
database/
 ├── migrations/
 ├── seeders/

routes/
 ├── web.php
 └── api.php

resources/
public/
storage/
```

---

## 🧠 Conceito de Multi-Tenancy

Este StartKit foi pensado para sistemas onde:

* Cada **empresa (tenant)** possui seus próprios dados
* O sistema pode usar:

  * banco único com identificação de tenant, ou
  * múltiplos bancos de dados (um por empresa)

A lógica de isolamento é feita através de **middleware**, **models** e **configurações dedicadas**.

---

## 🧪 O que já vem configurado

✅ Estrutura base Laravel
✅ Organização MVC
✅ Migrations iniciais
✅ Seeders de exemplo
✅ Configurações prontas para expansão

---

## ❌ O que NÃO deve ser feito

❌ Não usar este repositório diretamente como projeto final
❌ Não adicionar regras de negócio específicas
❌ Não versionar arquivos sensíveis (`.env`)

---

## ▶️ Como usar este StartKit em um novo projeto

### 1️⃣ Copiar o StartKit

```bash
cp -r StartKitMult-tenancy NovoProjeto
```

### 2️⃣ Remover vínculo Git

```bash
rm -rf .git
```

### 3️⃣ Criar um Git novo

```bash
git init
git add .
git commit -m "Inicialização do projeto a partir do StartKit"
```

### 4️⃣ Conectar ao repositório do projeto

```bash
git remote add origin https://github.com/SEU_USUARIO/NovoProjeto.git
git branch -M main
git push -u origin main
```

---

## 🧑‍💻 Público-alvo

* Estudantes de desenvolvimento
* Projetos acadêmicos (PAP)
* Desenvolvedores iniciantes e intermédios
* Sistemas SaaS em fase inicial

---

## 📌 Boas práticas recomendadas

* Criar documentação própria no projeto final
* Manter o StartKit limpo e genérico
* Versionar melhorias no StartKit separadamente

---

## 📄 Licença

Este StartKit é de uso **educacional e profissional**. Pode ser adaptado conforme a necessidade do projeto.

---

✍️ **Autor:** Isidro Manuel
📅 **Ano:** 2025
📍 **Projeto acadêmico / profissional**
