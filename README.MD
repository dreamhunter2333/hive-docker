# hive docker 环境配置

使用 docker 搭建 hadoop 环境

```bash
# 构建镜像
docker build -t registry.cn-beijing.aliyuncs.com/dreamhunter/hive-docker:1.0 .
# 启动
docker-compose up
```

## conf

`etc/hadoop` 下的一些配置文件

```bash
conf
├── core-site.xml
├── hadoop-env.sh
├── hdfs-site.xml
├── mapred-site.xml
├── workers
└── yarn-site.xml
```

## hive-conf

`hive/conf` 下的一些配置文件

hive-conf
├── hive-env.sh
└── hive-site.xml

## hadoop-bin

hadoop-bin 存放 [hadoop release 文件](https://mirrors.tuna.tsinghua.edu.cn/apache/hadoop/common/hadoop-3.3.1/hadoop-3.3.1.tar.gz)

## hadoop-bin

hive 存放 [hive release 文件](https://mirror-hk.koddos.net/apache/hive/hive-3.1.2/apache-hive-3.1.2-bin.tar.gz)
