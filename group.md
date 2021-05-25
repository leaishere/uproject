

# 用户组

用户组将职责相似或权限相同的子用户归为一类，统一授权，从而为了更高效得管理IAM子用户。

- 当整个用户组的职能范围变化，只需修改组的授权；
- 当个别用户的权限范围发生变化，e.g. 转岗、新成员加入，只需将其移出/移入用户组；

![](/images/group_mainpage.png)

### 创建用户组

“用户组名称”代表该用户组在这个云服务账号下的唯一标识，不可重复。
![](/images/create_group.png)

### 为用户组授权

该用户组在默认项目下用户超级管理员权限，即允许访问所有资源。
财务权限、IAM权限为全局策略，不受项目限制。
![](/images/project_policy_group.png)
![](/images/global_policy_group.png)

### 为用户组添加成员

选择子用户加入用户组，子用户将自动继承用户组权限。
![](/images/add_group_user.png)

### 删除用户组

删除用户组将自动移除组内所有成员。
![](/images/delete_group.png)