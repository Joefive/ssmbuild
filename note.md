###配置mysql没有设置时区问题
show variables like'%time_zone';  
如果显示SYSTEM则没有设置时区
set global time_zone = '+8:00'; 
然后设置时区为东八区