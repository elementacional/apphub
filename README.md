# AppHub Studio — Painel de aplicativos

Painel HTML estático, dark e responsivo, para reunir seus aplicativos em um único menu.

## Iniciar

Abra `index.html` em um navegador de desktop ou publique o arquivo na raiz de um repositório com GitHub Pages ativado em **Settings → Pages → Deploy from a branch → main / (root)**.

## Recursos

- 21 atalhos iniciais baseados nos repositórios GitHub da conta `elementacional`.
- Atalho **PageForge** direciona ao GitHub Pages; os demais direcionam ao repositório (altere o endereço para a URL do app hospedado, se houver).
- Adicionar, editar e excluir aplicativos.
- Upload de arquivos `.svg` para ícones (SVG básico, sem scripts ou referências externas).
- Busca instantânea e ordenação por arrastar e soltar no desktop.
- Exportação e importação de catálogo JSON.
- Interface escura responsiva, sem frameworks externos.

## Importante sobre persistência

As alterações são salvas em `localStorage`, **somente naquele navegador e dispositivo**. Elas não alteram automaticamente o site publicado para todos os visitantes. Para publicar um catálogo personalizado permanente, é necessário atualizar os dados iniciais dentro do `index.html` e republicá-lo ou acrescentar uma camada de armazenamento remoto. O JSON exportado serve como backup ou para importar a configuração em outro navegador.

## Segurança e privacidade

Não há envio de arquivos SVG nem dos atalhos para um servidor. Os ícones SVG são exibidos localmente como imagens. Evite importar configurações de origem desconhecida.

## Arquivos

- `index.html` — aplicativo autônomo.
- `README.md` — instruções.
- `.nojekyll` — compatibilidade com publicação estática no GitHub Pages.
