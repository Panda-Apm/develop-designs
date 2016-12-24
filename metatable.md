| 字段名称           | 类型           |   描述   |
| ------------------|---------------|-----------|
| base              | Node          |           |
| base.lang         | Node          |           |
| base.lang.version | String        | 语言版本  |
| base.protocol     | Node          |           |
| base.protocol.version | Long      | 协议版本  |
| server            | Node          |           |
| server.run_mode   | String        | 运行模式|
| server.ip         | String        | 服务端Ip   |
| script            | Node          |          |
| script.name       | String        | 运行脚本名称 |
| script.params     | Array         | 运行参数    |
| request           | Node          |            |
| request.uri       | String        | 请求URI    |
| request.method    | String        | 请求方法    |
| request.ip        | String        | 请求Ip     |
| request.cookie    | Array         | 是否抓取COOKIE|
| request.post      | Array         | 是否抓去POST|
| response          | Node          |           |
| response.type     | String        | 响应数据类型|
| response.status   | String        | 响应状态码  |
| response.length   | Long          | 响应数据长度 |
| error             | Node
| error.type        | String        | 错误类型    |
| error.line        | Long          | 错误行号    |
| error.file        | String        | 错误文件    |
| error.message     | String        | 错误详情    |
| exceptions        | Node          |            |
| exceptions.$num   | Array         |            |
| exceptions.$num.type  | Long      | 异常类型    |
| exceptions.$num.line  | Long      | 异常行号    |
| exceptions.$num.code  | Long      | 异常错误码  |
| exceptions.$num.file  | Long      | 异常错误信息 |
| exceptions.$num.message | string  | 异常详情     |
| performance       | Node          | 性能数据   |
| preformance.statistics | Array    | 性能统计   |
| preformance.statistics.nested_depth | Long | 最大嵌套深度|
| preformance.statistics.method_execution | Long | 方法总运行个数|
| preformance.statistics.runtime | Long  |总运行时间
| preformance.statistics.memory_usage |  Long | 总内存调用
| preformance.statistics.compiled_files | Long | 总编译文件个数|
| preformance.statistics.compiled_files_time | Long| 编译文件总运行时间|
| preformance.statistics.gc_runs| Long | gc 回收总运行次数|
| preformance.statistics.gc_collected| Long | gc 回收总收集次数|
| stacks           | Node           |        |
| stacks.$num      | Array          | 堆栈数据 |
| stacks.$num.id   | Long           | 节点ID  |
| stacks.$num.start_time| Long      | 开始时间 |
| stacks.$num.end_time  | Long      | 结束时间 |
| stacks.$num.call_time | Long      | 调用时间 |
| stacks.$num.method_name | String  | 方法名称 |
| stacks.$num.memory_usage| Long    | 内存占用 |
| stacks.$num.params| Array         | 参数数据 |
| stacks.$num.params_count | Long   | 参数总数 |
| stacks.$num.resource_id  | Long   | 资源实例 |
| resources        | Node           |          |
| resources.$num   | Array          | 资源数据  |
| resources.$num.module_name | String |资源模块名称|
| resources.$num.host  | String     | 资源主机地址|
| resources.$num.port  | Long       | 资源端口   |
| extends          | Node           | 扩展数据   |
| extends.user     | Array          | 扩展用户数据 |
| extends.end_to_end | Array        | 扩展端到端数据 |



