#1. Image Sitemap for Shopify
Image sitemap is one of the important SEO requirement but unfortunately it's not provided by Shopify in core features. 

Go to your Admin > Themes and "Edit Theme Code". Then you just need to create a new template and copy this code. Then save it, publish this template as a page. 

Check the XML URL in your Google Search Console account!


#2. Paginated Pages Canonical Tag

Shopify makes paginated pages in collections self-canonical. It means if the main collection page URL is /collections/pants and second page URL is /collections/pants?page=2. Second page's canonical tag is /collections/pants?page=2 but I have to change it as /collections/pants.

You just need to copy and paste this code into your main collection liquid template, then save it. Congrats, you fix the canonicalization issue on paginated pages 👏
