# aliDDns

 python3+ali云解析 实现动态域名解析

## main.py 更新解析记录

* domain：要更新记录的域名

* accessKeyId：阿里云id

* accessSecret：阿里云secret

## DDns.py

1. save_records( )

* 获取解析记录并保存为json文件

2. update_record( )

* 更新解析记录

## Utils.py 工具类

### 方法

1. get_records( )

* 调用DescribeDomainRecords( )  接口获取解析记录

2. get_recordinfo( )

* 调用DescribeDomainRecordInfoRequest( )  接口获取记录信息

3. update_record( )

* 调用UpdateDomainRecordRequest( )  接口更新解析记录

### 阿里云解析DNS解析管理API

1. DescribeDomainRecords( )

* 调用DescribeDomainRecords根据传入参数获取指定主域名的所有解析记录列表。

2. DescribeDomainRecordInfoRequest( )

* 调用DescribeDomainRecordInfo获取解析记录的详细信息。

3. UpdateDomainRecordRequest( )

* 调用UpdateDomainRecord根据传入参数修改解析记录。
