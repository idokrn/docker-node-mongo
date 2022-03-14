## Quick Start

```bash
# clone this repo
git clone https://github.com/idokrn/docker-node-mongo.git && cd docker-node-mongo

# Build app depencencies
helm dependency build dnm

# Install the chart
# Replace the <NAME> with relevant name.
helm install <NAME> dnm

# Start a port forwarder.
kubectl port-forward service/dnm-service 9000:80
```

You can check that the app is working [Here](http://localhost:9000)
