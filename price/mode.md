# 计费模式


1. 号码认证采用预付费模式，即购买资源包进行次数抵扣计费。  

   
 
2. 根据认证次数实时扣费，其中调用初始化接口不计费。   
- 调用一键登录的取号接口时，如果能够成功返回号码，会对本次认证计费;如果无法返回号码，则不计费；  
- 调用本机认证接口时，如果认证结果是一致、不一致，会对本次认证计费；如果认证结果是无法判断，则不计费。 

3.每月单应用保底次数为4000次，若不足最低消费次数，次月4日系统将自动扣除需补足的剩余次数。为了保证您的业务正常运行，请及时购买资源包。



