# Casos de Teste – Login

## CT-01 – Login com credenciais válidas
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar a tela de login
2. Informar usuário válido
3. Informar senha válida
4. Clicar em "Entrar"

**Resultado esperado:** Usuário autenticado com sucesso e redirecionado para a home.

---

## CT-02 – Login com senha inválida
**Pré-condição:** Usuário cadastrado  
**Passos:**
1. Acessar a tela de login
2. Informar usuário válido
3. Informar senha inválida
4. Clicar em "Entrar"

**Resultado esperado:** Mensagem de erro informando credenciais inválidas.

---

## CT-03 – Login com campos vazios
**Pré-condição:** Nenhuma  
**Passos:**
1. Acessar a tela de login
2. Não preencher usuário e senha
3. Clicar em "Entrar"

**Resultado esperado:** Sistema deve validar campos obrigatórios.
