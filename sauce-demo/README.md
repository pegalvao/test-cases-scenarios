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

---

## 👥 Usuários de Teste

A aplicação fornece os seguintes usuários para teste:

| Usuário | Senha | Comportamento |
|---------|-------|---------------|
| `standard_user` | `secret_sauce` | ✅ Usuário padrão sem problemas |
| `test_user` | `secret_sauce` | ✅ Usuário inválido não consegue acessar|

---

## 📊 Resumo dos Testes

| Categoria | Total de Casos | Pass | Fail | Cobertura |
|-----------|----------------|------|------|-----------|
| Login | 6 | 2 |  | 33,34% |
| Produtos | 0 | 0| 0 | 0% |
| Carrinho | 0 | 0| 0 | 0% |
| Checkout | 0 | 0| 0 | 0% |
| **TOTAL** | **6** | **2** | **** | **33,34** |

---

## 🐛 Bugs Encontrados

Total de bugs identificados: **0**

| ID | Título | Severidade | Status |
|----|--------|-----------|--------|

---

## 📂 Estrutura de Arquivos

```
sauce-demo/
├── README.md (este arquivo)
├── test-cases/
│   ├── TC1-login-valido.md
│   
├── bug-reports/
│   
└── evidences/
    └── screenshots/
```

## 🔍 Casos de Teste Detalhados

### Login
- [TC1](./test-cases/TC1-Login-valido.md) - Login com credenciais válidas
- [TC2](./test-cases/TC2-%20Login-usuario-invalido.md) - Login com credenciais inválidas

### Produtos e Carrinho

### Checkout


---

## 🛠️ Ferramentas Utilizadas

- **Documentação:** Markdown
- **Gestão de Bugs:** GitHub Issues
- **Evidências:** Screenshots (PNG)
- **Navegador:** Google Chrome 

---

## 📈 Métricas de Qualidade

- **Taxa de Sucesso:** 100 % (1 de 1 caso passou)
- **Bugs por Funcionalidade:**  0 (bugs em 1 teste)
- **Cobertura de Testes:** ?% das funcionalidades principais

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
- Navegador: Chrome versão 135
- Data da última execução: [11/01/2026]

---

[← Voltar ao README principal](../README.md)