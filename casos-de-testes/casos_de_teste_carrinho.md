# Casos de Teste - Feature Carrinho

## Pré-condições
- Acessar a página de Carrinho do sistema

---

## Caso de Teste 1 - Visualizar produto adicionado no carrinho (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 1.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 1.2 | Clicar em um produto do catálogo | Página de detalhes do produto é exibida | Passou |
| 1.3 | Verificar as informações do produto | Exibir nome, imagem e preço do produto e botão de adicionar | Passou |
| 1.4 | Adicionar o produto no carrinho | Contador do carrinho incrementa em +1 | Passou |
| 1.5 | Clicar no botão de carrinho | Usuário é redirecionado para tela de carrinho | Passou |
| 1.6 | Verificar as informações do produto | Exibir nome, imagem, preço, quantidade e botão de remover | Passou |

---

## Caso de Teste 2 - Excluir produto adicionado ao carrinho (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 2.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 2.2 | Clicar em um produto do catálogo | Página de detalhes do produto é exibida | Passou |
| 2.3 | Verificar as informações do produto | Exibir nome, imagem e preço do produto e botão de adicionar | Passou |
| 2.4 | Adicionar o produto no carrinho | Contador do carrinho incrementa em +1 | Passou |
| 2.5 | Clicar no botão de carrinho | Usuário é redirecionado para tela de carrinho | Passou |
| 2.6 | Clicar no botão de remover produto do carrinho | Contador do carrinho subtrai em -1 ou até zerar | Passou |

---

## Caso de Teste 3 - Botão de continuar comprando mais produtos (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 3.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 3.2 | Clicar em um produto do catálogo | Página de detalhes do produto é exibida | Passou |
| 3.3 | Verificar as informações do produto | Exibir nome, imagem e preço do produto e botão de adicionar | Passou |
| 3.4 | Adicionar o produto no carrinho | Contador do carrinho incrementa em +1 | Passou |
| 3.5 | Clicar no botão de carrinho | Usuário é redirecionado para tela de carrinho | Passou |
| 3.6 | Clicar no botão "Continue Shopping" | Usuário é redirecionado para o catálogo de produtos | Passou |

---

## Caso de Teste 4 - Botão de checkout de produtos (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 4.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 4.2 | Clicar em um produto do catálogo | Página de detalhes do produto é exibida | Passou |
| 4.3 | Verificar as informações do produto | Exibir nome, imagem e preço do produto e botão de adicionar | Passou |
| 4.4 | Adicionar o produto no carrinho | Contador do carrinho incrementa em +1 | Passou |
| 4.5 | Clicar no botão de carrinho | Usuário é redirecionado para tela de carrinho | Passou |
| 4.6 | Clicar no botão de checkout e prosseguir com os pedidos | Usuário é redirecionado para a tela de checkout de informações | Passou |
