# Website

To run the website locally, execute the command below.

```shell
docker run --rm -it -v "$PWD:/src" -v "$PWD/target:/target" -p 1313:1313 klakegg/hugo:0.69.0-ext-alpine server
```
