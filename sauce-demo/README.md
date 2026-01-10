# 🧪 Testes - Sauce Demo

## 📱 Sobre a Aplicação

**Nome:** Sauce Demo  
**URL:** https://www.saucedemo.com/  
**Tipo:** E-commerce de demonstração  
**Objetivo:** Praticar testes funcionais e automação

---

## 🎯 Escopo dos Testes

Este projeto contém testes para as seguintes funcionalidades:

### ✅ Funcionalidades Testadas

- **Login**
  - Login com credenciais válidas
  - Login com credenciais inválidas
  - Login com usuário bloqueado
  - Validação de campos obrigatórios

- **Produtos**
  - Visualização de lista de produtos
  - Ordenação de produtos
  - Visualização de detalhes do produto
  - Adição de produtos ao carrinho

- **Carrinho de Compras**
  - Adicionar produtos
  - Remover produtos
  - Atualizar quantidades
  - Continuar comprando

- **Checkout**
  - Preenchimento de informações
  - Revisão do pedido
  - Finalização da compra

---

## 👥 Usuários de Teste

A aplicação fornece os seguintes usuários para teste:

| Usuário | Senha | Comportamento |
|---------|-------|---------------|
| `standard_user` | `secret_sauce` | ✅ Usuário padrão sem problemas |
| `locked_out_user` | `secret_sauce` | 🔒 Usuário bloqueado |
| `problem_user` | `secret_sauce` | ⚠️ Usuário com bugs propositais |
| `performance_glitch_user` | `secret_sauce` | 🐌 Usuário com lentidão |
| `error_user` | `secret_sauce` | ❌ Usuário com erros |
| `visual_user` | `secret_sauce` | 👁️ Usuário com problemas visuais |

---

## 📊 Resumo dos Testes

| Categoria | Total de Casos | Pass | Fail | Cobertura |
|-----------|----------------|------|------|-----------|
| Login | 4 | 3 | 1 | 100% |
| Produtos | 3 | 2 | 1 | 100% |
| Carrinho | 2 | 2 | 0 | 100% |
| Checkout | 1 | 1 | 0 | 100% |
| **TOTAL** | **10** | **8** | **2** | **100%** |

---

## 🐛 Bugs Encontrados

Total de bugs identificados: **3**

| ID | Título | Severidade | Status |
|----|--------|-----------|--------|
| [BUG-001](./bug-reports/BUG001-ordenacao-problema.md) | Ordenação de produtos incorreta | 🟠 Alta | 🆕 Novo |
| [BUG-002](./bug-reports/BUG002-imagem-produto.md) | Imagem de produto quebrada | 🟡 Média | 🆕 Novo |
| [BUG-003](./bug-reports/BUG003-usuario-bloqueado.md) | Mensagem de erro genérica | 🟢 Baixa | 🆕 Novo |

---

## 📂 Estrutura de Arquivos

```
sauce-demo/
├── README.md (este arquivo)
├── test-cases/
│   ├── TC001-login-valido.md
│   ├── TC002-login-invalido.md
│   ├── TC003-adicionar-produto.md
│   ├── TC004-remover-produto.md
│   ├── TC005-ordenar-produtos.md
│   ├── TC006-visualizar-detalhes.md
│   ├── TC007-checkout-sucesso.md
│   ├── TC008-validacao-campos.md
│   ├── TC009-usuario-bloqueado.md
│   └── TC010-carrinho-vazio.md
├── bug-reports/
│   ├── BUG001-ordenacao-problema.md
│   ├── BUG002-imagem-produto.md
│   └── BUG003-usuario-bloqueado.md
├── test-plan/
│   └── plano-teste-sauce-demo.md
└── evidences/
    └── screenshots/
```

---

## 🔍 Casos de Teste Detalhados

### Login
- [TC001](./test-cases/TC001-login-valido.md) - Login com credenciais válidas
- [TC002](./test-cases/TC002-login-invalido.md) - Login com credenciais inválidas
- [TC009](./test-cases/TC009-usuario-bloqueado.md) - Login com usuário bloqueado
- [TC008](./test-cases/TC008-validacao-campos.md) - Validação de campos obrigatórios

### Produtos e Carrinho
- [TC003](./test-cases/TC003-adicionar-produto.md) - Adicionar produto ao carrinho
- [TC004](./test-cases/TC004-remover-produto.md) - Remover produto do carrinho
- [TC005](./test-cases/TC005-ordenar-produtos.md) - Ordenação de produtos
- [TC006](./test-cases/TC006-visualizar-detalhes.md) - Visualizar detalhes do produto

### Checkout
- [TC007](./test-cases/TC007-checkout-sucesso.md) - Checkout completo com sucesso
- [TC010](./test-cases/TC010-carrinho-vazio.md) - Tentativa de checkout com carrinho vazio

---

## 🛠️ Ferramentas Utilizadas

- **Documentação:** Markdown
- **Gestão de Bugs:** GitHub Issues
- **Evidências:** Screenshots (PNG)
- **Navegador:** Google Chrome 120

---

## 📈 Métricas de Qualidade

- **Taxa de Sucesso:** 80% (8 de 10 casos passaram)
- **Bugs por Funcionalidade:** 0,3 (3 bugs em 10 testes)
- **Cobertura de Testes:** 100% das funcionalidades principais

---

## 🚀 Próximos Passos

- [ ] Automatizar casos de teste com Cypress
- [ ] Testar responsividade mobile
- [ ] Adicionar testes de performance
- [ ] Criar testes de API

---

## 📝 Notas

- Todos os testes foram executados em ambiente desktop
- Resolução utilizada: 1920x1080
- Navegador: Chrome versão 120
- Data da última execução: [DD/MM/AAAA]

---

[← Voltar ao README principal](../README.md)