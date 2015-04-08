# jq docker image

## Description

jq is like sed for JSON data – you can use it to slice and filter and map and
transform structured data with the same ease that sed, awk, grep and friends
let you play with text

This image allows you to run jq in a completelly containerized environment

One of the benefits of this image over the others is its small size

## How to use this image

Process a json file from stdin

```
cat file.json | docker run -i --rm fr3nd/jq '.'
```
