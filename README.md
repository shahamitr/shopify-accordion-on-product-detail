# shopify-accordion-on-product-detail
Accordion based details on product description page on shopify store.

1. Upload accordion.css in <b>assets/</b> folder.
2. Upload accordion.js in <b>assets/</b> folder.
3. Copy data from <b>demo-product-description.txt</b> file and add it into any of the product detail page.
4. Copy <code><script src="{{ 'accordion.js' | asset_url }}" defer="defer"></script></code> to the <b>layout/theme.liquid</b> before end of the body tag.
5. Copy <code>{{ 'accordion.css' | asset_url | stylesheet_tag }}</code> to the <b>layout/theme.liquid</b> in the head section.
6. Please refer screenshot which sare there in repo which will demonstrate how the accordion will look like.

Once this is done, open the product detail page, you should see accordion there with demo data.
