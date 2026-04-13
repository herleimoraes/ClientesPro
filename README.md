📱 App Gestão de Clientes

Uma aplicação web focada em dispositivos móveis (Mobile-First) para gestão e cadastro de clientes. Desenvolvida como uma Single Page Application (SPA), oferece uma navegação fluida, interface moderna e armazenamento local de dados, sem a necessidade de um backend ou base de dados complexa.

✨ Funcionalidades Principais

Dashboard Analítico: Resumo rápido do total de clientes e atalhos de navegação.

CRUD Completo: Registo, visualização de detalhes, edição e exclusão de clientes.

Armazenamento Local: Os dados são guardados diretamente no localStorage do navegador do utilizador.

Relatórios de Qualidade: Gráficos de progresso que indicam a completude dos dados registados (percentagem de clientes com E-mail, Documento e Endereço).

Busca Inteligente: Filtro dinâmico na lista de clientes que pesquisa por Nome, Telefone ou CPF/CNPJ em tempo real.

Máscaras de Validação: Formatação automática em tempo real para Telefone, CEP e adaptação inteligente entre CPF e CNPJ.

Modo Escuro (Dark Mode): Tema escuro nativo implementado com Bootstrap, com preferência guardada na memória do dispositivo.

Design Mobile-First: Navegação inspirada em aplicações nativas, utilizando um Bottom Navigation Menu.

🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando apenas tecnologias front-end padronizadas, sem a necessidade de frameworks complexos de compilação:

HTML5

CSS3 (com variáveis CSS personalizadas)

JavaScript (Vanilla)

Bootstrap 5.3 (via CDN)

Bootstrap Icons (via CDN)

🚀 Como Executar o Projeto

Como a aplicação é 100% Client-Side e utiliza localStorage, não é necessária a instalação de nenhuma dependência ou servidor local.

Faça o clone deste repositório:

git clone [https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git](https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git)


Navegue até à pasta do projeto.

Abra o ficheiro index.html diretamente no seu navegador web, ou hospede a pasta numa plataforma de ficheiros estáticos (como o GitHub Pages, Vercel ou Netlify).

📁 Estrutura de Ficheiros Recomendada

index.html - O código-fonte principal contendo a estrutura, os estilos e a lógica JavaScript da aplicação.

version.json - Ficheiro utilizado para o versionamento dinâmico da aplicação.

CHANGELOG.md - Histórico detalhado de atualizações e versões do projeto.

README.md - A documentação principal do repositório.

📈 Próximos Passos (Roadmap)

[ ] Integração com a API do ViaCEP para preenchimento automático de endereço.

[ ] Opção para exportar os clientes cadastrados num ficheiro Excel/CSV.

[ ] Melhoria na acessibilidade e suporte a leitores de ecrã.

⌨️ Desenvolvido com ❤️
