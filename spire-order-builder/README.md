# Spire order builder

Turns a customer's order email into CSV files for Spire (Tools → Import → Sales Order / Customers)
and for Shopify (Matrixify order import, Shopify customer import, or a checkout link).

Open the live page: https://vishnuarmointern.github.io/spire-order-builder/

## Using it
1. Click **Manage → Import Spire export** and load the inventory list exported from Spire (CSV or Excel).
   The list stays in your browser only. It is never uploaded to GitHub or anywhere else.
2. Paste the customer's email and click **Read email**. It fills in the customer (names, contact, billing and
   ship-to addresses, PO, required date) and the order lines. Highlighted fields came from the email.
3. Check and edit everything in step 2 and the order lines in step 3. Anything you type is never overwritten
   if you read the email again.

Optional: click **Use Claude here** and paste a Claude API key to have Claude read the email instead of the
built-in reader. The key is stored in your browser only.
4. Download the CSV(s) and import them in Spire. For a new customer, import the customer CSV first.
5. For Shopify, either download the Shopify order CSV and import it with the Matrixify app,
   or copy the checkout link and send it to the customer to pay.
   Click "Refresh from armodilo.com" now and then to pick up new Shopify products.

## Updating the page
Edit `index.html` and commit. GitHub Pages republishes in about a minute.
