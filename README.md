# Teste Cypress

```markdown
O que você vai aprender

- Primeiros Passos
- Seletores e elementos
- Asserções e validações
```

## Primeiros Passos

### Estrutura básica
A estrutura básica do Cypress envolve o uso de `describe` e `it` para organizar e escrever seus testes.

#### `Describe` é usado para agrupar testes relacionados. Ele cria um bloco de testes que podem ser aninhados conforme necessário.

#### `It` é usado para definir um caso de teste individual. Cada it representa um cenário específico que você deseja testar.

Exemplo de como usá-los juntos:

```bash
describe('Testes de Login', () => {
  it('Deve permitir login com credenciais válidas', () => {
    // Seu código de teste para login
  });

  it('Deve exibir mensagem de erro para credenciais inválidas', () => {
    // Seu código de teste para credenciais inválidas
  });
});

```
