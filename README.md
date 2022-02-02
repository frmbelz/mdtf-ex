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

API documentation
http://localhost:8181/docs

Go endpoint should be at
http://localhost:8080/

## FastAPI API

![FastAPI API](https://user-images.githubusercontent.com/989627/152093475-1f34682e-ef67-4a50-9409-cde85a0f30b8.png "FastAPI API")

## FastAPI Client Comparing Matching Scores

![FastAPI MdTF Comparing Images Matching Scores](https://user-images.githubusercontent.com/989627/152093632-667bf5d1-67ce-4670-af4c-7c5a7a9c4285.png "FastAPI MdTF Comparing Images Matching Scores")

![FastAPI API](https://user-images.githubusercontent.com/989627/152093702-4d036a97-1079-4460-b19b-1ce6e5f0a1ed.png "FastAPI API")



