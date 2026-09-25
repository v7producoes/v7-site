# v7-site-novo

Site novo da V7 Produções (setembro/2026). Um arquivo só (`index.html`) + pasta `assets/`, sem build.

## O que tem
- Topo com frase-âncora e celular mostrando a IA atendendo às 02:14 e salvando o contato
- O problema (ferramentas soltas) + dado da HBR (23%)
- O sistema V7: ciclo Atrai → Atende → Organiza → Traz de volta + os 4 módulos
- Para cada tipo de cliente: do zero / refazer site / conectar peças soltas
- Projetos: Vivian Boa Sorte, StockCars, Adega do Zaca
- Os 21 posts do Instagram como portfólio de conteúdo
- Como funciona, Planos (tabela de 18/08), Dúvidas, chamada final

## Onde editar
No `<script>` no fim do `index.html`:
- `WHATSAPP_NUMBER`: número que recebe os cliques
- `META_PIXEL_ID`: cole o ID do Pixel para medir cliques no WhatsApp (evento Contact) nos anúncios

Cada botão de WhatsApp tem a própria mensagem pronta no atributo `data-wa`.

## Publicar
Este repositório (github.com/v7producoes/v7-site) publica sozinho em https://v7producoes.netlify.app a cada push na branch main.
