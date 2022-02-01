# MdTF Comparison of Images Match Scores with FastAPI

One container is a Go example of MdTF Images Match Scores from

https://github.com/TheMdTF/mdtf-public/tree/master/rally2-matching-system/go-example

The other container is [FastAPI](https://fastapi.tiangolo.com/), a Python web framework, implementing a sample comparison of several images.

## To run locally

```
$ git clone https://github.com/frmbelz/mdtf-ex .
$ git submodule update --init
$ docker-compose up --build -d
```

FastAPI API's should open at
http://localhost:8181/

Go endpoint should be at
http://localhost:8080/





