=== Etiqueta e declaração dos Correios para WooCommerce ===
Contributors: siteswp, alexkoti
Donate link: https://siteswp.com.br/contato/
Tags: woocommerce, shipping, correios, Brasil
Requires at least: 5.2
Tested up to: 6.5.5
Stable tag: 1.0.9
Requires PHP: 7.2
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Imprimir etiquetas de pedidos e declaração de conteúdo para os Correios do Brasil, para pedidos gerados no WooCommerce. Criado por SitesWP.

== Description ==

### O que este plugin faz?
Geração das etiquetas de envio dos Correios e também as declarações de conteúdo para os pedidos realizados no WooCommerce.

### Para quem é este plugin?
Negócios que estejam começando e ainda não possuem integração com serviços externos de entrega que cuidam do processo de geração de etiquetas e declaração.

= Campos adicionais =
Este plugin adiciona o campo "CPF/CNPJ" em WooCommerce > Configurações > aba Geral > Endereço da loja. Este campo é necessário para o preenchimento correto da declaração de conteúdo.

= Personalização =
É possível definir o logo da loja que irá aparecer na etiqueta.
O nome da loja na etiqueta usará a mesma informação cadastrada em Configurações > Geral

= Compatibilidade =

Requer WooCommerce 3.0 ou posterior para funcionar.

Requer WooCommerce Extra Checkout Fields for Brazil para funcionar. Este plugin é necessário para que os pedidos possuam corretamente os campos de número de endereço, bairro, CPF e CNPJ.

== Installation ==

= Instalação do plugin: =
- Envie os arquivos do plugin para a pasta wp-content/plugins, ou instale usando o instalador de plugins do WordPress.
- Ative o plugin.

= Após a instalação: =
- Acesse a lista de pedidos, marque o checkbox ao lado de cada pedido que deseja imprimir, e acione o botão "Imprimir Pedidos Selecionados".
- Ou clique no botão individual ao lado do nome de cada pedido
- Na etapa seguinte, você poderá escolher entre imprimir etiquetas ou declaração

== Frequently Asked Questions ==

= Este plugin tem integração com o sistema SIGEP Web dos Correios? =

Não, esta integração está fora do escopo deste plugin, que é voltado para lojas em estágio inicial de operação.

= É gerado arquivos PDF das etiquetas e declaração? =

Não, este plugin utiliza do recurso nativo de impressão do navegador, onde você poderá escolher a impressora ou "salvar como PDF".

= Reportar erros ou sugestões de código =

Pode utilizar a área de suporte aqui no WordPress ou enviar Issue ou PR no [github](https://github.com/siteswp-team/siteswp-wc-print-orders-brazil).

== Screenshots ==

1. Lista de pedidos com os botões de impressão.
2. Página de impressão de etiquetas.
3. Página de impressão de declaração de conteúdo.

== Changelog ==

= 1.0.9 - 2024.06.28 =
* Exibir corretamente o CNPJ na declaração de conteúdo, quando o comprador for pessoa jurídica

= 1.0.8 - 2024.04.26 =
* Registrar logs de geração e erros do código de barras. Os logs estarão disponíveis em WooCommerce > Status > Logs item 'siteswp-wc-print-orders-brazil'

= 1.0.7 - 2024.03.11 =
* Tradução do nome do plugin para PT-BR

= 1.0.6 - 2024.03.08 =
* Compatibilidade com HPOS
* Ajuste de permissão para "Gerente de loja" acessar as impressões

= 1.0.5 - 2023.09.26 =
* Ajuste de compatibilidade plugin Correios 4.1.5, mostrar selos de método de envio conforme nova versão API Correios

= 1.0.4 - 2023.08.16 =
* Atualização pacote picqer/php-barcode-generator

= 1.0.3 - 2023.05.27 =
* Adição da informação CPF/CNPJ na etiqueta, junto ao nome do remetente
* Possibilidade de adicionar o logo da loja na etiqueta, pelo painel "Personalizar"
* Sinalizar na etiqueta métodos de envio impresso e carta

= 1.0.2 - 2022.09.22 =
* Correção para código de barras vazio
* Ajuste exibição de informação 'Empresa' vazia

= 1.0.1 - 2022.09.21 =
* Correção exibição de selo de método PAC
* Melhoria na exibição de aviso de informações vazias

= 1.0.0 - 2022.09.12 =
* Lançamento inicial
