# README #

This project is simple Node JS file to test HTTP get and post.


### How to run the project ###

*  1. Please go to project folder from terminal.
*  2. Type command 'node testpost.js'
*  3. Please access http://127.0.0.1:8081 from browser or postman. You can call the server with both POST and GET. You can append with any directive as well. Eg: http://127.0.0.1:8081/get



### Sample CURL command ###

* 1. Please run following curl command for http://127.0.0.1:8081/get <br/>
  curl -X GET \
  http://127.0.0.1:8081/get \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 61e6539a-1f54-5aad-5d5d-0283a7fe8423'

* 2. Please run following curl command for http://127.0.0.1:8081 (GET) <br/>
  curl -X GET \
  http://127.0.0.1:8081/ \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 4f0adc8d-6409-c72a-ab60-3842d46bc2fa'

* 3. Please run following curl command for http://127.0.0.1:8081/post <br/>
  curl -X POST \
  http://127.0.0.1:8081/post \
  -H 'cache-control: no-cache' \
  -H 'postman-token: adcdec51-04c2-437c-e971-50d430049222'

*  4. Please run following curl command for http://127.0.0.1:8081 (POST) <br/>
  curl -X POST \
  http://127.0.0.1:8081/ \
  -H 'cache-control: no-cache' \
  -H 'postman-token: 341b8e1b-6c0b-c5fc-be2d-dd37bd68eb18'

### SAMPLE RESPONSE ###

* Response will include headers, method, url and body. <br/>
Please see sample response.

{
    "headers": {
        "host": "127.0.0.1:8081",
        "connection": "keep-alive",
        "content-length": "0",
        "cache-control": "no-cache",
        "origin": "chrome-extension://fhbjgbiflinjbdggehcddcbncdddomop",
        "user-agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_3) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/61.0.3163.100 Safari/537.36",
        "postman-token": "fc8c322f-234f-e52b-5a86-742308b27965",
        "accept": "*/*",
        "dnt": "1",
        "accept-encoding": "gzip, deflate, br",
        "accept-language": "en-US,en;q=0.8,en-GB;q=0.6"
    },
    "method": "POST",
    "url": "/",
    "body": ""
}

