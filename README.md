# Java_Orientacao_Objetos_2
Java-Orientado-Objetos-2

//Explicação:
//Classe Endereco:
//
//Representa os dados retornados pela API ViaCEP, como CEP, logradouro, bairro, cidade e UF.
//Inclui getters e um método toString para exibir os dados no console.
//
//Menu:
//
//O programa oferece um menu para o usuário escolher entre buscar um endereço pelo CEP ou sair.
//Método consultarCEP:
//
//Realiza a requisição HTTP para a API ViaCEP usando o CEP fornecido.
//Se o CEP não for encontrado, lança uma exceção com uma mensagem amigável.
//Caso a consulta seja bem-sucedida, os dados retornados são convertidos para um objeto Endereco.
//Método salvarEnderecoComoJson:
//
//Recebe o objeto Endereco e o converte para um arquivo .json usando a biblioteca Gson.
//Tratamento de Exceções:
//
//O programa captura e exibe erros no processo de consulta ou de gravação do arquivo JSON, garantindo que o usuário seja informado sobre qualquer problema.
