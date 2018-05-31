# 前端常用代码总结

---------------
## 目录
>* [1.IE支持html5常用标签](#IE支持html5常用标签)
<!-- >* [2.webpack配置分析](#webpack配置分析)
>* [3.vue踩过的那些坑](#vue踩过的那些坑) -->

-----------------

## IE支持html5常用标签 
<a name="IE支持html5常用标签">

### js代码
```javascript\

(function(){if(!/*@cc_on!@*/0)return;var e ="abbr,article,aside,audio,canvas,datalist,details,dialog,eventsource,figure,footer,header,hgroup,mark,menu,meter,nav,output,progress,section,time,video".split(','),i=e.length;while(i--){document.createElement(e[i])}})()

```

### css代码
```css\

/*html5*/
article,aside,dialog,footer,header,section,footer,nav,figure,menu{display:block}

```
