A python script for my media convergence curriculum
The script is all about data cleaning with specific requirements given by teacher.

===ABOUT VERSION===
Current version: 1.0

Version 1.0
Meet the requirements of following:

1, empty message, delete the entire line: len(news) < 50 
2.error format information, such as only layout or edit information, etc., will often be several lines linked together are wrong format confidence, delete the entire line together to delete a) < 50 
3.advertising information, can be deleted directly: keywords: company product name?  
4.non-Hangzhou news content, Beijing News, Nanjing News can be deleted directly, points out Huzhou, Wenzhou and other addresses of the general situation can be directly removed: keywords: national city name. 
5. keep Hangzhou information, most news will point out "Hangzhou somewhere" is relatively easy to identify, some news may directly mention the specific address of Hangzhou, such as Wentao Road, Wulin Square, and so on, everyone pay attention to: keywordsHangzhou, Hangzhou place names.  
6. Regular reports such as routine weather forecast, train number information, food price broadcast and so on can be deleted: keywords: temperature, rain, wind 
7.this work only need to eliminate non-Hangzhou information, keep Hangzhou news, do not need to identify the specific address, do not need to mark other work.