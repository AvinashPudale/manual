## 1С: Сбой после обновления или изменений

{% include list.liquid all=true %}


### Хронология

|Дата заявки|Версия 1С|Суть конфликта
|:--- |:--- |:--- 
|2020-12-24|8.3.17.1851|[После обновления пустой экран](main-window-is-white)


graph TD
     A[Client] --> B[Load Balancer]
     B --> C[Server1]
     B --> D[Server2]
