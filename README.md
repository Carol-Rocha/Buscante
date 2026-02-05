# Buscante

Buscante é uma aplicação web Angular que permite buscar livros utilizando a API pública do Google Books. O projeto foi desenvolvido para facilitar a pesquisa de títulos, autores e informações de livros de forma rápida e intuitiva.

## Link do Deploy

Acesse a aplicação online:  
https://buscante-nu.vercel.app/lista-livros

## Funcionalidades

- Busca de livros por título, autor ou palavra-chave.
- Exibição de resultados com detalhes dos livros.
- Interface responsiva e moderna.

## Tecnologias Utilizadas

- Angular 14
- TypeScript
- RxJS
- Google Books API

## Como baixar e rodar localmente

1. Clone o repositório:
   ```bash
   git clone <URL_DO_SEU_REPOSITORIO>
   cd Buscante
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Rode a aplicação:
   ```bash
   npm start
   ```
   Acesse em `http://localhost:4200/lista-livros`

## Rotas

A aplicação possui as seguintes rotas:

- `/lista-livros`: Página principal onde é possível buscar e visualizar livros.

A rota padrão redireciona para `/lista-livros`.

## API Utilizada

A busca de livros é feita através da API pública do Google Books:
```
https://www.googleapis.com/books/v1/volumes
```
O serviço consome esta API enviando o termo digitado pelo usuário como parâmetro `q`.

## Estrutura do Projeto

- `src/app/componentes/`: Componentes reutilizáveis (cabeçalho, rodapé, livro).
- `src/app/views/`: Telas principais (lista de livros, modal de detalhes).
- `src/app/service/livro.service.ts`: Serviço responsável pela comunicação com a API do Google Books.
- `src/app/models/`: Interfaces e tipos utilizados.
- `src/app/pipes/`: Pipes personalizados.
- `src/app/app-routing.module.ts`: Configuração das rotas.

## Como contribuir

1. Faça um fork do projeto.
2. Crie uma branch para sua feature ou correção:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça suas alterações e envie um pull request.

## Licença

Este projeto está sob a licença MIT.






