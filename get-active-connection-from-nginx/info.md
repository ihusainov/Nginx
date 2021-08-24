# get-active-connection-from-nginx

```bash
curl --silent http://127.0.0.1:8899/stats | sed '3q;d' | awk '{ print "echo " $3"/"$2" | bc -l" }' | sh
```
