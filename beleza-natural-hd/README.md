# Beleza Natural HD

Mini site responsivo que realça automaticamente a luz, o contraste, a saturação e a temperatura de cor de uma foto. A pessoa só seleciona a imagem; não precisa escolher filtros ou ajustar controles.

## Usar
Abra o site publicado e toque em **Escolher foto e realçar**. Depois, salve a imagem ou use o botão de compartilhamento do celular para enviá-la ao Instagram.

## Privacidade e limitações
A foto é processada dentro do navegador e não é enviada a um servidor por este site. Esta versão usa realce automático de imagem, não detecção facial nem transformação por IA. O efeito pode variar conforme a foto original.

## Publicar com GitHub Pages

A configuração inicial do GitHub Pages precisa ser habilitada nas configurações do repositório: **Settings → Pages → Build and deployment → Source → GitHub Actions**. Depois, abra **Actions → Deploy Beleza Natural HD → Run workflow**. O workflow usa `actions/configure-pages` sem tentar criar o site automaticamente, porque o `GITHUB_TOKEN` padrão não tem a permissão administrativa necessária para ativar o Pages pela primeira vez.
