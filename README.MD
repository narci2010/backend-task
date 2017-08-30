# 拓胜科技后端工程师上机考试试题

## 以下试题根据自己的应聘职位的等级自行选择一个任务作答即可。
* 任务1：使用Springmvc+Mybatis的架构完成订单管理基本的CRUD功能。
    * 不会搭建环境的同学可以参考我们准备好的手脚架(项目jar包一定要使用maven管理)：https://github.com/narci2010/springmvc-mybatis
    * 下图是订单和订单项表结构（请忽略商品表）：
      <img src="task1.jpg"/>
    * 提交的源代码应该包含数据库脚本（含测试数据），且源代码应该是可以运行的。
 
          1. 实现订单项CRUD操作：Spring MVC RESTful API （初级）
             显示订单项ID为1的订单项信息：/orderitem/1
             显示全部订单项信息：/orderitems
             增加一条订单项：/orderitem/add
             修改一条订单项：/orderitem/modify
             删除订单项ID为1的订单项：/orderitem/del/1
             删除多条订单项记录：/orderitem/delany  
          2. 实现订单CRUD操作：Spring MVC RESTful API （中级）
             显示订单ID为1的订单信息：/order/1
             显示全部订单信息：/orders
             增加一条订单：/order/add
             修改一条订单：/order/modify
             删除订单ID为1的订单：/order/del/1 （删除订单会自动删除订单项）
             删除多条订单记录：/order/delany  （删除订单会自动删除订单项）
           3. 使用JQuery Ajax函数测试上述api （中级）
           4. 使用Spring提供的RestTemplate或HttpClient测试上述api （中级）
           5. 解决跨域访问问题 （中级）
           6. 给以上业务功能加上权限控制（至少有资源、角色和用户三张表实现），
           业务功能的权限能够灵活配置（可以采用shiro或Spring Security实现）（高级）
           7. 配置CAS登录问题 （高级）
           8. 对spring mvc设计统一的异常处理机制（中级）。          
* 任务2：使用Spring Boot+Spring Data JPA架构完成任务1相同的功能。
* 任务3：使用Spring MVC+Spring Data JPA架构完成任务1相同的功能。


------
（说明：应聘初级工程师，只需要完成初级题目；中级工程师必须完成初、中级题目；高级工程师必须完成初、中、高题目）
         
