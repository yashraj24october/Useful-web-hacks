## Easy ‘100’ SEO achieving technique:

1. Add meta description of site in ```` <head> ````: <br>
````html
   <meta name="description" content="Description about site">
````
<br><br>
2. Add <b>robots.txt</b> file in your project root directory
and add this content in it:<br>
User-agent: * Disallow: /admin/ <br>
Disallow: /private/ <br>
Allow: /public/ <br>
Sitemap: https://www.example.com/sitemap.xml<br><br>
3. Must add <b>alt</b> attribute on each img elements of site

### Additional for increasing site speed and performance

Create CDN of your static files and use it in your project.<br>
It will significantly reduce memory load on your server and definetly boost the site performance!
