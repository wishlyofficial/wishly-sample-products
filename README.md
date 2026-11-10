# Wishly — Fictional product sample site

This **public** test site contains only six fictional fashion products and original AI-generated sample photos. It is **not** the real Wishly app. No user data, app code, credentials, retailer listings, checkout, or tracking are included.

## Publish for free with GitHub Pages

1. Open your separate public repository **wishlyofficial/wishly-sample-products** on GitHub.
2. **Unzip** the supplied ZIP on your computer. Upload the **contents inside** `wishly-sample-products` (not the ZIP itself, and not a surrounding folder) to the repository root using **Add file → Upload files**. Commit the files.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, **main**, **/(root)**, then **Save**.
4. When GitHub Pages finishes deploying, visit `https://wishlyofficial.github.io/wishly-sample-products/` in a private/incognito window.
5. Click a product. Give Lovable the full URL of a product page to test importing the name, fictional brand, USD price, description, and image.

GitHub Pages public hosting is free under GitHub's applicable free-plan terms; Lovable/Firecrawl usage may still consume credits. Never upload private Wishly data here.

### Product page URL pattern

`https://wishlyofficial.github.io/wishly-sample-products/products/mila-ribbed-midi-dress/`

Replace the slug with another product listed in the catalog.

### Note about image import

The sample pages expose the image via HTML and metadata, and JSON-LD structured product data. Some importers require an **absolute image URL** rather than a relative URL. If image import fails but other fields work, configure the importer to resolve image URLs against the fetched product-page URL, or convert the metadata to an absolute public URL after publishing.
