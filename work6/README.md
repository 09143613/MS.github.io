 ###用户test1可以查看的页面（Sys_menu）
![test1](test1操作.png)
###结果
![test1](text1结果.png)
###伪代码:
1、根据名称查找人员编号UserID

2、根据人员编号UserID查找改人员所对应的角色集合RoleIDs

3、 在权限表中查询 While表为Role，权限类别为Menu，PrivilegeMasterKey为RoleID，权限为Permit的数据
###订单(order)页面中的操作权限(sys_button）
![order](order操作.png)
###结果
![order](order结果.png)
###伪代码:
1、根据名称查找人员编号UserID

2、根据人员编号UserID查找改人员所对应的角色集合RoleIDs

3、权限表、页面表、按钮表做连接 


