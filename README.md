# Cypress

```markdown
O que você vai aprender

- Listas de Cursos
- Primeiros Passos
- Selecionando elementos
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

É importante que os testes sejam independentes e que o resultado de um não afete o outro.

### Selecionando Elementos
Usamos os comando `cy.get()` e `cy.contains()`  obter um ou mais elementos do DOM.

#### `cy.get()` Este comando é usado para obter um ou mais elementos do DOM. Ele pode ser usado com um seletor jQuery para obter elementos específicos. Por exemplo:
```bash
cy.get('.nav');
```
Obtém todos os elementos com a classe ‘nav’.

#### `cy.contains()` Este comando é usado para obter o primeiro elemento do DOM que contém um texto específico. Ele pode ser usado de várias maneiras, exemplo:

```bash
cy.contains('Hello');
```
Obtém o primeiro elemento que contém o texto ‘Hello’.
