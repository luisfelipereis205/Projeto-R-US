 Projeto Réus - Efeito Parallax
Sobre o Projeto
Este projeto é um estudo de caso focado em Web Design Urbano e manipulação de propriedades de imagem via CSS. A proposta foi transpor a carga emocional e a estética da música "Réus" do rapper Filipe Ret para uma interface web, utilizando efeitos de profundidade e transições de camadas.

O objetivo principal foi praticar a técnica de Parallax Scrolling puro (sem bibliotecas externas), garantindo uma navegação fluida e imersiva.

🎨 Identidade Visual
A estética foi inspirada no conceito "Vivaz" e na cultura das ruas do Rio de Janeiro (TTK).

Paleta de Cores: Predominância de tons escuros (#2C2F33) para simular o asfalto e o ambiente noturno, com contrastes em branco e transparências em preto (rgba) para garantir a legibilidade sobre as imagens.

Tipografia: * Passion One: Para títulos, trazendo o impacto das fontes de impacto (display).

Sriracha: Para os versos, remetendo à caligrafia urbana e ao traço do grafite.

🛠️ Tecnologias e Técnicas Utilizadas
CSS3 Avançado
background-attachment: fixed: O coração do projeto, criando o efeito de "janelas" onde o conteúdo desliza enquanto a imagem de fundo permanece estática.

background-size: cover: Utilizado para garantir que as imagens geradas por IA ocupem toda a área da seção sem distorção.

Variáveis CSS (:root): Centralização das fontes e cores para facilitar a manutenção e escalabilidade do código.

Viewport Units (vh e vw): Layout adaptável que utiliza a altura e largura da tela do usuário para dimensionar títulos e espaçamentos.

Flexbox & Box-sizing: Gerenciamento de espaçamento interno e alinhamento de versos.

📂 Estrutura de Pastas
Plaintext
/
├── imagens/          # Assets visuais (Backgrounds urbanos)
├── css/
│   └── estilo.css    # Estilização completa e Parallax
├── index.html        # Estrutura semântica do site
└── README.md         # Documentação
