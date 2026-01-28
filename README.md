### Setup shopify cli
use node - 20+ version

1. `npm install -g @shopify/cli@latest` : ("To install shopify globally in your system")
2. `shopify version` : ("Check version of shopify")
3. login to your shopify store in web
4. `shopify theme dev --store=your_store_name` : ("To connect the shopify store 'Where your_store_name can be varry according to your store name'")
5. Confirm with verification in browser
6. Preview your theme : `http://127.0.0.1:9292` ("Locally with generated urls")


### Theme Structure:

/ Layout
    ----- theme.liquid
    
/ template
    ----- index.liquid (home page)
    ----- product.liquid (single product)
            - More on product read - [dev.docs](https://shopify.dev/docs/api/liquid/objects/product)

/ config
    ----- JSON schema for overall theme settings