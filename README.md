# Jimson
### JSON-RPC 2.0 Client for Ruby
[![Build Status](https://travis-ci.org/chriskite/jimson.svg?branch=master)](https://travis-ci.org/chriskite/jimson)

## Quick Start
    require 'jimson'
    client = Jimson::Client.new("http://www.example.com:8999") # the URL for the JSON-RPC 2.0 server to connect to
    result = client.sum(1,2) # call the 'sum' method on the RPC server and save the result '3'

## JSON Engine
Jimson uses multi\_json, so you can load the JSON library of your choice in your application and Jimson will use it automatically.

For example, require the 'json' gem in your application:
    require 'json'

