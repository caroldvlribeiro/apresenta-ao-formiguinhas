# Formiguinhas da Praia

Apresentação web estática da plataforma Formiguinhas da Praia, pronta para publicação no GitHub Pages.

## Estrutura
- `index.html`: página única da apresentação; mantém os slides no mesmo endereço.
- `slides/`: os 12 slides HTML, com navegação por botões e pelas setas do teclado.
- `css/`: estilos dos slides e folhas compartilhadas de navegação e responsividade.
- `assets/`: imagens utilizadas pela apresentação.

## Como visualizar
Abra `index.html` em um navegador ou acesse a URL publicada no GitHub Pages. A apresentação ocupa a tela toda, com fundo azul-escuro. Use as setas ← e → do teclado ou os botões na tela para navegar pelos slides sem sair da página. Em telas menores, o conteúdo se reorganiza em coluna e pode ser rolado quando necessário. As imagens e os estilos locais usam caminhos relativos. Fredoka, Quicksand e alguns ícones são carregados de serviços externos, então precisam de conexão à internet.

## Publicar no GitHub Pages
1. Envie o conteúdo desta pasta para a raiz de um repositório GitHub.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch principal (por exemplo, `main`) e a pasta **/(root)**; salve.
5. Após a publicação, abra a URL indicada nessa página. O `index.html` inicia a apresentação.

Não é necessário instalar dependências ou executar etapa de build.
