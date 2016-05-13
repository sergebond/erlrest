# erlyrest
A wrapper over cowboy web server, simplifies the development of rest api
#### features
  - simplifies start of http listeners. You don't need to start cowboy and its dependencies obviously (all incapsulated)
  - provides several built-in validating features: *ip whitelist filter, basic auth, alowed methods*
  - built-in request-body decoding to erlang terms. Supports *xml, json, form_urlencoded, multipart data (without files), automatic detection*
  - built-in response-body encoding. Supports *xml, json, form_urlencoded*
  - built-in workflow, that allows you to create buisness logic by passing functions as parameters to erlyrest.

You can also:
  - Import and save files from GitHub, Dropbox, Google Drive and One Drive
  - Drag and drop files into Dillinger
  - Export documents as Markdown, HTML and PDF
