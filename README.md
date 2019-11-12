# Reverse Proxy for Intercom support pages

Intercom requires an SSL reverse proxy for custom domains. See [their docs](https://developers.intercom.com/installing-intercom/docs/set-up-your-custom-domain).

This project uses Nginx to implement sucha a reverse proxy on Heroku.

## Credits

Based on [funwhilelost/heroku-reverse-proxy](https://github.com/funwhilelost/heroku-reverse-proxy),
originally forked from [api-proxy-3scale-heroku](https://github.com/Taytay/api-proxy-3scale-heroku).
