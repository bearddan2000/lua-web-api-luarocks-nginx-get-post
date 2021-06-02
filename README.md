# lua-web-api-luarocks-nginx-get-post

## Description
Embedded lua in nginx config file
with JSON support. Allows for get
and post actions.

## Tech stack
- lua
  - reqargs
- nginx

## Docker stack
- openresty/openresty:alpine

## To run
`sudo ./install.sh -u`
- GET curl localhost
- POST curl -H "Content-Type: application/json" -X POST -d '{"id": 1, "username":"xyz","pass":"foobar"}' localhost

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://ketzacoatl.github.io/posts/2017-03-02-lua-and-openresty-hello-world-examples.html
