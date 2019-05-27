# JS vs Rust-to-Wasm Fannkuch

View online [here](https://alexcrichton.github.io/rust-fannkuch-js-and-wasm/index.html)

View locally with:

```
python -m SimpleHTTPServer
```

Build locally with:

```
sh build.sh
```

---

Sample console output on Firefox nightly on a mac:

```
wasm fannkuch: 7825ms
js fannkuch: 2719ms
```

## Notes on standalone benchmarks

The script fannkuch.js can be run in a JS shell and runs JS fannkuch(11) and prints the time.

The script benchmark.js can also be run in a JS shell and runs Rust fannkuch(11) by default and prints the time, if rust.wasm is present in the current directory.
