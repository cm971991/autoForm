# autoForm
jquery 表单插件

## 使用方法
### 拼接表单参数
        `$('#form').autoSpliceForm()`
       
### 清空表单
        `$('#form').autoEmptyForm()`
          
### 表单赋值
        `$('#form').autoAssignmentForm()`
        
### 表单验证
        `$('#form').autoEmptyForm()`
        
        `<div id='form' data-autoVerify='true'>
            <input type='text' name='name'
                           data-expression='isNumber' data-error='XXX格式不正确'>
        </div>`
