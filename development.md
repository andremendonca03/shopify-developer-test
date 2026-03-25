# Product Template Development

## 1. Product Images

My approach was simply adjusting Horizon's original styles for the block to match the aspect ratio from the Figma reference.


## 2. Size and Colour Variants

I used 3 metafields under products to create the colour functionality:

- Label:
  - The name of the colour to display in the product template;
- Colour:
  - Colour picker for the colour 'variant';
- Sibling Collection (referencing to collections):
  - A special collection to group only sibling products of the same type, so they can be queried together.

For the size variants, I simply styled Shopify's existing component to match the designs. To avoid going over the 2 hours, I haven't fixed the spacing between the items to bring them closer together.


## 3. Description and ATC Buttons

Only basic style changes applied to these blocks.


## 4. USP Icons and Accordions

I decided to use metafields and a metaobject to implement these. Since different product could have different USPs, the scenario is that the client would create all USPs required and assign them to products.

The next step to complete these would be simply displaying on the template from the metafield object within the product.

Regarding the accordions, I used static metafields instead of a metaobject with entries, since I believe the client wouldn't require multiple accordion sections. Therefore, I created 3 rich-text metafields under products, that would generate each accordion with its content.


## 5. Related Products Section

These section was basically customised from Horizon's Recommended Products default section.


## 6. Image Text Section

Haven't had time to start on this section but the setup would be similar to the previous section, using Horizon's 'Image With Text' instead.


## 7. Global CTA Section

For the optional background image, my approach would be a simple toggle setting on the block theme editor, so the client could either activate or deactivate the background SVG.
