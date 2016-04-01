##RESTful Programming  

REST is the underlyig architectural principle of the web. The key constraint is that the server and client must both agree on the media used, which in the case of the web is HTML.  An API that adheres to the principles of REST doesn't require the client to know anything about the strucutr of the API. Rather the server needs to provide the necessary information needed to interact with the service for the client.  

An example of this is a HTML form. The server specifies the location of the resource and the required fields. **The browser doesn't know in advance where to submit the information and it doesn't know in advace what information to submit. Both forms of information are entirely supplied by the server.**(HATEOAS principle)