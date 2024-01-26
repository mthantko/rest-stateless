stateless -> curl -X POST -H 'Content-Type: application/json' -d '{"number":17}' http://localhost:8080/counter/stateless/countUp
stateful -> curl -b cookies.txt -c cookies.txt -X POST http://localhost:8080/counter/stateful/countUp
