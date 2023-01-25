# Building Full Stack Applications With Python and ReactJS

<a href="https://www.youtube.com/watch?v=Jx39roFmTNg" >Video</a>

## Requirements

- Python3
- Node >= 19.x
- Gatsby

## Installation

Using <a href="https://fastapi.tiangolo.com/">FastAPI</a> to build the backend.

```bash
$ python3 -m venv py-env
$ source py-env/bin/activate
$ pip3 install fastapi
$ pip3 install "uvicorn[standard]"
$ cd backend
$ uvicorn main:app --reload
```
In a new bash window

```bash
$ npm i
$ gatsby develop
```