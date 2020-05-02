## DP后台管理系统
- 路由
  模块路由 admin.jsx 易懂但多引入一层
- 前台表单验证
  from功能强大 验证  有效数据 
  from.create方法返回函数 返回了新的组件
  1. 高阶函数
    1). 一类特别的函数
        a. 接受函数类型的参数
        b. 返回值是函数
    2). 常见
        a. 定时器: setTimeout()/setInterval()
        b. Promise: Promise(() => {}) then(value => {}, reason => {})
        c. 数组遍历相关的方法: forEach()/filter()/map()/reduce()/find()/findIndex()
        d. 函数对象的bind()
        e. Form.create()() / getFieldDecorator()()
    3). 高阶函数更新动态, 更加具有扩展性
  包装form组件 生成一个新的组件form(login)
  新的组件会问form
  得到具有强大功能的form对象
  getfiledecorator高阶函数有两个属性 标识名称 验证规则
  const form = this.props.from 得到form对象
2. 高阶组件
    1). 本质就是一个函数
    2). 接收一个组件(被包装组件), 返回一个新的组件(包装组件), 包装组件会向被包装组件传入特定属性
    3). 作用: 扩展组件的功能
    4). 高阶组件也是高阶函数: 接收一个组件函数, 返回是一个新的组件函数

- 项目准备
    描述项目
    技术选型
    API接口/接口文档。测试接口
- 启动项目开发
- 仓库学习
- 创建项目的基本结构
  api
  component:非路由组件
  pages:路由组件
  app.js
  index.js
- 引入antd
  下载
  按需打包
    下载工具包
    config-oberrides
    package改变命令
  自定义主题
  使用antd组件
- 引入路由
  下载包
  拆分应用路由
  映射路由
- login的静态组件
- 收集表单数据验证
  form对象：高阶组件包装得到form属性 
    操作表单数据：form操作 getfiledecrator innitialvalue初始值
  前台表单验证
    声明式实时验证
    自定义验证
    点击提示验证
- 高阶函数高阶组件
- 前台展现数据
- 后台获取数据
  接口文档