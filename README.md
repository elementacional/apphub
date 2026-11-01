# AppHub Studio v1.2

Central estática de atalhos para aplicativos. Interface dark, edição de cards, upload de SVG, PNG e WEBP, busca, organização por arrastar, JSON de importação/exportação.

## Publicação
Envie `index.html` e `.nojekyll` à raiz do repositório e ative GitHub Pages em Settings > Pages, branch `main`, pasta `/ (root)`.

## Links
O campo **Link para abrir** deve conter a URL pública em execução (por exemplo, `https://elementacional.github.io/pageforge/`), não o endereço `github.com/usuario/repo` do código-fonte. Ter `index.html` no repositório não basta: cada app precisa estar publicado e funcionar no Pages. Alguns projetos exigem build e não podem ser executados apenas copiando o fonte.

## Ícones SVG
Aceita SVG simples de até 220 KB. Bloqueia scripts, referências externas e componentes potencialmente inseguros. Use o arquivo `.svg` real (não SVG comprimido nem arquivos renomeados).

## Persistência
Alterações feitas na página são armazenadas via localStorage deste navegador. **Exportar catálogo** baixa `apps.json`; coloque-o junto ao `index.html` no GitHub para servir de catálogo inicial a novos navegadores. O JSON é carregado apenas quando não houver preferências locais. Use **Restaurar links sugeridos** para corrigir URLs iniciais sem apagar ícones personalizados.

## Limitações
Os endereços GitHub Pages dos apps são sugestões construídas a partir dos nomes dos repositórios, não atestados de que cada site esteja publicado. Projetos sem hospedagem não abrem diretamente. Não há sincronização remota automática nem alteração de arquivos no GitHub a partir do painel.
