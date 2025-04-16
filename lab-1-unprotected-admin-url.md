# Lab 1 – Unprotected Admin Functionality

## 🔍 Objetivo
Acessar funcionalidade administrativa escondida por uma URL imprevisível.

## 💡 Como resolvi
- Usei DevTools (F12) para inspecionar elementos.
- Descobri uma referência a `/admin-panel` no código-fonte.
- Acesse essa URL diretamente → painel admin liberado.
- Excluí usuário através de um botão "Delete".

## 🧠 O que aprendi
Mesmo que a URL seja "escondida", se não houver autenticação e controle de permissão, qualquer usuário pode acessar.
