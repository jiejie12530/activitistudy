以前用的都是activiti5,做了一段时间管理后,有段时间没有写代码了,后来有天配activiti时想用新版,发现有不少的改动,此外也遇到了一些坑,  
这里写个教程记录一下,也降低后面使用的人的门槛  
study1是原始的配置,未修改项目名,注意将java加入project structure中resources,resources加入resources,至此启动  
Study1Application即可启动项目,访问http://127.0.0.1:8888/activiti/create即可进入activiti流程图的新建页面    
study2修改项目名为act,这里除了要修改application.properties中,还要修改app-cfg.js中'contextRoot': '/service'  
为'contextRoot': '/act/service',至此访问地址变为http://127.0.0.1:8888/act/activiti/create