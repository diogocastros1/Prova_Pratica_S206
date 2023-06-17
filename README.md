# Prova_Pratica_S206
Prova prática final da disciplina de Qualidade de software (S206).

## 🛠 Preparando ambiente

### Cypress
- Na pasta `testesCypress` digite o comando `npm install` para instalar todas as dependências.

### Karate
- Clonando este repositório o Karate já estará preparado para utilização.

---
## ▶ Executando os testes
### Cypress
- No git bash, acesse a pasta `testesCypress` e digite `npm test`.

### Karate
- No git bash, acesse a pasta `testesKarate/aula_inatel` digite `mvn test -Dtest=FakeRunner`

---
## 📑 Relatórios
### Cypress
- Após executar o comando acima, o Cypress irá gerar as pastas `videos`, onde é possivel acessar o videos dos testes e `reports` onde podemos acessar o arquivo `index.html` que é o relatório de testes.

### Karate
- Os relatorios do karate podem ser acessados na pasta `target/karate-reports`, dentro desta pasta basta abrir o arquivo `fakestore.fakestore.html`.
