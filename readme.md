Setup
```
$ cargo install trunk wasm-bindgen-cli
$ cd app 
$ rustup target add wasm32-unknown-unknown

$ sudo apt update
$ sudo apt install nodejs npm
$ sudo node -v  
$ sudo npm install n -g
$ sudo n stable
$ sudo apt purge -y nodejs npm
$ exec $SHELL -l

$ sudo npm i -g tailwindcss
$ tailwindcss -o ./tailwind.css

$ trunk serve
```

Build for css
```
// local dev
tailwindcss -o ./tailwind.css

// production
NODE_ENV=production tailwindcss -c ./tailwind.config.js -o ./tailwind.css --minify

```
