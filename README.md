# Catálogo digital NEXUS (demonstrativo)

Landing page frontend estática baseada na versão clara do export do Google Stitch. A marca, os produtos, preços, textos comerciais e disponibilidade atuais são exemplos e devem ser substituídos antes da publicação.

## Executar localmente

Abra index.html em um navegador ou sirva esta pasta com um servidor estático. Não há backend nem etapa de build. Tailwind CSS e Google Fonts são carregados por CDN; esses estilos e fontes requerem conexão à internet.

## Configuração antes da publicação

1. Em config.js, configure o número oficial de WhatsApp em formato internacional, somente dígitos. Os links de contato permanecem inativos enquanto o valor for o placeholder.
2. Revise produtos, preços, promoções, estoque, variantes, textos, contatos e redes sociais. Os dados de catálogo estão em products.js; conteúdo e imagens estão no index.html.
3. As imagens do Stitch são URLs remotas hospedadas no Google, não arquivos locais incluídos neste projeto. A origem/licença de cada imagem deve ser confirmada antes de redistribuir publicamente; substitua-as por assets cuja utilização esteja autorizada.
4. Atualize a identificação NEXUS e o conteúdo institucional para os dados reais da empresa.

## Funcionalidades

- Pesquisa reativa por nome, filtro por categoria, ordenação por preço e estado sem resultados.
- Preços promocionais, indicador de indisponibilidade e botão de pedido desabilitado para itens sem estoque.
- Seleção de cor e quantidade nos pedidos por produto.
- Links individuais de WhatsApp e botão flutuante, com mensagem codificada no navegador.
- Navegação adaptada para dispositivos móveis.

O projeto não coleta nem envia dados para um backend. A ação de pedido abre o WhatsApp após configurar o contato.

## Versão

Esta entrega corresponde à versão 1.0.0. O resumo está em CHANGELOG.md.
