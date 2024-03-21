## Requisitos Funcionais:

RF1. **O sistema deve ter interface de usuário intuitiva:**
   - Os usuários devem ser capazes de navegar facilmente pela aplicação.
   - Os elementos da interface devem ser organizados de forma lógica e intuitiva.

RF2. **O sistema deve ter possuir fluxo de navegação suave:**
   - Os usuários devem poder transitar facilmente entre as diferentes seções da aplicação.
<<<<<<< HEAD
   - O fluxo de navegação deve ser claro e direto, minimizando o número de cliques necessários para acessar as funcionalidades principais.
     
4. **Design Atraente e Moderno:**
   - O design da aplicação deve ser esteticamente agradável e atualizado para refletir as tendências de design contemporâneas.
   - Deve haver uma atenção especial para o uso de cores, tipografia e elementos visuais para criar uma experiência atraente para o usuário.

5. **Integração com Backend:**
   - A interface do usuário deve se integrar perfeitamente com o backend existente da Clínica DosImagem.
   - As funcionalidades existentes devem ser mantidas e aprimoradas, conforme necessário.

6. **Segurança:**
   - As informações dos pacientes e quaisquer dados sensíveis devem ser protegidos por medidas de segurança adequadas, como criptografia de dados e autenticação de usuário.

=======
   - O fluxo de navegação deve ser claro e direto, minimizando o número de cliques necessários para acessar as funcionalidades principais e aumentando a eficiência de trabalho dos funcionários.

RF3. **O sistema deve possuir organização inteligente dos serviços:**
   - Atualmente a api da dosimagem conta com uma aba de "Services", que contém todos os 5 tipos de formulários para cada serviço deles,
      no entanto, isso gera um design "caótico" no design do site, confuso e nada intuítivo.

RF4. **O sistema deve ter um design atraente e moderno:**
   - O design da aplicação deve ser esteticamente agradável e atualizado para refletir as tendências de design contemporâneas.
   - Deve haver uma atenção especial para o uso de cores, tipografia e elementos visuais para criar uma experiência atraente para o usuário.
     
>>>>>>> main
## Requisitos Não Funcionais:

RNF1. **O sistema deve possuir bom desempenho:**
   - A aplicação deve carregar rapidamente, garantindo uma experiência de usuário fluida e sem atrasos perceptíveis.
   - As interações do usuário, como clicar em botões e preencher formulários, devem ter resposta imediata.
   - - O sistema deve receber e processar os exames enviados pelos usuários de uma forma relativamente rapida.

RNF2. **O sistema deve possuir boa compatibilidade:**
   - A aplicação deve ser compatível com os principais navegadores da web, incluindo Google Chrome, Mozilla Firefox, Safari e Microsoft Edge.

RNF4. **O sistema deve ser capaz de sofrer manutenção:**
   - O código-fonte deve ser bem estruturado, modular e de fácil compreensão, facilitando futuras atualizações e manutenção.
   - Deve-se adotar práticas de desenvolvimento que promovam a reutilização de código e a escalabilidade da aplicação.
   - Deve ser fornecida documentação abrangente para auxiliar no desenvolvimento, implantação e manutenção da aplicação. Isso inclui documentação do código-fonte, guias de instalação e instruções para a resolução de problemas comuns.

RNF5. **O sistema deve ser fácilmente testável:**
   - A aplicação deve ser testada de forma abrangente para garantir que todas as funcionalidades estejam funcionando conforme o esperado.
   - Deve haver uma estratégia de testes que cubra tanto os casos de uso típicos quanto os cenários de exceção.

<<<<<<< HEAD
6. **Compatibilidade com Padrões Web:**
   - O código da aplicação deve seguir os padrões e diretrizes da web, como HTML, CSS e JavaScript.
   - Deve ser compatível com as especificações mais recentes para garantir a interoperabilidade e a sustentabilidade a longo prazo.
=======
RNF6. **O sistema deve possuir compatibilidade com os padrões web:**
   - O código da aplicação deve seguir os padrões e diretrizes da web, como HTML5, CSS3 e JavaScript ECMAScript 6.
   - Deve ser compatível com as especificações mais recentes para garantir a interoperabilidade e a sustentabilidade, evitando que se torne legado a curto ou médio prazo.
>>>>>>> main

RNF7. **O sistema deve ser escalável:**
   - A aplicação deve ser projetada para lidar com um potencial aumento no número de usuários e volume de dados no futuro.
   - Deve ser possível adicionar novas funcionalidades e expandir a aplicação sem grandes modificações na arquitetura existente.
  
RNF9. **O sistema deve ser suficientemente seguro:**
   - Deve seguir as normas ISO/IEC 27001
   - As informações dos pacientes e quaisquer dados sensíveis devem ser protegidos por medidas de segurança adequadas, como criptografia de dados e autenticação de usuário.
   - Por exemplo, utilizar as últimas versões das ferramentas de desenvolvimento e prevenir SQL Injection nas entradas de dados para que o Front-End contribua na segurança do sistema como um todo.
