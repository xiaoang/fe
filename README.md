fe
==

the web front develop
/*
*肖昂收集整理<br/>
*功能说明：<br/>
*基于jquery库的一款form input验证<br/>
*需引入jquery库和validate插件js， 已在html页面中引入了奇虎360的静床版本<br/>
*引用方式 $(dom).validate(); 或者 $(dom).validate({submitHandler:function(){}}); {}内容为参数配置。<br/>
*参数可参考： http://www.open-open.com/doc/view/2fb99c596a7c471c83490dc9c10c2b16<br/>
*验证规则通过input标签的class类名引入，如：class="required"表示该字段必填字段，class="email"表示以email规则校验该输入段<br/>
*验证提示语，通过设置input标签的title属性来实现。 若不设置，按照插件内置提示语<br/>
*更多校验规则参考demo
*/
