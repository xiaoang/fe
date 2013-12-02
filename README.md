fe
==

the web front develop
/*
*肖昂收集整理
*功能说明：
*基于jquery库的一款form input验证
*需引入jquery库和validate插件js， 已在html页面中引入了奇虎360的静床版本
*引用方式$(*).validate();
*$(*).validate({submitHandel:function(){}}); 
*参数可参考： http://www.open-open.com/doc/view/2fb99c596a7c471c83490dc9c10c2b16
*验证规则通过input标签的class类名引入，如：class="required"表示该字段必填字段，class="email"表示以email规则校验该输入字段
*验证提示语，通过设置input标签的title属性来实现。 若不设置，按照插件内置提示语
*/
