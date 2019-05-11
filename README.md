# passport
单点登录相关的代码

# 技术栈
swagger 快速生成文档
wireMock 快速伪造restfull服务

# 依赖管理
passport
    -passport-app 手机端登录拦截  
    -passport-browser 浏览器登录拦截  
    -passport-core 核心安全包  
    -passport-demo 样例使用  
    -passport-test 安全登录项目
    -passport-oauth 基于oauth2的测试
# 配置相关控制
 --------------------------
 顺序依次如下  
     -----filter----对请求URL的过滤     
     -----interceptor----对请求方法调用的处理   
     -----ControllerAdvice----对控制层的监控  
     -----Aspect----对接口的切面  
     -----Controller----控制层实现  
     -----代码执行------具体代码执行
