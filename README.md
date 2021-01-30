# proj76-islua-add-usr-namespace

为iSulad 创建容器命令增加User namespace的能力

### *描述* 

当前iSulad默认没有隔离宿主机用户和容器中的用户，要求通过客户端isula配置—setns接口参数isula来隔离容器中的用户

### *难度* 

中

### *导师* 

@jingwoo

*联系方式* [wujing50@huawei.com](mailto:wujing50@huawei.com)

### License

- MulanPSL v2

### *项目产出标准*

- 完成客户端iSula及服务端iSulad相应代码的编写（客服端实现参数的透传，服务端实现参数的校验，并从主机/etc/subuid和/etc/subgid中获取相应的配置信息转发置lcr） 

### *技术要求*

1. 熟悉c语言的使用
2. 了解 Linux user     namespace

### *相关项目*

1. https://gitee.com/openeuler/iSulad

### *相关资料*

1. http://man7.org/linux/man-pages/man7/user_namespaces.7.html
2. https://docs.docker.com/engine/security/userns-remap/
