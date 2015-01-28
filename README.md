# reviewcenter
Crowd-sourced review center for training programs


The OpenShift `nodejs` cartridge documentation can be found at:

http://openshift.github.io/documentation/oo_cartridge_guide.html#nodejs

##Day1
Follow the steps
https://developers.openshift.com/en/getting-started-windows.html#making-first-change
until 
* `C:\> rhc setup -l account`
replace account with the one given to you.
when prompted using hostname:  master.openshift.monevalue.com
with the provided credentials.
after login
* `rhc git-clone testnode --namespace rewardrefer`

##workflow from local
* edit the files
* git add `the file`
* git commit -m "your message"
* git push  //will update the product online.

##workflow from github
* edit files on github   
* git pull reviewcenter master  //run on local
* git push  //will update the product online.


##tutorial:
* http://git-scm.com/book/en/v2
* https://help.github.com/articles/markdown-basics/
* http://mgcrea.github.io/angular-strap/
* http://nqdeng.github.io/7-days-nodejs/ In Chinese; not suggested
* http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/ 
* https://github.com/airbnb/javascript  //learn javascript

##Team
- Tim(tim@rewardrefer.com)
- Lala
- Chris
- Anqi
- Tony
- Chao
- Enda
- Jing 
- Rabbit
- Conrad

##ToDo List:
1. articulate the idea of rating
良莠不齐的培训市场，需要一个统一的公正的点评系统来评估他们。
2. design the architecture
* front-end AngularJS, bootstrap
* backend nodejs
* mongodb
3. design the UX
4. workflow
