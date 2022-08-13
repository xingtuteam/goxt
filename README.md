# goxt
星图节点源码

####  1.下载节点文件

#### 2. 拷贝到全局目录

```shell
 cp ./goxt  /usr/bin/
 goxt -v
```

#### 3. 创建存储节点数据目录

```
mkdir data 
```

3.1初始化目录

```
goxt init ./genesis.json --datadir "./data"
```

3.2 启动节点

```
goxt --snapshot=false --datadir './data'  
 --syncmode "full" 全节点同步
```

