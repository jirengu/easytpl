# easyTpl

easyTpl, a simple JavaScript template.

## install

1. Node environment
    
    npm install -g easytpl

2. Client environment
    
    bower install easytpl
    
## useage

```javascript

    var easyTpl = require('easyTpl');
    var tpl = 'hello my name is {{name}}. I have a {{dog.age}} year old dog. His color is {{dog.color}}.';

    var data = {
        name: 'hunger',
        dog: {
            color: 'yellow',
            age: 2
        }
    };

    var str = easyTpl(tpl, data);
    console.log(str);
```
more demos in sample folder.

## test

```bash
    make test
```

## auther

ruoyu@jirengu.com