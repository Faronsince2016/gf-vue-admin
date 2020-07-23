gf-vue-admin

- [x] gf-vue-admin服务端
    - [x] 基于[gin-vue-admin](https://github.com/flipped-aurora/gin-vue-admin)的server与[goframe](https://goframe.org/start/index)的官方推荐架构
    - [x] 架构具体看文档
    - [x] 路由层
    - [x] jwt鉴权
    - [ ] casbin鉴权
    
## Api开发计划
- [x] jwt黑名单
    - [x] jwt加入黑名单
- [x] 管理员用户模块
    - [x] 管理员登录
    - [x] 管理员注册
    - [x] 验证码获取
    - [x] JWT刷新
- [x] 基础功模块
- [ ] menu模块
    - [x] 获取用户动态路由
    - [ ] 分页获取基础menu列表
    - [ ] 新增菜单
    - [ ] 获取用户动态路由
    - [ ] 获取用户动态基础路由
    - [ ] 增加menu和角色关联关系
    - [ ] 获取指定角色menu
    - [ ] 删除菜单
    - [ ] 更新菜单
    - [ ] 根据id获取菜单
- [ ] 角色管理模块
    - [x] 创建角色
    - [x] 删除角色
    - [x] 更新角色
    - [ ] 复制角色
    - [x] 获取角色列表
    - [ ] 设置角色资源权限
- [x] 功能api模块
    - [x] 创建api
    - [x] 删除指定api
    - [x] 更新基础api
    - [x] 根据id获取api
    - [x] 获取所有的Api 不分页
    - [x] 分页获取API列表
- [x] 文件上传下载功能模块
    - [x] 上传文件示例
    - [x] 删除文件
    - [x] 分页文件列表
- [ ] 文件断点续传功能模块
    - [ ] 断点续传到服务器
    - [ ] 查找文件
    - [ ] 删除切片
- [ ] 工作流
    - [ ] 注册工作流
- [ ] casbin权限模块
    - [ ] 更改角色api权限
    - [ ] 获取权限列表
    - [ ] RESTFUL测试路由
- [ ] system模块
    - [ ] 获取配置文件内容
    - [ ] 设置配置文件内容
    - [ ] 重启服务器
- [ ] 客户模块
    - [ ] 创建客户
    - [ ] 删除客户
    - [ ] 更新客户信息
    - [ ] 获取权限客户列表
- [ ] 自动化代码模块
    - [ ] 自动代码模板
- [x] 字典详情管理模块
    - [x] 创建DictionaryDetail
    - [x] 删除DictionaryDetail
    - [x] 用id查询DictionaryDetail
    - [x] 分页获取DictionaryDetail列表
- [x] 字典管理模块
    - [x] 创建Dictionary
    - [x] 删除Dictionary
    - [x] 更新Dictionary
    - [x] 用id查询Dictionary
    - [x] 分页获取Dictionary列表
- [x] 操作历史模块
    - [x] 创建Operation
    - [x] 删除Operation
    - [x] 更新Operation
    - [x] 批量删除Operation
    - [x] 用id查询Operation
    - [x] 分页获取Operation列表
- [ ] 角色模块
    - [x] 创建角色
    - [x] 删除角色
    - [x] 更新角色
    - [ ] 复制角色
    - [x] 获取角色列表
    - [ ] 设置角色资源权限

## 测试api
- [x] 基础功模块
    - [x] 管理员登录
    - [x] 管理员注册
    - [x] 验证码获取
    - [ ] JWT刷新
- [ ] 管理员用户模块    
    - [x] 管理员修改密码    
    - [x] 分页获取管理员列表    
    - [x] 设置用户权限    
    - [ ] 删除用户(ID接收问题)
- [ ] 角色模块
    - [ ] 创建角色
    - [ ] 删除角色
    - [ ] 更新角色
    - [ ] 复制角色
    - [ ] 获取角色列表
    - [ ] 设置角色资源权限
  
## TODO
- [ ] 用户多角色
- [ ] 自写api批量导入权限分配列表
- [ ] 生成文件自动导入