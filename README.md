# erlyrest
A wrapper over cowboy web server, simplifies the development of restfull api
#### features
  - simplifies handling of http request. You don't need to start cowboy and its dependencies obviously (all incapsulated)
  - provides several built-in request validating features: *ip whitelist filter, basic auth, alowed methods*
  - built-in body decoding/encoding. Supports *xml, json, form_urlencoded, multipart data (without files), automatic detection*
  - built-in workflow, that allows you to create buisness logic by passing functions as parameters to erlyrest.

You can also:
  - interrupt your function flow at any place and response on http request by calling *erlyrest:reply/2*  (non functional style, but can be useful in some cases)
  - 
### installation
You just need to add *erlyrest* dependency in your projects *rebar.config* file
``` erlang 
{deps, [
        ...
    {erlyrest,      ".*", {git, "https://github.com/sergebond/erlyrest.git",      {branch, "master"}}}
    ]}.
```
### usage examples

  - 
