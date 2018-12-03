# 1.3 日常规定

update 2017-08-11 18:42:43

## 沟通

1. 每个月进行一次户外活动或聚会
2. 团队内部交流和协作场景需使用规范花名
3. 每个月7号进行一次问卷调查或笔试测验
4. 公用代码增删改需要告知到大家
5. 在有思路上的疑问情况下主动发起话题或探讨
6. 每周（6或1）最多进行一次调度协调会议
7. 任务下达之前应与执行同事确定完成时间
8. 消极态度和意识早发现早排除
9. 每周六做技术分享一次，课题不限（尽量互联网技术周边），主讲次序按照部门成员次序。

## 协作

1. 正常上班时间未批准到请假的情况下不迟到、不早退
2. 如发现旷工、调休未按约定正式上班情况，每半个工作日处以1/20的月薪扣除作为警示
3. 在做的工作应必须在今目标任务中存在且完成时间明确
4. 当日有未完成的拖延任务时应在当日日志里说明
5. 任务参与人应有部门所有成员+侯总+李经理+崔经理+杨经理
6. git上协作开发需要自建临时性分支命名规范：功能开发（feature\_xxx,f\_xxx）,预发布（release\_xxx,r\_xxx）,bug修复（bug\_xxx）
7. GIT上该有的操作说明介绍一定要写到位，方便自己和别人快速查阅
8. 每个工作日下班必备两件事 记录日志、push代码
9. 每周五下午合并一次代码到develop
10. 每周六发布一版开发版本、编制本周计划完成总结、编制下周计划
11. 周六本周总结一项一行列好，动作位置清晰一目了然，枚举前缀“完成-、新增-、优化-、修复-、清除-”，如：修复-手机Web个人主页列表不能继续加载的bug
12. 每周上传更新公告首先发布到客服群里，公告更新时间和更新的项，更新的项可参考合并分支时的说明介绍，范：

    ```text
    公告：滨州网于2017年7月15日周六下午6点更新升级：
    1. 修复-XXXXXXX.
    2. 新增-XXXXXXXXXXXX.
    3. 优化-XXXXXXXXXX.
    4. ... ...
    ```

13. 重视起线上协作如今目标、coding.net、群
14. 任务时间确定时可以预留出优化时间但不应后期拖延
15. 请假申请应直接向侯总请假
16. 主管/代理主管根据季度满意度问卷调查规范实行民主制，支持率最高当选和上季支持率最高交接，实在无能力担任可以让给上届或支持率第二位
17. 部门内部不允许有家属、情侣、恋爱等对部门产生潜在影响的连带关系
18. 新建分支时无需都将源分支设为develop，除非你的这个开发是独立的。按照树形主从选择源分支。
    * 比如 A负责的领域基于团队的计划 那源分支应选develop，开发完成也应合并到develop。
    * 比如 B负责的是A负责的下面的领域，那新开发分支源分支应选A的分支，开发完成合并也应合并到A的分支，而不是develop。
    * 比如 C负责的是B负责的下面的领域，那B新建开发分支的源分支应选的是B的分支，开发完成应合并回源分支，而不是develop。
19. 新建分支后最好通知 @归海 设置分支保护，别人除了合并请求到你的分支之外是无法干扰到你的开发的。
20. 上班时间PC今目标要登录
21. 上班时间玩游戏看娱乐视频对公司影响较大强制执行警告 或 考虑劝退部门
22. 同事之间应互相尊重，上班期间不得嬉戏打闹
