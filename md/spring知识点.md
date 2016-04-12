# spring知识点 #
- ## spring transaction 自定义异常不回滚 ##
> spring aop  异常捕获原理：被拦截的方法需显式抛出异常，并不能经任何处理，这样aop代理才能捕获到方法的异常，才能进行回滚，
> 默认情况下aop只捕获runtimeexception的异常