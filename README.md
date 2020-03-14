# Go-Storage

无盘网络存储系统

## 命令

### 服务器

启动监控服务，元数据存储在 `./data`

```bash
go-storage-server -listen 127.0.0.1:20214 -data "./data"
```

或者 （默认参数 `-listen 127.0.0.1:20214 -data "./data"` ) 

```bash
go-storage-server
```


### 客户端

#### 上传


```bash
go-storage-client -addr 127.0.0.1:20214 /path/to/file
```
或者 

```bash
go-storage-client /path/to/file
```


#### 下载

```bash
go-storage-client -addr 127.0.0.1:20214 -path "./download" 0d14a3da07c74efaee62f3ea495ce7de2e62c257
```

或者 

```bash
go-storage-client 0d14a3da07c74efaee62f3ea495ce7de2e62c257
```

## 接入存储云

- ali