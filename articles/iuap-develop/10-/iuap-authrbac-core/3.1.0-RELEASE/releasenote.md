##3.1.0-RELEASE##
优化权限控制逻辑和提供缓存，进一步提高性能。

##3.0.0-RELEASE##
**登录组件**

1.	提供统一的登录组件；
2.	身份、证明验证身份；
3.	支持多种身份标识，用户名、邮箱、手机号等；
4.	支持多个域，从域得到用户相应的角色/权限进行验证用户是否能进行操作（鉴权）；
5.	提供会话管理和安全管理；
6.	支持多种验证策略，并支持扩展

**权限框架**

1.	提供了用户、角色、功能、数据权限、用户角色关联，角色权限关联模型及维护Api。
2.	提供认证、授权、加密、会话管理、与Web集成、缓存等功能。
3.	权限结构基于RBAC模型，用户关联角色，角色关联功能。
4.	功能根据自定义策略可自行扩展；
5.	提供拦截器机制对权限进行控制；
6.	提供缓存机制，降低读消耗