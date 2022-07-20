# Desafio-react-redux
redux com react

// Utilizando os conceitos e funções ensinadas (createAsyncSlice, Thunk, localStorage).<br>
// Crie um mini aplicativo utilizando a API do Dogs.<br>
// Crie um formulário para a autenticação do usuário<br>
// Após o usuário ser autenticado, remova o formulário<br>
// e mostre uma lista com as fotos mais recentes<br>

const api_photos = {
  url: `https://dogsapi.origamid.dev/json/api/photo/?_page=1&_total=3&_user=0`,
  options: {
    method: 'GET',
    cache: 'no-store',
  },
};
<br><br>
// permita que o usuário carregue mais fotos ao clicar em um botão<br>
// crie a funcionalidade de logout
