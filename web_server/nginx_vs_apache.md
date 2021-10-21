Nginx vs Apache, main difference: https://www.youtube.com/watch?v=ZhfpYgl8BtQ: 

We can place nginx in front of apache as a server proxy,  to handle all the client requests, this taks advantage of fast processing speed of nginx and ability to handle large number of connections simultaneously. for static content, which nginx excels at, the files will be shared quickly and directly to the client, for dynamic content, e.g. php files, nginx will proxy the request to apache, which can then process the results and return the rendered the page, nginx can then pass the content back to the client.

This model will allow you to have a very funtional webserver and to server your users (large volumn) very fast 