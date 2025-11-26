# PostgreSQL-install-PGvector
# 将本项目下的文件拷贝到PostgreSQL安装目录下
## 插件运行文件 文件夹：1
核心作用：提供向量类型、索引、相似度计算的核心实现

拷贝目标路径（以下为我的PostgreSQL安装路径）：
``` shell
F:\PostgreSQL_18\lib\
```
## 扩展脚本 文件夹：2
核心作用：插件安装、版本升级的脚本依赖，PostgreSQL 识别插件的关键

拷贝目标路径：
``` shell
F:\PostgreSQL_18\share\extension
```

# 启动PostgreSQL的psql命令行工具
执行以下SQL命令：
``` sql
-- 创建vector扩展
CREATE EXTENSION vector;
```