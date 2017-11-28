# ICE Hello World
A very simple ICE hello world example using a python server and a js browser client.

## Dependency
- You need to have Ice for Python installed `pip install zeroc-ice` (https://zeroc.com/downloads//ice#python)
- You need to have a http server installed I'm using http-server (https://www.npmjs.com/package/http-server)
- Optional: If you are going to change the ICE interface (Hello.ice) you need to have slice2js and slice2py (part of the python package) available to recreate the interfaces `npm install --save-dev slice2js` or `npm install --global slice2js` to use slice2js from command line 


## Start server with
```
cd hello_server
python Server.py
```

## Run client
From root do
`http-server`