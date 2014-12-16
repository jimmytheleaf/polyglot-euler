# Polyglot Euler

Solutions to [Project Euler](https://projecteuler.net/) problems 1-10 in a variety of different languages.

I don't particularly go for efficiency in these; mostly I'm interested in exploring different facilities of the languages.

To run solutions:

## Python

    python run_python.py

## Javascript / ES6

    # Required for ES6 features
    nvm install 0.11.14

    npm install
    npm run-script solve


## Lua

    # Required to read files and accurate timing
    luarocks install lua-cjson
    luarocks install luasocket
    
    lua run_lua.lua