.基于jmeter的测试平台

1. 添加测试计划
  * 测试计划名称、压测地址url、测试说明、测试数据生成类

2. 执行测试计划，并保存结果  
  * 执行测试计划时，需要输入线程数和持续时间
  * 保存结果（测试计划id、线程数、持续时间、jtl保存路径、html保存路径）
  
3. 查看测试结果
  * 查询所有执行完毕的测试，查看html测试报告
  * 查询正在执行的测试，查看简单的jmeter聚合报告（命令行模式报告）
  
4. 测试数据生成类  
  采用插件的模式，对于新的生成类，实现接口，系统自动加载该类。

5. 上传jmx脚本  
  除了在平台中新建测试计划，也可以通过上传jmx脚本，然后执行。
  


        // TODO: wangc@2016/12/28  获取页面上的参数 

        // TODO: wangc@2016/12/28  运行生成测试数据的类 

        // TODO: wangc@2016/12/28  根据参数和模板生成jmeter脚本 
        
        // TODO: wangc@2016/12/28  运行jmeter脚本 

        // TODO: wangc@2016/12/28  实时显示测试结果（解析并显示jtl文件） 
                简单按行显示x.log文件中的关键内容   wangc@2017/03/14

        // TODO: wangc@2016/12/28  生成html报告 

        // TODO: wangc@2016/12/28  归档（jmeter脚本、测试数据、jtl测试结果、html报告） 

        // TODO: wangc@2017/03/14  选择一个或多个远程机器来执行jmx
        