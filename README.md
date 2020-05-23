### 非root安裝教學

```
cd ~ && mkdir .local
```

```
wget https://raw.githubusercontent.com/McDull-GitHub/aria2c/master/aria2-1.35.0.tar.gz || curl -O https://raw.githubusercontent.com/McDull-GitHub/aria2c/master/aria2-1.35.0.tar.gz
```

```
tar -zvxf aria2-1.35.0.tar.gz
```

```
cd aria2-1.35.0
```

```
./configure --prefix=$HOME/.local/
```

```
make
```

```
make install
```

### 使用方法
```
aria2c --enable-rpc=true --rpc-allow-origin-all=true --rpc-listen-all=true
```
