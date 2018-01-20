#1.网页中的盒模型(Box Model)分为:
    标准盒模型
    怪异/混杂盒模型

#2.标准盒模型：
    width = content ;
    offsetWidth =  content + padding + border ;

#3.怪异/混杂盒模型：
    width = content + padding + border ;

#4.转化：
    box-sizing: border-box ;

#5.删掉<!DOCUMENT html>在IE6下会开启怪异模式/混杂模式
  怪异模式指的不是IE6,而是IE6之前的版本。