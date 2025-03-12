# Usages
```
pony@ponydeMBP 1.0.0 % java -jar Artemis.jar -h
Usage: SAST [-hV] [-bc=<build_cmd>] [-d=<dbpath>] [-j=<java_home>]
            [-mr=<mr_enable>] [-od=<out_dbpath>] [-p=<path>] [-r=<rulePath>]
            [-t=<mr_target_path>]
static code analysis.
      -bc, --build-command=<build_cmd>
                            指定编译命令.
  -d, --database=<dbpath>   指定加载的数据库路径.
  -h, --help                Show this help message and exit.
  -j, --java-home=<java_home>
                            指定java_home路径.
      -mr, --mr-enable=<mr_enable>
                            是否启用mr扫描.
      -od, --output-database=<out_dbpath>
                            指定输出的编译数据库路径.
  -p, --path=<path>         指定源码路径.
  -r, --rule=<rulePath>     指定规则路径.
  -t, --mr-target-path=<mr_target_path>
                            指定target数据库路径.
  -V, --version             Print version information and exit.
```
# Detection capability
|漏洞名称|规则编号|漏洞等级|
| ---- | ---- | ---- |
|sql注入漏洞|dataflow-rule-sqli|高危|
|命令执行漏洞|dataflow-rule-cmdi|高危|
|反序列化漏洞|dataflow-rule-deserialize|高危|
|fastjson反序列化漏洞|dataflow-rule-fastjson-deserialize|高危|
|文件上传漏洞|dataflow-rule-fileupload|高危|
|路径枚举漏洞|dataflow-rule-pathmanipulation|高危|
|ql表达式注入漏洞|dataflow-rule-QlExpress|高危|
|SpEl表达式注入|dataflow-rule-SpEl|高危|
|服务端请求伪造|dataflow-rule-ssrf|高危|
|服务端模版注入漏洞|dataflow-rule-ssti|高危|
|重定向漏洞|dataflow-rule-redirect|中危|
|xml外部实体引用漏洞|dataflow-rule-xxe|高危|
|水平越权检测|ai-overstep-rule1|高危|
|垂直越权检测|ai-overstep-rule2|高危|

更多检测规则等你补充

# For more details
更多详情，建议访问我的博客：[pOny的技术博客地址](https://zsdlove.github.io/)
# Contact with me
![image](https://github.com/user-attachments/assets/e2031634-de32-4450-b7cb-4508eea36848)
