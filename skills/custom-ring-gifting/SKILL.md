# Custom Ring Gifting Skill

## Description
This skill enables the agent to assist users in designing, customizing, and gifting rings using the Shopify MCP server.

## Trigger Scenarios
- The user expresses intent to buy a ring as a gift.
- The user asks about customizing rings (e.g., engraving, material, sizing).
- The user wants to send a customized jewelry gift directly to someone's address.

## Workflow
1. **Gather Requirements:** Ask the user for the recipient's preferences (metal type, gemstone, ring size, engraving text).
2. **Search Inventory:** Use the Shopify MCP `products_search` tool to find customizable ring base models.
3. **Customize:** Guide the user through the customization options.
4. **Checkout & Shipping:** Collect the recipient's shipping details and use Shopify MCP to generate a checkout/gift link or place the order.
5. **Confirmation:** Confirm the gift order details and estimated delivery.

## Required MCP Tools
- `shopify_search_products`
- `shopify_get_product_details`
- `shopify_create_cart`
- `shopify_add_to_cart`

