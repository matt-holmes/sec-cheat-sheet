# sec-cheat-sheet

## Docker Images
##### Damn Vulnerable Web Application:
https://github.com/digininja/DVWA
`docker container run --rm -it -p 80:80 vulnerables/web-dvwa`

##### crAPI 
https://github.com/OWASP/crAPI 
`docker-compose -f docker-compose.yml --compatibility up -d`
http://localhost:8888

##### Pixi
https://github.com/DevSlop/Pixi
`/Users/mattholmes/Projects/sec-tools/owasp-pixi/Pixi`
`docker compose up`
http://localhost:8000

##### Juice Shop
https://github.com/juice-shop/juice-shop
`docker run --rm -p 3000:3000 bkimminich/juice-shop`
http://localhost:3000/

#### Damn Vulnerable GraphQL Application
https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application
`docker run -t -p 5013:5013 -e WEB_HOST=0.0.0.0 dolevf/dvga`
http://localhost:5013