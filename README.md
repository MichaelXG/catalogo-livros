# 📚 Catálogo de Livros Online

Este projeto é uma aplicação web simples para gerenciar um catálogo de livros. Ele permite **adicionar**, **listar**, **buscar**, **ordenar** e **avaliar livros**, com persistência de dados no navegador usando `localStorage`.

## 🔧 Funcionalidades

- ✅ **Listar Livros**  
  Exibe todos os livros cadastrados no catálogo, com dados como título, autor, gênero, ano e média de avaliações.

- ➕ **Adicionar Livro**  
  Permite adicionar um novo livro informando título, autor, gênero e ano de publicação.

- 🔍 **Buscar Livro**  
  Busca dinâmica por título, autor ou gênero (enquanto digita).

- ↕️ **Classificar Livros**  
  Ordena os livros por título, autor ou avaliação média.

- ⭐ **Avaliar Livro**  
  Permite que o usuário atribua uma nota de 1 a 5 a um livro.

- 💾 **Salvar e Carregar**  
  Os dados são armazenados no `localStorage` do navegador. Na primeira execução, é feito o carregamento de um `books.json` com livros pré-definidos.

- 📤 **Exportar JSON**  
  Permite exportar o catálogo atual em formato `.json`.

---

## 🗂️ Estrutura de Dados

Cada livro é representado como:

```json
{
  "titulo": "Dom Casmurro",
  "autor": "Machado de Assis",
  "genero": "Romance",
  "ano": 1899,
  "avaliacoes": [5, 4, 5]
}
```

---

## ▶️ Como Executar Localmente

1. Instale o `serve` (caso ainda não tenha):

```bash
npm install -g serve
```

2. Navegue até a pasta do projeto:

```bash
cd caminho/do/seu/projeto
```

3. Execute com:

```bash
npx serve .
```

4. Acesse no navegador:

```
http://localhost:3000
```

💡 **Dica**: certifique-se de que o arquivo `books.json` está na mesma pasta do `index.html` para que o carregamento inicial funcione corretamente.

---
