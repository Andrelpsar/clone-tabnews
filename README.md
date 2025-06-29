# clone-tabnews
Implementação do tabnews para fins de estudos relativos ao curso.dev do Filipe Deschamps.

Este leia-me servirá como um diário de aprendizado, mais do que um manual do código.

Fundação - Node.js

Paredes - Next.js

Dia 3 28/06/2025

1. NVM - Node Version Manager

1.1 Utilitário para utilizarmos versões do node diferentes da padrão (ou mais nova)
Para este projeto, utilizaremos a lts/iron-> v20.19.2

        nvm ls
        nvm install lts/iron 

1.1.1 Para que a versão desejada continue mesmo quando fechar e abrir, vamos apontar o padrão (default) para a nova alias, que é o iron (neste caso)

        nvm alias default lts/iron

1.2 Para mais ações: nvm --help

1.3 .nvmrc - nvm run commands: "rc (run commands) é convenção para indicar arquivos que contêm instruções que devem ser executadas no início do programa. Ao criar esse arquivo, pode ser verificado ao utilizar o comando nvm install que terá a indicação da intalação da versão que contém nele.

2. Frameworks - Next.js e React.js

        npm init - para fazer o package.json (mudar só a licença para MIT)
        npm install next@13.1.6 - aqui para instalar o next
        npm install react@18.2.0 - aqui para instalar o react
        npm install react-dom@18.2.0 - para HTMTL

As versões instaladas são propositalmente desatualizadas, para que em aulas futuras poderem ser trocadas para fins didáticos. Quando forem trocadas, este tópico será atualizado. VOLTAR

dia 4 26/06/2025

Esta parte começa com conceitos de protocolos da internet. Vai ser feito um servidor HTTP. 

1. levantando o servidor.

1.1 ir ao package.json para fazer um script para rodar o next de forma global

        "dev": "next dev"
        npm run dev

Obiter dictum: usar ctrl + l em vez de clear, porque aí este não é acessado com a seta pra cima



    
