# ZJGSUAAO_js

* 用于教务网学生评价
* console控制

* 源码如下
```
var SelectionOfALl = document.getElementsByClassName("radio-pjf");
var num =  SelectionOfALl.length;
for(var i = 0; i < num; i++)//此处默认五星好评，若修改请修改i的值
{
    if(i % 5 == 0){
        var Select = SelectionOfALl[i];
        Select.checked = true;
    }
}

var button1 = document.getElementById("btn_xspj_bc");//寻找保存按钮的Id来触发事件
button1.click();
```
