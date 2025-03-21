# linux-projeto1-iac

# 💻 Projeto: Infraestrutura como Código (IaC) - Linux

Este projeto tem como objetivo automatizar a criação da estrutura de usuários, grupos e diretórios no sistema Linux, utilizando **Shell Script**.

Com esse script, é possível configurar rapidamente um ambiente de trabalho padronizado em qualquer máquina Linux, ideal para empresas ou laboratórios.

---

## 🚀 Funcionalidades

- Criação de diretórios:
  - `/publico`, `/adm`, `/ven`, `/sec`

- Criação de grupos de usuários:
  - `GRP_ADM`, `GRP_VEN`, `GRP_SEC`

- Criação de usuários e associação aos respectivos grupos

- Configuração de permissões:
  - Diretórios com acesso restrito por grupo
  - Diretório `/publico` acessível a todos

---

## 📁 Estrutura Criada

```bash
/publico  -> Acesso liberado a todos os usuários
/adm      -> Acesso exclusivo do grupo GRP_ADM
/ven      -> Acesso exclusivo do grupo GRP_VEN
/sec      -> Acesso exclusivo do grupo GRP_SEC
