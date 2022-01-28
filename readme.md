
### Curl command for curl request-2

-curl https://jsonplaceholder.typicode.com/posts/5 (make a get request to /users endpoint and retrieve the 3rd user)

-curl -X GET https://jsonplaceholder.typicode.com/posts/5 (use the explicit flag ( which means use -X ))

-curl -o 5_X.txt -X GET https://jsonplaceholder.typicode.com/posts/5 (store into a file called 5_X.txt)