Routes
======

Placeholder, actual project coming soon :)

Warning: Uses ASP.NET vNext which alpha/beta tech. Not for production.

Super simple "static" website builder. Write your views (partitial views or parts) as pure HTML. Define routes in json format and give each route one or more views that should be associated with it.

Routes and views are found in the /app folder.

- Uses XHR (Ajax, XMLHttpRequest) to load route data and views.
- SEO enabled via live snapshots.
- Live sitemap.xml
- Child views are identified by a query selector. Ex.: #container, div.menu
- Default views can be defined in defaults.json

Install
- clone
- kpm restore
- Add some views and routes, see example.

Run
- k web
- (IIS, when it supports vNext.)

"Sometimes you just want to write HTML content and serve it at a URL."
