# Dockerfile for Stanford CoreNLP Server
This Dockerfile builds the [Stanford CoreNLP
Server](http://stanfordnlp.github.io/CoreNLP/corenlp-server.html) and exposes
the endpoint on port 9000. Requests are made as covered in the documentation.

# Running
```bash
docker run \
   -d \
   -p 9000:9000 \
   --name=corenlp \
   Koenkk/corenlp
```
