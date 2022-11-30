# awesome-wasm
WebAssembly focus on Rust (on going)

![image](https://user-images.githubusercontent.com/97060/158044484-13e84872-a725-4710-88cb-7dff9fb8518f.png)
> https://coggle.it/diagram/YgSRKkMks4i53-Ps/t/webassembly-icon-wasm-webassembly

## Video
- `Lin Clark`: A Cartoon Intro to WebAssembly | JSConf EU 2017: https://www.youtube.com/watch?v=HktWin_LPf4
- What WebAssembly means for React - `Lin Clark` aka @linclark at @ReactEurope 2017: https://www.youtube.com/watch?v=3GHJ4cbxsVQ
- Bringing WebAssembly outside the web with WASI by `Lin Clark` 2019: https://www.youtube.com/watch?v=fh9WXPu0hw8
- `Ashley Williams` Rust, WebAssembly, and Javascript Make Three: An FFI Story - QCon 2019: https://www.infoq.com/presentations/rust-webassembly-javascript/
- `Lin Clark` — WebAssembly: Building a new kind of ecosystem 2020: https://www.youtube.com/watch?v=IBZFJzGnBoU
- `Lin Clark` on the Web Assembly Component Model: https://www.youtube.com/watch?v=HktWin_LPf4
- Keynote: WASI - A new kind of system interface & what it means for cloud native - `Lin Clark`, Fastly: https://www.youtube.com/watch?v=k3HDivg3xyc

## Extras
- `SIMD`: https://medium.com/wasmer/webassembly-and-simd-13badb9bf1a8
- `WASI`: https://wasi.dev/

## CloudFlare
- https://www.fpcomplete.com/blog/serverless-rust-wasm-cloudflare/
- https://github.com/cloudflare/serde-wasm-bindgen
  > An alternative native integration of [Serde](https://serde.rs/) with [wasm-bindgen](https://github.com/rustwasm/wasm-bindgen)

## Frontend
- Yew Stack: https://yew.rs/
  > Yew is a modern Rust framework for creating multi-threaded front-end web apps using WebAssembly.
- Gloo : https://github.com/rustwasm/gloo
  > Rust wrappers for browser, `web-sys/js-sys` replacement.
- Integrating a Svelte app with Rust using WebAssembly: https://blog.logrocket.com/integrating-svelte-app-rust-webassembly/
- WASM (with Rust) + Vite + Svelte Monorepo: https://github.com/dsegovia90/wasm-vite-svelte-monorepo
- Leptos: https://github.com/gbj/leptos

## DevOps
- Docker + WASM: https://wasmedge.org/book/en/frameworks/serverless.html
- Kubecon EU 2021 Keynote - Cloud Native and WebAssembly: Better Together: https://cosmonic.com/blog/kubecon-eu-2021-webassembly-keynote-cloud-native-and-wasm-better-together/
- WasmEdge in Kubernetes: https://wasmedge.org/book/en/kubernetes.html

## AI/ML
- Why would you use WebAssembly to put scikit-learn in the browser?: https://towardsdatascience.com/why-would-you-use-webassembly-to-put-scikit-learn-in-the-browser-77671e8718d6
- https://blog.tensorflow.org/2020/03/introducing-webassembly-backend-for-tensorflow-js.html
- https://blog.tensorflow.org/2021/05/high-fidelity-pose-tracking-with-mediapipe-blazepose-and-tfjs.html
- https://www.vedereai.com/supercharging-the-tensorflow-js-webassembly-backend-with-simd-and-multi-threading/
- https://arxiv.org/pdf/2110.07128.pdf

## Image Processing
- `Photon`: https://silvia-odwyer.github.io/photon/
  > Photon is a high-performance image processing library, written in Rust and compilable to WebAssembly, which can be used both natively and on the web.

## Blockchain
- https://arxiv.org/pdf/2012.01032.pdf

## Embedded systems
- https://rahul-thakoor.github.io/using-no-standard-library-crates-with-webassembly/
  > A good rule of thumb is that if a crate supports embedded and #![no_std] usage, it probably also supports WebAssembly.

## Security
- https://www.usenix.org/system/files/sec20-lehmann.pdf

## Rust
- Rust 🦀 and WebAssembly 🕸: https://rustwasm.github.io/docs/book/introduction.html

## State of...
- Talk: the Nuts and Bolts of Webassembly- 2019: http://sriku.org/blog/2019/08/24/talk-the-nuts-and-bolts-of-webassembly/
- Benchmark of WebAssembly runtimes - 2021 Q1: https://00f.net/2021/02/22/webassembly-runtimes-benchmarks/
- Rust and WebAssembly without a Bundler: https://tung.github.io/posts/rust-and-webassembly-without-a-bundler/

## Tools
- Package Manager: https://wapm.io/
- Watt: https://github.com/dtolnay/watt
  > Compiling macros ahead-of-time to Wasm.
- Twiggy🌱: https://rustwasm.github.io/twiggy/index.html
  > A code size profiler for Wasm.

## Book
- The `wasm-bindgen` Guide: https://rustwasm.github.io/wasm-bindgen/

## Examples
- wasm-by-example: https://github.com/torch2424/wasm-by-example

## Good read
- Rust And WebAssembly For the masses - Sharing Classes: https://sendilkumarn.com/blog/rustwasm-sharing-classes/
- Avoiding allocations in Rust to shrink Wasm modules: https://nickb.dev/blog/avoiding-allocations-in-rust-to-shrink-wasm-modules/
- Don't freak, but our Rust web server is now Node.js: https://nickb.dev/blog/dont-freak-but-our-rust-web-server-is-now-nodejs/
- Avoiding allocations in Rust to shrink Wasm modules: https://nickb.dev/blog/avoiding-allocations-in-rust-to-shrink-wasm-modules/
- OpenTally dev log: https://yingtongli.me/blog/tag/webassembly/
- wasmbin: a self-generating WebAssembly parser & serializer: https://rreverser.com/wasmbin-yet-another-webassembly-parser-serializer/
- Using asynchronous web APIs from WebAssembly: https://web.dev/asyncify/
- sendilkumarn: https://sendilkumarn.com/blog/tag/rust/

## Read more...
- https://github.com/mbasso/awesome-wasm
