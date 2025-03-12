# Hugo - Site da Clínica de Psicologia

## Comandos
- **Construir site**: `hugo`
- **Construir para produção**: `hugo --minify`
- **Iniciar servidor de desenvolvimento**: `hugo server -D`
- **Criar novo conteúdo**: `hugo new content/nomedapasta/novo-arquivo.md`
- **Limpar cache**: `hugo --cleanDestinationDir`

## Diretrizes de Estilo
- **Markdown**: Use Markdown padrão com shortcodes do Hugo
- **Front Matter**: Use formato TOML (+++) para front matter
- **Conteúdo**: Mantenha conteúdo no diretório /content
- **Imagens**: Armazene imagens em /static/images
- **Layout**: Layouts personalizados vão em /layouts
- **CSS**: CSS personalizado em /assets/css
- **Configuração**: Use hugo.toml para configuração do site
- **Tema**: PaperMod é o tema atual
- **Estrutura de Conteúdo**: Siga a estrutura existente no diretório content/
- **Links**: Use links relativos para conteúdo interno

## Implantação
- Auto-implantação para GitHub Pages ao fazer push para master
- Publicado em: https://vtsugi1.github.io/site-clinica-hugo/