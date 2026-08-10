# Esteira da análise - Bibliotech
**Estudante:** Mayara Mierzva

## Funcionalidade 1: Cadastrar Leitor
- **1. Fala do cliente:** "Preciso cadastrar os leitores no sistema para conseguir realizar a identificação dos alunos que utilizam a biblioteca e seus serviços."

- 2. História de usuário: Como bibliotecário, quero cadastrar um leitor, para manter os dados dos leitores organizados no sistema.

- **3. Requisito:** RF01 — O sistema deve permitir que o bibliotecário cadastre um leitor.

- **4. Caso de uso (RF01):** Ator Bibliotecário → "Cadastrar leitor"





## Funcionalidade 2: Cadastrar livro

- **1. Fala do cliente:** "Quaando chegar um livro novo, eu preciso cadastrar ele no sistema com as informações necessárias para que possa ser encontrado depois."

- 2. História de usuário: Como bibliotecário, quero cadastrar um livro, para manter as informações do acervo organizadas e facilitar sua localização.

- **3. Requisito:** RF02 — O sistema deve permitir que o bibliotecário cadastre um livro.

- **4. Caso de uso (RF02):** Ator Bibliotecário → "Cadastrar livro"

# Rastreabilidade

| Fala do cliente | História de usuário | Requisito | Caso de uso |
| Cadastrar leitores para identificar os alunos que utilizam a biblioteca. | Como bibliotecário, quero cadastrar um leitor, para manter os dados dos leitores organizados no sistema. | RF01 | Cadastrar leitor |
| Cadastrar livros novos com as informações necessárias para serem encontrados depois. | Como bibliotecário, quero cadastrar um livro, para manter as informações do acervo organizadas e facilitar sua localização. | RF02 | Cadastrar livro |

## Relacionamento entre casos de uso

Utilizei o relacionamento «include» entre os casos de uso **Cadastrar leitor** e **Identificar leitor**, pois a identificação do leitor é obrigatória durante o cadastro.