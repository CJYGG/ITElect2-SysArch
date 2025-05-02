
How to Test
1. Open XAMPP, start Apache.
2. Put this folder in `htdocs`.
3. Go to `http://localhost/my_api_gateway/docs.html` for docs.
4. Use Postman or curl to test.

API Key (set in config.php)
- `key123`
- `key456`

Endpoints

GET `/api/users`
Returns a list of users.

Header:  
X-API-Key: key123

Sample Response:
json
[
  {"id":1,"name":"Alice"},
  {"id":2,"name":"Bob"}
]
