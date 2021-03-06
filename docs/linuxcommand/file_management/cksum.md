# cksum 命令
***用来输出每个文件的CRC校验值和字节统计***

**补充说明**
**cksum命令**是检查文件CRC是否正确，确保文件从另一个系统出传输到另一个系统中不被破坏。这种方法用于校检和在源系统中被计算出来，在目的系统中又被计算一次，两个数字进行比较，如果校检值相等，则该文件被认为是正确传输。

### 语法
```bash
cksum [文件]...
cksum [选项]
```

### 选项
```
--help		在线帮助
--version	显示版本信息
```

### 参数
```
文件：指定要计算校检的版本信息
```

### 实例
1> 使用cksum命令计算文件"testfile1"的完整性，输入如下命令
```bash
cksum testfile1
```
#### 返回结果
```
[检验码]...[字节数]...[文件名]
```
