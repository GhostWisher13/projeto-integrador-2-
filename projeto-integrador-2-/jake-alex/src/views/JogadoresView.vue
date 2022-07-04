<script>
export default {
  data() {
    return {
      livros: [
        {
          id: "72b60663-4943-4f37-a782-3b0688d5b313",
          nome: "autor 1",
          livros: "livro 1",
        },
        {
          id: "e91ca40f-1b1c-40d9-a589-a6d74b42f6c5",
          nome: "autor 2",
          livros: "livro 2",
        },
        {
          id: "d181a6a6-fa46-426e-bd5a-9a9ee19356d6",
          nome: "autor 3",
          livros: "livro 3",
        },
        {
          id: "e0b9c7d6-06d5-405f-a674-0e4b286a6b6a",
          nome: "autor 4",
          livros: "livro 4",
        },
        {
          id: "0daa3bee-b872-4ca7-87ef-42481f434a9a",
          nome: "autor 5",
          livros: "livro 5",
        },
      ],
    };
  },
};
</script>
<template>
  <div class="container">
    <div class="title">
      <h2>Gerenciamento de livros</h2>
    </div>
    <div class="form-input">
      <input type="text" />
      <button>Salvar</button>
    </div>
    <div class="list-livros">
      <table>
        <thead>
          <tr>
            <th>ID</th>
            <th>autor</th>
            <th>livros</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="livros in " :key="livros.id">
            <td>{{ livros.id }}</td>
            <td>{{ livros.autor }}</td>
            <td>{{ livros.autor }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>