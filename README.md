# Flask-Basic-Authentication

1.
curl -i -X POST -H "Content-Type: application/json" -d "{\"username\":\"kevin\",\"password\":\"python\"}" http://127.0.0.1:5000/api/users

2. 
curl -u kevin:python -i -X GET http://127.0.0.1:5000/api/resource


