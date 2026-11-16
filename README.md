# Terra Nobre
PWA de catálogo imobiliário, publicado pelo GitHub Pages.

## Uso
Abra Gestão e entre com a conta administrativa configurada. Defina o WhatsApp principal e cadastre os imóveis. Cada anúncio aceita um WhatsApp próprio, até 12 fotos, preço, área, cidade, descrição e publicação/rascunho.

Os dados e fotos são compartilhados entre dispositivos. Favoritos ficam no navegador. A sessão administrativa fica apenas na sessão do navegador. Não há senhas nem chaves de serviço no repositório.

## Publicação
A página de entrada é index.html na raiz. Manifesto e service worker usam caminhos relativos para /TERRA-NOBRE/. Ícones PNG 192 e 512 incluídos. O service worker armazena só os arquivos do app, nunca respostas do banco ou credenciais.

## Verificação
JavaScript verificado sintaticamente. Regras RLS e conta verificadas no banco. Teste visual, instalação e login HTTP devem ser verificados em navegador.
