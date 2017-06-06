# scvcs : concurrent versioning and cats for strings
Strings sharing and versionning

Strings management:  
* New piece : Value/Key  
POST /piece/create  
string value  
(optional) string key  
* Last string value of a piece  
GET /piece/last/[id]  
* History of a piece  
GET /piece/history/[id]  

