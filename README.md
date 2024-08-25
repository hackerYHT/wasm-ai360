# wasm-ai360
higress对接360智脑插件开发

higress tinygo 打包命令：
```shell
tinygo build -o main.wasm -scheduler=none -target=wasi -gc=custom -tags='custommalloc nottinygc_finalizer proxy_wasm_version_0_2_100' ./main.go
rm -rf /Users/xiehaitao/GolandProjects/wasm-ai360/main.wasm &&  mv ./main.wasm /Users/xiehaitao/GolandProjects/wasm-ai360                 
```
