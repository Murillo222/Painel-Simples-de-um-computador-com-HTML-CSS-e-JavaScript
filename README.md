# Painel-Simples-de-um-computador-com-HTML-CSS-e-JavaScript


🖥️ Painel do Computador

O Painel do Computador é uma aplicação web simples e responsiva construída com HTML puro, CSS e JavaScript Vanilla. O objetivo do projeto é demonstrar o uso de diversas APIs nativas do navegador para extrair e exibir informações em tempo real sobre o sistema, hardware, tela, localização e arquivos do usuário.

🚀 Funcionalidades

O painel é dividido em quatro seções principais que utilizam recursos modernos do ecossistema Web:
• Navegador e sistema: Exibe detalhes sobre o User Agent, idioma preferido, quantidade de núcleos da CPU (hardwareConcurrency), memória RAM aproximada (deviceMemory), fuso horário local e o status atual da conexão (Online/Offline).
• Tela e janela: Mostra a resolução nativa do monitor e as dimensões em tempo real da janela do navegador, atualizando os dados automaticamente ao redimensionar a tela (resize). Também detecta se o sistema está utilizando o Modo Escuro (prefers-color-scheme).
• Localização: Utiliza a API de Geolocalização do navegador para obter e exibir as coordenadas de Latitude e Longitude do usuário (após a concessão de permissão).
• Arquivos: Permite a seleção múltipla de arquivos locais e monta dinamicamente uma tabela listando o nome e o tamanho de cada arquivo convertido para Kilobytes (KB).

🛠️ Tecnologias Utilizadas

• HTML5: Estruturação semântica da página.
• CSS3: Estilização moderna e limpa, utilizando fontes do sistema e layout responsivo.
• JavaScript (ES6+): Manipulação dinâmica do DOM e consumo das APIs Web (navigator, screen, window, Intl, Geolocation).

📁 Estrutura do Código

O projeto está dividido logicamente em três partes:
1. index.html: Define a interface com tabelas dinâmicas e os blocos de visualização.
2. style.css: Controla o visual minimalista e a quebra de textos longos.
3. script.js: Gerencia a lógica de captura dos dados e preenchimento automatizado das tabelas.
