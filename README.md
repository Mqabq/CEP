Consulta de CEP

## Descrição

Este projeto consiste em uma aplicação web simples que permite ao usuário consultar informações relacionadas a um Código de Endereçamento Postal (CEP) brasileiro. A aplicação utiliza HTML, CSS e jQuery para criar uma interface amigável e realizar requisições AJAX a uma API externa (ViaCEP) para obter os dados do endereço consultado.

## Funcionalidades

- Consulta de CEP com validação do formato de entrada.
- Exibição das informações do endereço, incluindo:
  - Logradouro
  - Bairro
  - Cidade
  - Estado
- Feedback ao usuário em caso de CEP inválido ou não encontrado.
- Estilização responsiva e interativa com uso de CSS.

## Tecnologias Utilizadas

- **HTML5**: Estruturação da página.
- **CSS3**: Estilização e layout responsivo.
- **jQuery**: Manipulação do DOM e execução de requisições AJAX.

## Estrutura do Código

### HTML

O arquivo HTML contém:

- Declaração do tipo de documento e linguagem.
- Metadados, incluindo charset e viewport para responsividade.
- Título da página.
- Inclusão da biblioteca jQuery.
- Estrutura do formulário de consulta de CEP.
- Div para exibir o resultado da consulta.

### CSS

O estilo define:

- Cores e fonte da aplicação.
- Layout centralizado da página.
- Estilos para o botão e campos de entrada, incluindo efeitos ao passar o mouse.

### JavaScript (jQuery)

O script JavaScript realiza as seguintes ações:

- Captura o input do usuário ao clicar no botão de consulta.
- Valida se o CEP possui pelo menos 8 caracteres.
- Envia uma requisição AJAX à API do ViaCEP.
- Processa a resposta da API e exibe as informações obtidas ou erros relevantes.

## Instruções de Uso

1. Abra o arquivo HTML em um navegador web.
2. Insira o CEP desejado no formato apropriado (ex: 80030-130).
3. Clique no botão "Consultar".
4. As informações do endereço correspondente ao CEP serão exibidas abaixo.

## Contribuições

Sinta-se à vontade para contribuir no projeto, seja reportando problemas ou sugerindo melhorias.

## Licença

Este projeto é de uso livre. Sinta-se à vontade para utilizá-lo como desejar!

---

Esperamos que você aproveite a aplicação de Consulta de CEP! Se você tiver alguma dúvida ou sugestão, não hesite em entrar em contato.
