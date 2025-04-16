# 🔓 Broken Access Control (BAC) - Estudos em Segurança da Informação

Este repositório contém anotações, laboratórios e exemplos práticos relacionados à vulnerabilidade **Broken Access Control**, que ficou em **1º lugar no Top 10 da OWASP 2021**.

## 🧠 O que é Broken Access Control?

Broken Access Control (BAC) acontece quando o sistema não verifica corretamente **quem pode acessar o quê**, permitindo que usuários comuns tenham acesso não autorizado a áreas ou ações restritas (ex: painel de admin, exclusão de contas, alteração de permissões etc).

## 📚 Conteúdo abordado:

- Conceitos básicos de controle de acesso
- Analogia do cookie como "crachá virtual"
- Como funciona o envio de cookies/sessionID nas requisições
- Exploração com ferramentas como **Burp Suite**
- Acesso indevido via:
  - Manipulação de cookies (`role=admin`)
  - URLs previsíveis (ex: `/admin`, `/delete-user`)
  - Parâmetros ocultos no HTML ou no código
- Testes práticos com labs da **PortSwigger Web Security Academy**

## 🧪 Labs realizados:

| Lab | Descrição |
|-----|-----------|
| ✔️ Unprotected admin functionality with unpredictable URL | Acesso ao painel de admin via inspeção de código |
| ✔️ User deletion via manipulated cookie | Exclusão de usuário alterando valor de cookie |
| ✔️ Access control via robots.txt | Exploração de rota escondida no `robots.txt` |

## 🛠️ Ferramentas utilizadas:

- [Burp Suite](https://portswigger.net/burp) – interceptação de requisições
- Navegador (DevTools) – inspeção de elementos, cookies e headers
- Kali Linux – ambiente de testes
- PortSwigger Labs – simulação de cenários reais

## ✅ O que aprendi até agora:

- Como o controle de acesso deve ser feito no back-end
- Como **não confiar em dados do cliente** (cookies, headers, parâmetros)
- Que segurança é contínua: precisa de testes, monitoramento e revisão constante
- A importância do **hardening** e da segmentação de acesso

---

📌 Em construção — Este repositório será atualizado com novos laboratórios e estudos da área de segurança ofensiva.

---
