# laravel-caddy

This is a caddy template for laravel 

## Prerequisites

- [x] Caddy v2

## How install caddy

https://caddyserver.com/docs/install

## Deployment

Step 1 : - 
```sh 
cd /etc/caddy/
```

Step 2 : - 
```sh 
git clone https://github.com/Kamleshpaul/laravel-caddy.git
```

Step 3 : - 

edit `Caddyfile` based on the example [Caddyfile](./Caddyfile.example)

-----
## Usage

```sh
import snippets/*

# Use the "laravel-app" snippet for our site:
import laravel-app exmaple.com /var/www/html/laravel-app
```
