# Oauth 

We use [Django Oauth Toolkit] (https://django-oauth-toolkit.readthedocs.org/). Each client must make a endpoint call to - [<code>POST</code> o/token/] (endpoints/o-token.md) to obtain an Oauth2 token. 

# Endpoints

The following are public API endpoints for Volley. Note that calls to the endpoints require Oauth authentication (see above).

## Search
- [<code>GET</code> search/string] (endpoints/search-string.md)
- [<code>GET</code> search/email] (endpoints/search-email.md)

## Oauth
- [<code>POST</code> o/token/] (endpoints/o-token.md)

