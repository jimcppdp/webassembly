# webassembly
webassembly stuffs

compile
emcc hello.c -s WASM=1 -o hello.html

setup webserver to run
python3 -m http.server

run
open browser, and put http://[::]:8000/
