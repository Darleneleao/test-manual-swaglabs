# Casos de Teste - Feature Produto

## Pré-condições
- Acessar a página de Produto do sistema

---

## Caso de Teste 1 - Visualizar produto disponível (Positivo)

| Passo | Ação                                             | Resultado Esperado                                  | Status |
|-------|--------------------------------------------------|-----------------------------------------------------|--------|
| 1.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 1.2   | Clicar em um produto do catálogo                 | Página de detalhes do produto é exibida             | Passou |
| 1.3   | Verificar as informações do produto              | Exibir nome, imagem, preço do produto e botão de adicionar | Passou |

---

## Caso de Teste 2 - Visualizar produto indisponível (Negativo)

| Passo | Ação                                             | Resultado Esperado                                                  | Status |
|-------|--------------------------------------------------|----------------------------------------------------------------------|--------|
| 2.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo           | Passou |
| 2.2   | Clicar em um produto do catálogo                 | Página de detalhes do produto é exibida                             | Passou |
| 2.3   | Verificar as informações do produto              | Exibir nome, imagem, preço e mensagem de erro: "Produto esgotado / não disponível" | Novo |

---

## Caso de Teste 3 - Adicionar produto no carrinho (Positivo)

| Passo | Ação                                             | Resultado Esperado                        | Status |
|-------|--------------------------------------------------|-------------------------------------------|--------|
| 3.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 3.2   | Clicar em um produto do catálogo                 | Página de detalhes do produto é exibida   | Passou |
| 3.3   | Adicionar o produto no carrinho                  | Contador do carrinho incrementa em +1     | Passou |

---

## Caso de Teste 4 - Remover um produto do carrinho (Positivo)

| Passo | Ação                                             | Resultado Esperado                        | Status |
|-------|--------------------------------------------------|-------------------------------------------|--------|
| 4.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 4.2   | Clicar em um produto do catálogo                 | Página de detalhes do produto é exibida   | Passou |
| 4.3   | Adicionar o produto no carrinho                  | Contador do carrinho incrementa em +1     | Passou |
| 4.4   | Remover o produto do carrinho                    | Contador do carrinho subtrai em -1        | Passou |

---

## Caso de Teste 5 - Filtrar catálogo por ordem crescente alfabética (Positivo)

| Passo | Ação                                                       | Resultado Esperado                                     | Status |
|-------|------------------------------------------------------------|--------------------------------------------------------|--------|
| 5.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 5.2   | Filtrar produtos por ordem crescente alfabética (A a Z)   | Página de catálogo exibe os produtos em ordem crescente alfabética | Passou |

---

## Caso de Teste 6 - Filtrar catálogo por ordem decrescente alfabética (Positivo)

| Passo | Ação                                                       | Resultado Esperado                                     | Status |
|-------|------------------------------------------------------------|--------------------------------------------------------|--------|
| 6.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 6.2   | Filtrar produtos por ordem decrescente alfabética (Z a A) | Página de catálogo exibe os produtos em ordem decrescente alfabética | Passou |

---

## Caso de Teste 7 - Filtrar catálogo por ordem crescente de preço (Positivo)

| Passo | Ação                                                       | Resultado Esperado                               | Status |
|-------|------------------------------------------------------------|--------------------------------------------------|--------|
| 7.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 7.2   | Filtrar produtos por ordem crescente de preço             | Página de catálogo exibe os produtos em ordem crescente de preço | Passou |

---

## Caso de Teste 8 - Filtrar catálogo por ordem decrescente de preço (Positivo)

| Passo | Ação                                                       | Resultado Esperado                               | Status |
|-------|------------------------------------------------------------|--------------------------------------------------|--------|
| 8.1   | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 8.2   | Filtrar produtos por ordem decrescente de preço           | Página de catálogo exibe os produtos em ordem decrescente de preço | Passou |
