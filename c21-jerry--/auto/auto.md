[system detailed map](https://git.page/jj/board?qname=jerry)

## auto structure

![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/e98241ead93b9bb9b5b7697a2a48b928326be578/auto_system_structure.png)


## auto microservice

![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/master/auto_microservice.png)


## smartscreen -auto-pd


![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/master/smart_auto_pd_structure.png)

## auto-flow
![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/master/auto_flow.png)

## pd-flow
![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/master/pd_flow.png)

## tips
* use ```onEvent``` node as the event trigger system design
* use ```>>ddn ```  in send node to do the object passing between the flows
* can use whois flow in jujue flow to get ddn after qrun
* object type should  be follow as  JSON object type
* ex:
* ```{"place":"jerry.nb","pd": "123", "in":{"from":"jerry.ss", "to" :"auto"},"name":"jerry"}```

![image](https://gitwork.ypcloud.com/clouder-21/c21-jerry--/raw/master/smartscreen.png)
