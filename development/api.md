# Oauth 

We use [Django Oauth Toolkit] (https://django-oauth-toolkit.readthedocs.org/). Each client must make a endpoint call to - [<code>GET</code> o/token/] (readme/development/api.md) to obtain an Oauth2 token. 

# Endpoints

The following are Volley's public api endpoints. Note that calls to the endpoints require Oauth authentication (see above).

## Search
- [<code>GET</code> search/string] (readme/development/api.md)
- [<code>GET</code> search/email] (readme/development/api.md)

## Oauth
- [<code>GET</code> o/token/] (readme/development/api.md)

