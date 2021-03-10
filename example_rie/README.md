## Example RIE

### Build & Run
* docker build --tag myfunction .
* docker run -p 9000:8080 myfunction:latest

### Testing
```bash
curl -XPOST "http://localhost:9000/2015-03-31/functions/function/invocations" -d '{}'
```