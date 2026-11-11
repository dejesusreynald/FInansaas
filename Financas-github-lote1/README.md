# Finanças

App de controle de finanças pessoais (versão beta). Tudo roda no navegador: não há servidor, e os dados ficam apenas no aparelho de quem usa (localStorage).

## Recursos
- Início com saldo geral, contas, próximas contas e faturas
- Lançamentos de receitas e despesas
- Orçamento previsto x real, com gráficos
- Tetos de gastos por categoria
- Contas fixas e cartões de crédito
- Senha e PIN, com bloqueio automático
- Backup e restauração por arquivo
- Tema Grafite (escuro) e claro

## Como publicar no GitHub Pages
1. Crie um repositório novo no GitHub (por exemplo, `financas`).
2. Envie estes arquivos para a raiz do repositório.
3. Em **Settings → Pages**, em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e clique em **Save**.
4. Em cerca de um minuto o app estará em `https://SEU-USUARIO.github.io/financas/`.

## Estrutura
- `index.html`: o app inteiro (HTML, CSS e JavaScript em um único arquivo)
- `manifest.webmanifest` e `icons/`: nome e ícone ao instalar na tela inicial
- `.nojekyll`: faz o GitHub Pages servir os arquivos como estão

## Observações
- Cada endereço (domínio) guarda os seus próprios dados. Ao mudar de endereço, use **Ajustes → Seus dados → Exportar backup** no endereço antigo e **Escolher arquivo** no novo.
- Os dados não são enviados a nenhum servidor. Limpar os dados do navegador apaga o conteúdo do app, por isso faça backups.
- As fontes (Bricolage Grotesque e Figtree) são carregadas do Google Fonts; sem internet, o app usa as fontes do sistema.
