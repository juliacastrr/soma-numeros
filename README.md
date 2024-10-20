Documentação da Página de Soma de Números
1. Introdução
Este projeto é uma aplicação web simples construída com Next.js, que permite ao usuário inserir dois números e calcular a soma. A aplicação foi desenvolvida para demonstrar o uso de formulários, gerenciamento de estado e manipulação de eventos em React.

2. Estrutura do Projeto
O projeto segue a estrutura padrão do Next.js. A página principal está localizada no arquivo src/app/index.js.

Arquivos Importantes
src/app/index.js: Contém o código principal da aplicação.
src/styles/styles.css: Contém os estilos aplicados à página.
3. Implementação da Página
Lógica da Implementação
Importação de Dependências: O hook useState é importado do React para gerenciar o estado dos números e do resultado.

Gerenciamento de Estado:

numero1 e numero2: Armazenam os valores dos números inseridos pelo usuário.
soma: Armazena o resultado da soma dos dois números.
Função de Submissão: Esta função é chamada quando o formulário é submetido. Ela previne o comportamento padrão de recarregar a página e calcula a soma dos números, armazenando o resultado no estado.

Renderização do Componente: A página renderiza um título e um formulário com dois campos de entrada e um botão de submissão. O resultado da soma é exibido abaixo do formulário, caso exista.

4. Estilos
Os estilos da página são definidos no arquivo src/styles/styles.css, visando proporcionar uma interface simples e amigável ao usuário, com um layout claro e elementos visualmente agradáveis.

5. Conclusão
A aplicação permite que os usuários realizem a soma de dois números de forma simples e interativa. Este projeto é um exemplo prático do uso do Next.js para construir interfaces de usuário dinâmicas e responsivas.
