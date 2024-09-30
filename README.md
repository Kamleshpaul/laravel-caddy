# laravel-caddy

This is a caddy template for laravel 

> NOTE : There is better way to host caddy with laravel read here : https://codingtricks.co/boost-laravel-performance-running-octane-with-frankenphp-in-production

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

---
## Usage

```sh
import snippets/*

# Use the "laravel-app" snippet for our site:
import laravel-app exmaple.com /var/www/html/laravel-app
```
---

> __NOTE : -__  Edit you php version [here](https://github.com/Kamleshpaul/laravel-caddy/blob/d695b143d5ec0230507ed5d80d96a073577a9467/snippets/laravel-app.conf#L18) which you want to use and install in you OS
