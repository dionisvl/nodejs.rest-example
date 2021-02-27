## Examples

```
curl -i -X POST -H 'Accept: application/json' \
    -H 'Content-type: application/json' http://localhost:3000/programming-languages \
    --data '{"name":"dart", "released_year": 2011, "githut_rank": 13, "pypl_rank": 20, "tiobe_rank": 25}'

curl -i -X PUT -H 'Accept: application/json' \
    -H 'Content-type: application/json' http://localhost:3000/programming-languages/17 \
    --data '{"name":"dart", "released_year": 2011, "githut_rank": 12, "pypl_rank": 20, "tiobe_rank": 25}'

curl -i -X DELETE -H 'Accept: application/json' \
    -H 'Content-type: application/json' http://localhost:3000/programming-languages/17
```

### source
https://blog.logrocket.com/node-js-express-js-mysql-rest-api-example/