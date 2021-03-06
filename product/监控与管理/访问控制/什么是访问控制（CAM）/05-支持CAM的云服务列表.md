支持CAM的云服务列表如下：

| 服务  | 业务权限  | 策略语法 | 云API |控制台  |授权粒度 | 条件 |临时证书|
|---------|---------|---------|---------|---------|
| CDN|支持 | 不支持 | 	支持 |支持 |  操作级 | 不支持 |不支持 |
| 消息队列 CMQ |支持|支持|支持|支持|资源级|不支持|不支持 |
| 密钥管理服务 KMS |支持|支持|支持|支持|资源级|不支持|不支持 |
| 互动直播|支持 | 支持 | 不支持 |支持 |  服务级 | 不支持 |不支持 |
| 云点播|  支持 | 支持 | 不支持 | 支持 | 服务级 | 不支持 |不支持 |
| 云直播|支持 | 支持 | 不支持 |支持  | 服务级 | 不支持 |不支持 |
| 短信|支持|支持 | 不支持 |支持 | 服务级 | 不支持 |不支持 |
| 对象存储 COS |不支持 | 支持 | 支持 |不支持 | 资源级 | 部分支持 |支持 |
| 归档存储 CAS |不支持| 支持 | 支持  | 支持  |资源级 | 部分支持 |支持 |
| 云监控 CM |不支持| 支持 | 支持  |支持| 资源级 | 部分支持 |不支持 |
| 密钥管理服务 KMS |不支持| 支持 | 支持  |支持| 资源级 | 不支持 |不支持 |
| 私有网络 VPC (灰度) |不支持|  支持 | 支持  | 支持 | 资源级 | 部分支持 |不支持 |
| 存储网关 CSG (灰度)|不支持| 支持 | 支持 | 支持  | 资源级 |不支持 |支持 |
| 云数据库 CDB (灰度)|不支持| 支持 | 支持  | 不支持  | 资源级 | 不支持 |不支持 |
| 数据传输 DTS (灰度)|不支持| 支持 | 支持  |不支持| 资源级 | 不支持 |不支持 |
| 负载均衡 CLB (灰度)|不支持| 支持 | 支持  |支持| 资源级 | 部分支持 |不支持 |
| 云服务器 CVM (灰度)|不支持| 支持 | 支持  |支持| 资源级 | 部分支持 |不支持 |
| 安全组 DFW (灰度)|不支持| 支持 | 支持  |支持| 资源级 | 部分支持 |不支持 |
| 云硬盘 CBS (灰度)|不支持| 支持 | 支持  |支持| 资源级 | 部分支持 |不支持 |

说明：
1. ***业务权限*** 是指按业务权限方式创建策略，***策略语法*** 是指按策略语法方式创建策略。

2. ***云 API*** 是指云 API 是否接入了 CAM ，***控制台*** 是指控制台是否接入了 CAM 。 

3. 授权粒度按照粒度粗细分为服务级、操作级和资源级三个级别。服务级粒度下仅支持定义某个服务是否拥有访问权限；操作级粒度下支持某个服务下的某个操作是否拥有访问权限；资源级粒度下支持针对某个资源是否拥有访问权限，是最细粒度的授权。

4. 条件语法仅在部分业务支持。已支持条件的业务的条件列表请参考具体的业务文档说明。

5. 临时证书目前仅对象存储 COS 和归档存储 CAS 支持。

6. 对象存储 COS 仅支持 xml 协议的 API 接口；私有网络 VPC 等云服务均在灰度期，具体信息请参考业务文档说明。

