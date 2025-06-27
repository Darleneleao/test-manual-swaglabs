
# Casos de Teste - Feature Login

## Pré-condições
- Acessar a página de Login do sistema

---

## Caso de Teste 1 - Login com usuário `standard_user` e senha válida (Positivo)

| Passo | Ação                             | Resultado Esperado                                   | Status |
|-------|---------------------------------|----------------------------------------------------|--------|
| 1.1   | Digite o usuário: `standard_user` |                                                    | Passou |
| 1.2   | Digite a senha: `secret_sauce`    |                                                    | Passou |
| 1.3   | Clique no botão de Login          | O usuário é logado com sucesso / Redirecionado para página de produtos | Passou |

---

## Caso de Teste 2 - Login com usuário `standard_user` e senha inválida (Negativo)

| Passo | Ação                             | Resultado Esperado                                                 | Status |
|-------|---------------------------------|------------------------------------------------------------------|--------|
| 2.1   | Digite o usuário: `standard_user` |                                                                  | Passou |
| 2.2   | Digite a senha: `123456`           |                                                                  | Passou |
| 2.3   | Clique no botão de Login          | Mensagem de erro: "nome de usuário e senha não correspondem a nenhum usuário neste serviço" | Passou |

---

## Caso de Teste 3 - Login com usuário `locked_out_user` e senha válida (Negativo)

| Passo | Ação                             | Resultado Esperado                                   | Status |
|-------|---------------------------------|----------------------------------------------------|--------|
| 3.1   | Digite o usuário: `locked_out_user` |                                                    | Passou |
| 3.2   | Digite a senha: `secret_sauce`    |                                                    | Passou |
| 3.3   | Clique no botão de Login          | Mensagem de erro: "Desculpe, este usuário foi bloqueado.." | Passou |

---

## Caso de Teste 4 - Login com usuário `locked_out_user` e senha inválida (Negativo)

| Passo | Ação                             | Resultado Esperado                                                 | Status |
|-------|---------------------------------|------------------------------------------------------------------|--------|
| 4.1   | Digite o usuário: `locked_out_user` |                                                                  | Passou |
| 4.2   | Digite a senha: `123456`           |                                                                  | Passou |
| 4.3   | Clique no botão de Login          | Mensagem de erro: "nome de usuário e senha não correspondem a nenhum usuário neste serviço" | Passou |

---

## Caso de Teste 5 - Login com usuário `problem_user` e senha válida (Positivo)

| Passo | Ação                             | Resultado Esperado                                   | Status |
|-------|---------------------------------|----------------------------------------------------|--------|
| 5.1   | Digite o usuário: `problem_user` |                                                    | Passou |
| 5.2   | Digite a senha: `secret_sauce`    |                                                    | Passou |
| 5.3   | Clique no botão de Login          | O usuário é logado com sucesso / Redirecionado para página de produtos | Passou |

---

## Caso de Teste 6 - Login com usuário `problem_user` e senha inválida (Negativo)

| Passo | Ação                             | Resultado Esperado                                                 | Status |
|-------|---------------------------------|------------------------------------------------------------------|--------|
| 6.1   | Digite o usuário: `problem_user` |                                                                  | Passou |
| 6.2   | Digite a senha: `123456`           |                                                                  | Passou |
| 6.3   | Clique no botão de Login          | Mensagem de erro: "nome de usuário e senha não correspondem a nenhum usuário neste serviço" | Passou |

---

## Caso de Teste 7 - Login com usuário `performance_glitch_user` e senha válida (Positivo)

| Passo | Ação                                       | Resultado Esperado                                   | Status |
|-------|--------------------------------------------|----------------------------------------------------|--------|
| 7.1   | Digite o usuário: `performance_glitch_user` |                                                    | Passou |
| 7.2   | Digite a senha: `secret_sauce`              |                                                    | Passou |
| 7.3   | Clique no botão de Login                    | O usuário é logado com sucesso / Redirecionado para página de produtos | Passou |

---

## Caso de Teste 8 - Login com usuário `performance_glitch_user` e senha inválida (Negativo)

| Passo | Ação                                       | Resultado Esperado                                                 | Status |
|-------|--------------------------------------------|------------------------------------------------------------------|--------|
| 8.1   | Digite o usuário: `performance_glitch_user` |                                                                  | Passou |
| 8.2   | Digite a senha: `123456`                    |                                                                  | Passou |
| 8.3   | Clique no botão de Login                    | Mensagem de erro: "nome de usuário e senha não correspondem a nenhum usuário neste serviço" | Passou |

---

## Caso de Teste 9 - Login com usuário inválido e senha válida (Negativo)

| Passo | Ação                | Resultado Esperado                                                 | Status |
|-------|---------------------|------------------------------------------------------------------|--------|
| 9.1   | Digite o usuário: `user123` |                                                                  | Passou |
| 9.2   | Digite a senha: `secret_sauce` |                                                                | Passou |
| 9.3   | Clique no botão de Login | Mensagem de erro: "nome de usuário e senha não correspondem a nenhum usuário neste serviço" | Passou |

---

## Caso de Teste 10 - Logar com todos os campos em branco (Negativo)

| Passo | Ação                | Resultado Esperado                          | Status |
|-------|---------------------|-------------------------------------------|--------|
| 10.1  | Clique no botão de Login | Senha é necessária / "Nome de usuário é obrigatório" | Passou |

---

## Caso de Teste 11 - Logar com a senha em branco (Negativo)

| Passo | Ação                | Resultado Esperado              | Status |
|-------|---------------------|-------------------------------|--------|
| 11.1  | Digite um usuário válido |                               | Passou |
| 11.2  | Clique no botão de Login | Senha é necessária / "Senha é necessária" | Passou |

---

## Caso de Teste 12 - Logar com o usuário em branco (Negativo)

| Passo | Ação                  | Resultado Esperado                       | Status |
|-------|-----------------------|----------------------------------------|--------|
| 12.1  | Digite a senha válida `secret_sauce` |                                | Passou |
| 12.2  | Clique no botão de Login | Senha é necessária / "Nome de usuário é obrigatório" | Passou |
