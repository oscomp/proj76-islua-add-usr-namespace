# proj76-islua-add-usr-namespace

为iSulad 创建容器命令增加User namespace的能力

### *描述* 

当前iSulad默认没有隔离宿主机用户和容器中的用户，要求通过客户端isula配置—setns接口参数isula来隔离容器中的用户

### 所属赛道

2021全国大学生操作系统比赛的“OS功能设计”赛道



### 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2021年春季学期或之后本科毕业的大一~大四的学生）
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
- 请遵循“2021全国大学生操作系统比赛”的章程和技术方案要求

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
