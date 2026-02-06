```shell
curl -i -X POST \
  -H "Content-Type: application/json" \
  -H "X-GitHub-Event: push" \
  -d '{}' \
  https://http://192.168.80.76:8080/github-webhook/
```