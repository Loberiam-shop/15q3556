# Estrutura do Projeto Loberiam Shop Premium (HTML/CSS/JS)

Este projeto contém a versão redesenhada do Loberiam Shop, desenvolvida com HTML, CSS e JavaScript puros, inspirada nas melhores práticas de grandes marketplaces.

## Estrutura de Pastas e Arquivos

```
/loberiam_premium_redesign/
├── index.html                # Página Inicial
├── produtos.html             # Página de Listagem de Produtos
├── produto_exemplo.html      # Página de Detalhes do Produto
├── carrinho.html             # Página do Carrinho de Compras (se dedicada)
├── checkout.html             # Página de Checkout
├── conta.html                # Página Principal da Conta do Usuário
├── sobre.html                # Página Sobre Nós
├── contato.html              # Página de Contato
├── politicas.html            # Página de Políticas
├── ajuda.html                # Página de Ajuda/FAQ
├── style.css                 # Estilos principais (redesenhados)
├── funcionalidades.js        # Scripts para funcionalidades (carrossel, carrinho, etc.)
├── assets/                   # Pasta para imagens, logos, ícones
│   ├── logo-loberiam.png
│   ├── banner1.jpg
│   └── ... (outras imagens)
└── README.md                 # Este arquivo
```

## Publicação Facilitada

Esta versão do projeto, por ser construída apenas com HTML, CSS e JavaScript estáticos, é ideal para publicação em plataformas como GitHub Pages ou qualquer hospedagem web tradicional que suporte arquivos estáticos.

### Publicando no GitHub Pages (Recomendado para Testes)

1.  **Crie um Repositório no GitHub:** Se ainda não tiver, crie um novo repositório público no seu GitHub (ex: `loberiam-shop-premium`).
2.  **Envie os Arquivos:**
    *   Navegue até a pasta `/home/ubuntu/loberiam_premium_redesign` no seu terminal (ou use um cliente Git).
    *   Inicialize o Git (se ainda não for um repositório): `git init`
    *   Adicione todos os arquivos: `git add .`
    *   Faça o commit: `git commit -m "Versão premium inicial do Loberiam Shop"`
    *   Adicione o repositório remoto do GitHub: `git remote add origin https://github.com/SEU_USUARIO/SEU_REPOSITORIO.git`
    *   Envie os arquivos para o GitHub: `git push -u origin main` (ou `master`, dependendo do nome do seu branch principal).
3.  **Ative o GitHub Pages:**
    *   No seu repositório no GitHub, vá em "Settings" (Configurações).
    *   No menu lateral, clique em "Pages".
    *   Em "Source", selecione o branch `main` (ou `master`) e a pasta `/root`.
    *   Clique em "Save".
4.  **Acesse o Site:** Aguarde alguns minutos. Seu site estará disponível em `https://SEU_USUARIO.github.io/SEU_REPOSITORIO/`.

### Publicando em Hospedagem Tradicional

1.  **Faça o Upload:** Simplesmente copie todos os arquivos e pastas de `/home/ubuntu/loberiam_premium_redesign` para o diretório raiz (geralmente `public_html`, `www` ou similar) do seu serviço de hospedagem usando um cliente FTP (como FileZilla) ou o gerenciador de arquivos do painel de controle da sua hospedagem.
2.  **Configure o Domínio (se aplicável):** Se você tiver um domínio próprio, configure-o para apontar para o diretório onde você fez o upload dos arquivos.

**Observação:** Como este é um site estático, funcionalidades que normalmente exigiriam um backend (como salvar carrinhos entre sessões, processar pagamentos reais, salvar dados de usuário permanentemente) não estarão ativas. A interação do carrinho, login (simulado), etc., funcionará no navegador usando JavaScript, mas os dados não serão persistidos em um servidor.

