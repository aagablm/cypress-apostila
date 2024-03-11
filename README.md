# Teste Cypress

```markdown
O que você vai aprender

- Listas de Cursos
- Primeiros Passos
- Seletores e elementos
- Asserções e validações
```
## Lista de Cursos

* [Talking About Testing](https://talkingabouttesting.coursify.me/courses/introducao-aos-testes-automatizados) - Curso gratuito de introdução aos testes automatizados
* [Agilizei](https://app.agilizei.com/pt) - Curso gratuito ensinando os primeiros passos
* [Pedro Hyvo](https://github.com/pedrohyvo/cypress-docs-pt-br) - Projeto com a tradução da documentação oficial do Cypress
  
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
