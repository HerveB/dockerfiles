# Example Usage
```
docker run -it --rm \
  --name webgrind \
  -p 80:80 \
  -v </path/to/data>:/cachegrind \
  cbolt/webgrind
```
