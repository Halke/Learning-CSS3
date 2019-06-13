## FAST HTML Tags Reference

 - UTF-8
    ```
    <meta charset="utf-8">
    ```
 - Responsive
    ```
    <meta name="viewport" content="width=device-width, initial-scale=1">
    ```
 - <meta http-equiv="X-UA-Compatible" content="IE=edge">
 - <meta name="description" content="">
 - Favicon
    - [Favicon-Generator.org](https://www.favicon-generator.org/)
    ```
    <link rel="icon" href="img/favicon.png" />
    ```
 - [MIME Types](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Basico_sobre_HTTP/MIME_types)
    - O MIME type é o mecanismo para dizer ao cliente a variedade de documentos transmitidos: a extensão de um nome de arquivo não tem significado na web. Portanto, é importante que o servidor esteja configurado corretamente, de modo que o MIME-type correto seja transmitido com cada documento. Os navegadores costumam usar o MIME-type para determinar qual ação usar como padrão para fazer quando um recurso é obtido.
    - Existem muitos tipos de documentos, por isso há muitos MIME-types. 
 - Open Graph Protocols
   - [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/sharing/?q=http%3A%2F%2Fb7web.com.br%2Fmetashare%2F)
   - Meta Tags Post Share
   ```
   <meta property="og:url" content="http://b7web.com.br/metashare">
   <meta property="og:type" content="article">
   <meta property="og:title" content="Titulo do nosso artigo">
   <meta property="og:description" content="descrição do artigo">
   <meta property="og:image" content="http://b7web.com.br/metashare/titulo_teste.png">
   <meta property="og:image:type" content="image/png">
   <meta property="og:image:width" content="1200">
   <meta property="og:image:height" content="630">
   <meta name="twitter:card" content="summary_large_image">
   <meta name="twitter:site" content="@jgthms">
   <meta name="twitter:creator" content="@jgthms">
   ```