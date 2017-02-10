# networking-examples
Simple Linux network tool examples.

## Bash, HTTP GET download and sleep 10 seconds
while true; do echo "Download..."; curl -s -XGET "<URL_ADDRESS_HERE>" > /dev/null; echo "Sleep..."; sleep 10; done

