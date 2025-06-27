# Casos de Teste - Feature Checkout de Resumo de Compra

## Pré-condições
- Acessar a página de Checkout de Resumo de Compra do sistema

---

## Caso de Teste 1 - Visualizar todas as informações do resumo da compra (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 1.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 1.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 1.3 | Preencher todos os campos e clicar em continuar | Usuário é redirecionado para tela de checkout de resumo de compra | Passou |
| 1.4 | Verificar informações do resumo da compra | Exibir nome, quantidade, preço do produto de cada produto | Passou |
| 1.5 | Visualizar valor total da compra | Exibir soma dos produtos + entrega | Passou |

---

## Caso de Teste 2 - Cancelar o pedido da compra (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 2.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 2.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 2.3 | Preencher todos os campos e clicar em continuar | Usuário é redirecionado para tela de checkout de resumo de compra | Passou |
| 2.4 | Verificar informações do resumo da compra | Exibir nome, quantidade, preço do produto de cada produto | Passou |
| 2.5 | Visualizar valor total da compra | Exibir soma dos produtos + entrega | Passou |
| 2.6 | Clicar no botão de cancelar | Pedido é descartado e usuário é redirecionado para tela inicial de produtos | Passou |

---

## Caso de Teste 3 - Finalizar o pedido da compra (Positivo)

| Passo | Ação | Resultado Esperado | Status |
|-------|------|---------------------|--------|
| 3.1 | Logar com o usuário: `standard_user` e senha: `secret_sauce` | Usuário logado com sucesso e redirecionado para o catálogo | Passou |
| 3.2 | Clicar no botão de checkout no carrinho | Usuário é redirecionado para tela de checkout de informações | Passou |
| 3.3 | Preencher todos os campos e clicar em continuar | Usuário é redirecionado para tela de checkout de resumo de compra | Passou |
| 3.4 | Verificar informações do resumo da compra | Exibir nome, quantidade, preço do produto de cada produto | Passou |
| 3.5 | Visualizar valor total da compra | Exibir soma dos produtos + entrega | Passou |
| 3.6 | Clicar no botão de finalizar | Usuário é redirecionado para tela final com mensagem de confirmação do pedido | Passou |
