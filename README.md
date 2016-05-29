# mxt-command-webfont

## 使用

`mxt webfont`

## 设置

```js
fis.set('webfont',{
    src       : '/src/icon',// 图标目录
    dest      : '/dist/font',  // 产出字体目录
    fontname  : 'myfont', // 产出字体名称
    destCss   : '/dist/css', // 产出的css目录
    destHtml  : '/dist/html', // 产出的html文件目录
    template  : '/src/icon/templates/template.css', // 模板css
    htmlDemoTemplate: '/src/icon/templates/template.html' // 模板html文件
});
```