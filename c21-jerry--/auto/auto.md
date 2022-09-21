[system detailed map](https://git.page/jj/board?qname=jerry)

## auto structure

![image]([https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/smart_auto_pd_structure.png](https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/auto_system_structure.png))


## auto microservice

![image](https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/auto_microservice.png)


## smartscreen -auto-pd


![image](https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/smart_auto_pd_structure.png)

## auto-flow
![image](https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/auto_flow.png)

## pd-flow
![image](https://github.com/chen88088/firstshot/blob/main/c21-jerry--/auto/picture/pd_flow.png)

## tips
* use ```onEvent``` node as the event trigger system design
* use ```>>ddn ```  in send node to do the object passing between the flows
* can use whois flow in jujue flow to get ddn after qrun
* object type should  be follow as  JSON object type
* ex:
* ```{"place":"jerry.nb","pd": "123", "in":{"from":"jerry.ss", "to" :"auto"},"name":"jerry"}```

