# Oauth 

We use [Django Oauth Toolkit] (https://django-oauth-toolkit.readthedocs.org/). Each client must make a endpoint call to - [<code>GET</code> o/token/] (readme/development/api.md) to obtain an Oauth2 token. 

# Endpoints

The following are public API endpoints for Volley. Note that calls to the endpoints require Oauth authentication (see above).

## Search
- [<code>GET</code> search/string] (readme/development/api.md)
- [<code>GET</code> search/email] (endpoints/search-email.md)

## Oauth
- [<code>GET</code> o/token/] (readme/development/api.md)

