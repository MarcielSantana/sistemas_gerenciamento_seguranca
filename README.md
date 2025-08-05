# 🛡️ Sistema de Gerenciamento de Segurança – Indústrias Wayne

Este é um projeto desenvolvido como parte do curso de Programação, com o objetivo de aplicar conceitos de autenticação, autorização, CRUD de dados e dashboard visual. O sistema simula o controle de segurança das instalações das **Indústrias Wayne**, permitindo o gerenciamento de acesso e recursos internos.

## 📌 Funcionalidades

- ✅ Autenticação de usuários
- ✅ Controle de acesso baseado em permissões (funcionário, gerente, administrador)
- ✅ Cadastro, edição e remoção de recursos internos:
  - Equipamentos
  - Veículos
  - Dispositivos de segurança
- ✅ Dashboard visual com dados e gráficos

## 👥 Tipos de Usuários

| Tipo de Usuário         | Permissões Principais                               |
|-------------------------|-----------------------------------------------------|
| Funcionário             | Visualizar informações e status dos recursos        |
| Gerente                 | Visualizar e editar recursos                        |
| Administrador de Segurança | Controle total (CRUD completo + usuários)      |

## 🗂️ Estrutura das Páginas

- Página de Login
- Dashboard de Segurança
- Gerenciamento de Recursos
- Cadastro de Usuários (somente admin)
- Página de Logout

## 🛠️ Tecnologias Utilizadas

- HTML, CSS e JavaScript
- Python com Flask
- SQLite (ou MySQL)

## 🗃️ Estrutura do Banco de Dados (inicial)

- `usuarios (id, nome, email, senha_hash, tipo)`
- `recursos (id, tipo, nome, status, detalhes)`
- `logs_atividades (id, usuario_id, acao, data_hora)`

## 📊 Dashboard

- Total de recursos por categoria
- Status dos recursos (ativo, manutenção, inativo)
- Atividades recentes no sistema
- Gráficos ilustrativos (pizza, barras)
