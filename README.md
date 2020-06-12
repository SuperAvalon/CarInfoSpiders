### CarInfoSpiders

### 项目简介
 * 框架   Python Spider
 * DB     MySQL
 * 项目需求：全量爬取汽车资料数据库，将其数据库数据解析之后存入db，构建汽车门户网站关键数据库。
 
### 执行流程
 * 1、定义数据字典，attributes.ini文件；
 * 2、爬取各级别（a、b、c、d、suv、mpv、a0、a00）所有车型数据，已经保存车型option页url，为下一步爬取做准备；
 * 3、爬取具体车型的option数据，并解析，存入db；
 
 
