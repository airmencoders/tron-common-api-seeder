## TRON API DEVELOPMENT SEED UTIL

This repo is used for development purposes to seed a local Common API's database with an entire Wing sized element (groups, squadrons, and members).

It is primarily intended to be used for the Tron API's docker compose stack.

However to use it as a standalone script, running:

    `node seeder.js` will send all REST requests to http://localhost:8088/api/v1 (TRON Common's default dev port), but this can be changed by defining the `PROXY` env var first...

    `PROXY=http://localhost:9000/api/v1 node seeder.js` will send all traffic thru localhost's 9000 port.

    
