### 非root安裝教學

```
wget https://raw.githubusercontent.com/McDull-GitHub/aria2c/master/aria2-1.35.0.tar.gz || curl -O https://raw.githubusercontent.com/McDull-GitHub/aria2c/master/aria2-1.35.0.tar.gz
```

```
cd ~ && madir .local
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
