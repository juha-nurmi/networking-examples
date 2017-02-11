# networking-examples
Simple Linux network tool examples.

## Bash, HTTP GET download and sleep 10 seconds
```sh
while true; do echo "Download..."; curl -s -XGET "<URL_ADDRESS_HERE>" > /dev/null; echo "Sleep..."; sleep 10; done
```

```sh
sudo iftop -i eth0 -f DESTINATION_IP_ADDRESS
```
