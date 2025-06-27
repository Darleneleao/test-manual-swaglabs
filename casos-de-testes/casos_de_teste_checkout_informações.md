
# Casos de Teste - Feature Checkout de Informações

## Pré-condições
- Acessar a página de Checkout de Informações do sistema

---

## Caso de Teste 1 - Preencher todos os campos do endereço (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 1.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 1.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 1.3 | Digitar nome | - | Passou |
| 1.4 | Digitar sobrenome | - | Passou |
| 1.5 | Digitar CEP | - | Passou |
| 1.6 | Clicar no botão de continuar | Redirecionado para checkout de resumo de compra | Passou |

---

## Caso de Teste 2 - Deixar todos os campos vazios (Negativo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 2.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 2.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 2.3 | Clicar no botão de continuar | Aparece mensagem de erro dizendo que todos os campos são obrigatórios | Passou |

---

## Caso de Teste 3 - Nome vazio (Negativo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 3.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 3.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 3.3 | Digitar sobrenome | - | Passou |
| 3.4 | Digitar CEP | - | Passou |
| 3.5 | Clicar no botão de continuar | Aparece mensagem de erro: "Erro: Nome é obrigatório" | Passou |

---

## Caso de Teste 4 - Sobrenome vazio (Negativo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 4.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 4.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 4.3 | Digitar nome | - | Passou |
| 4.4 | Digitar CEP | - | Passou |
| 4.5 | Clicar no botão de continuar | Aparece mensagem de erro: "Erro: Sobrenome é obrigatório" | Passou |

---

## Caso de Teste 5 - CEP vazio (Negativo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 5.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 5.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 5.3 | Digitar nome | - | Passou |
| 5.4 | Digitar sobrenome | - | Passou |
| 5.5 | Clicar no botão de continuar | Aparece mensagem de erro: "Erro: Código postal é necessário" | Passou |

---

## Caso de Teste 6 - CEP no formato incorreto (Negativo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 6.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Bloqueado |
| 6.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Bloqueado |
| 6.3 | Digitar CEP incorreto | - | Bloqueado |
| 6.4 | Clicar no botão de continuar | Aparece mensagem de erro: "Erro: Código postal é inválido" | Falhou |

---

## Caso de Teste 7 - CEP no formato correto (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 7.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 7.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 7.3 | Digitar CEP correto | - | Passou |
| 7.4 | Clicar no botão de continuar | Redirecionado para checkout de resumo de compra | Passou |

---

## Caso de Teste 8 - Cancelar preenchimento e retornar ao carrinho (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 8.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 8.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 8.3 | Clicar no botão de cancelar | Usuário é retornado para tela de carrinho de compra | Passou |
