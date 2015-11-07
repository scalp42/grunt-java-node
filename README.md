# node-java-grunt

Docker container with grunt, node and java.

### Running

Go in your code directory and for example:

```
docker run --rm -ti -v "$PWD:/app" scalp42/node-java-grunt bash -c 'npm install ; /usr/local/bin/grunt package --verbose'
```
