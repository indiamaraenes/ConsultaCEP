# Consulta CEP - Documentação do Projeto

## Descrição do Projeto
O projeto "Consulta CEP" consiste em uma aplicação web simples que permite aos usuários consultar informações de endereço com base em um CEP fornecido. A interface é composta por um formulário que solicita o CEP, e os campos de logradouro, bairro, localidade e UF são preenchidos automaticamente após a consulta à API ViaCEP.

## Estrutura do Projeto
O projeto está estruturado em um arquivo HTML que contém a estrutura da página, um arquivo CSS para estilização e um arquivo JavaScript para manipulação da lógica de consulta à API e preenchimento dos campos.

### HTML (`index.html`)
- `<!DOCTYPE html>`: Declaração do tipo de documento HTML.
- `head`: Contém metadados, como o conjunto de caracteres, título da página e links para estilos.
- `body`: Contém o formulário de consulta CEP.

### CSS (`style.css`)
- Estilização básica para a página, incluindo um contêiner centralizado, formatação do formulário e estilo para o título.

### JavaScript (`script.js`)
- Seleção do elemento de input do CEP (`#cep`).
- Definição da função `showData` para preenchimento automático dos campos do formulário com os dados obtidos da API.
- Adição de um evento de escuta para o evento `blur` no input do CEP, desencadeando a consulta à API ViaCEP e o preenchimento dos campos.

## Tecnologias Utilizadas
- HTML5
- CSS3
- JavaScript (ES6+)
- Bootstrap 4.0.0 (CDN)
- API ViaCEP para consulta de informações de endereço.

## Instruções de Uso
1. Abra o arquivo `index.html` em um navegador web.
2. Insira o CEP desejado no campo correspondente.
3. Aguarde a consulta à API ViaCEP e observe o preenchimento automático dos campos de logradouro, bairro, localidade e UF.

## Considerações Finais
Certifique-se de ter uma conexão com a internet ao utilizar a aplicação, pois a consulta à API ViaCEP depende dela.
