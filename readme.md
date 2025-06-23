# Sistema de Salas de Reunião

## 🎯 Objetivo

Desenvolver um sistema simples de gestão de salas de reunião e geração de códigos de acesso para convidados. O sistema deve conter:

- Um backend com lógica de negócio e rotas
- Um frontend funcional (interface web simples) para interação

## 🛠️ Funcionalidades

🗂️ Gestão de salas

    ✅ Criar uma nova sala

        - A sala deve ter um nome único

    ❌ Deletar uma sala
    
        - Ao deletar uma sala, os códigos associados também devem ser deletados

    📋 Listar todas as salas existentes

🧑‍🤝‍🧑 Gestão de códigos de acesso

    ✅ Gerar um código único de acesso para uma sala

        - O código deve ser único (ex: UUID, hash ou string aleatória)
        - O código pode ter um apelido opcional
        - Não permitir apelidos duplicados dentro da mesma sala
        - Cada sala pode ter no máximo 4 códigos

    ❌ Deletar um código de acesso

    📋 Listar todos os códigos vinculados a uma sala

🔑 Acesso à sala

    ✅ Entrar em uma sala utilizando um código válido

        - Para acesso à sala deve ser informado nome da sala e código de acesso
        - Se código e sala forem válidos, exibir uma mensagem de confirmação
        - Se código e/ou sala forem inválidos, exibir uma mensagem de erro

# Observações

🔙 Backend

    Pode usar qualquer linguagem/framework

    Os dados podem ser mantidos no sqlite, mysql, sqlserver ou qualquer outro banco de dados relacional

🌐 Frontend

    A frontend pode ser feito com HTML/CSS/JS puro ou com algum framework (React, NextJS, etc.).

🎁 Bônus (não obrigatório)

    Interface responsiva

📦 Entrega

    Suba o código no GitHub
