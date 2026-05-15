## 编译：  
先运行 

```cmd
cmake -G Ninja -B build -DCMAKE_BUILD_TYPE=Release -DCMAKE_C_COMPILER=clang -DCMAKE_CXX_COMPILER=clang++
```

然后再运行
```cmd
cmake --build build

```
或者这个
```cmd
cmake --build build --config Release
```

使用
```
.\dx11_tex_dbg.exe -t YuanShen.exe -s 512
```