# Brazilian Market on WooCommerce #
**Contributors:** [claudiosanches](https://profiles.wordpress.org/claudiosanches/)  
**Donate link:** https://apoia.se/claudiosanches  
**Tags:** woocommerce, checkout, brazil, cpf, cpnj  
**Requires at least:** 4.0  
**Tested up to:** 6.2  
**Stable tag:** 3.8.2  
**Requires PHP:** 5.6  
**License:** GPLv2 or later  
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html  

Adds Brazilian checkout fields in WooCommerce

## Description ##

Adiciona novos campos para Pessoa Física ou Jurídica, Data de Nascimento, Sexo, Número, Bairro e Celular. Além de máscaras em campos e aviso de e-mail incorreto.

Em breve serão integradas mais novidades para o mercado brasileiro, como poder fazer login por CPF/CNPJ, ocultar alguns campos no carrinho, aguardem!

É necessário estar utilizando uma versão do [WooCommerce](http://wordpress.org/extend/plugins/woocommerce/) para que o Brazilian Market on WooCommerce funcione.

### Compatibilidade ###

Compatível desde a versão 5.0.x do WooCommerce.

Funciona com os plugins:

* [PagSeguro](http://wordpress.org/extend/plugins/woocommerce-pagseguro/) (adiciona as informações de **bairro**, **CPF** e **número**)
* [Bcash](http://wordpress.org/extend/plugins/woocommerce-bcash/) (adiciona as informações de **número**, **CPF**, **Razão Social** e **CNPJ**)
* [Moip](http://wordpress.org/extend/plugins/woocommerce-moip/) (adiciona as informações de **bairro** e **número** e melhora o Checkout Transparente)

### Dúvidas? ###

Você pode esclarecer suas dúvidas usando:

* Utilizando o nosso [fórum no Github](https://github.com/claudiosmweb/woocommerce-extra-checkout-fields-for-brazil/issues).
* Criando um tópico no [fórum de ajuda do WordPress](https://wordpress.org/support/plugin/woocommerce-extra-checkout-fields-for-brazil).

### Créditos ###

Foram utilizados os seguintes scripts/serviços de terceiros:

* [MailCheck jQuery](https://github.com/Kicksend/mailcheck).
* [jQuery Mask Plugin](https://github.com/igorescobar/jQuery-Mask-Plugin).

### Colaborar ###

Você pode contribuir com código-fonte em nossa página no [GitHub](https://github.com/claudiosmweb/woocommerce-extra-checkout-fields-for-brazil).

## Frequently Asked Questions ##

### Qual é a licença do plugin? ###

* Este plugin esta licenciado como GPL.

### O que eu preciso para utilizar este plugin? ###

* Ter instalado o plugin WooCommerce.

## Screenshots ##

### 1. Página de checkout usando o tema Storefront ###
![Página de checkout usando o tema Storefront](https://ps.w.org/woocommerce-extra-checkout-fields-for-brazil/assets/screenshot-1.png)

### 2. Página de edição de endereço de entrega usando o tema Storefront ###
![Página de edição de endereço de entrega usando o tema Storefront](https://ps.w.org/woocommerce-extra-checkout-fields-for-brazil/assets/screenshot-2.png)

### 3. Página de dados do pedido ###
![Página de dados do pedido](https://ps.w.org/woocommerce-extra-checkout-fields-for-brazil/assets/screenshot-3.png)

### 4. Configurações do plugin ###
![Configurações do plugin](https://ps.w.org/woocommerce-extra-checkout-fields-for-brazil/assets/screenshot-4.png)

### 5. Sugestão de e-mail ###
![Sugestão de e-mail](https://ps.w.org/woocommerce-extra-checkout-fields-for-brazil/assets/screenshot-5.png)


## Changelog ##

### 3.8.2 - 2023/05/01 ###

- Sugestão de e-mail agora pode ser traduzida.

### 3.8.1 - 2023/05/01 ###

- Atualizado arquivo de tradução.

### 3.8.0 - 2023/05/01 ###

- Adicionado suporte para versões atuais do WooCommerce.
- Removido suporte a versões anteriores a 3.0 do WooCommerce.
- Corrida aplicação de máscaras no checkout.
- Corrido retorno dos resultados para o hook `woocommerce_ajax_get_customer_details`. 

### 3.7.2 - 2019/09/26 ###

- Nome do plugin alterado de "WooCommerce Extra Checkout Fields for Brazil" to "Brazilian Market on WooCommerce".
- Removida opção obsoleta de preenchimento de endereço, no lugar dela utilize a integração direta que existe no plugin "Claudio Sanches - Correios for WooCommerce".
- Corrigido bug causado pelo WooCommerce na exibição do endereço de entrega na lista de pedidos no painel admininstrativo.

### 3.7.1 - 2019/09/24 ###

- Corrigido bug causado pelo WooCommerce na exibição do endereço de entrega na lista de pedidos no painel admininstrativo.

### 3.7.0 - 2019/09/20 ###

- Nome do plugin alterado de "WooCommerce Extra Checkout Fields for Brazil" to "Brazilian Market on WooCommerce".
- Removida opção obsoleta de preenchimento de endereço, no lugar dela utilize a integração direta que existe no plugin "Claudio Sanches - Correios for WooCommerce".

### 3.6.1 - 2018/05/24 ###

- Correção de mensagens dizendo que alguns campos eram opcionais, mesmo quando marcados como obrigatórios.

### 3.6.0 - 2017/05/12 ###

- Modificada a posição de todos os campos do formulário para funcionar melhor com temas que ainda não são totalmente compatíveis com o WooCommerce 3.0.

### 3.5.1 - 2017/04/26 ###

- Corrigido o posicionamento do campo de CEP.
- Corrigida a validação de CNPJ.

### 3.5.0 - 2017/03/04 ###

- Adicionado suporte ao WooCommerce 3.0.
- Alterado o plugin de máscara de [jquery.maskedinput](https://github.com/digitalBush/jquery.maskedinput) para [jquery.mask](https://github.com/igorescobar/jQuery-Mask-Plugin). (Possível com a ajuda de [Thiago Guimarães](https://github.com/thiagogsr)).
- Corrigida a máscara dos campos telefone e celular, permitido ter 10 ou 11 dígitos sem alterar a experiência do usuário. (Possível com a ajuda de [Thiago Guimarães](https://github.com/thiagogsr)).
- Alterados os tipos dos campos telefone, celular, cep, data de nascimento para `tel` quando o país selecionado for BR. (Possível com a ajuda de [Thiago Guimarães](https://github.com/thiagogsr)).
- Alterados os tipos dos campos cpf, cnpj para `tel` e e-mail para `email`. (Possível com a ajuda de [Thiago Guimarães](https://github.com/thiagogsr)).

## Upgrade Notice ##

### 3.8.1 ###

- Adicionado suporte para versões atuais do WooCommerce.
- Removido suporte a versões anteriores a 3.0 do WooCommerce.
- Corrida aplicação de máscaras no checkout.
- Corrido retorno dos resultados para o hook `woocommerce_ajax_get_customer_details`. 
- Atualizado arquivo de tradução.
- Sugestão de e-mail agora pode ser traduzida.
