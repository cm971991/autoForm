# autoForm
jquery 表单插件

## 使用方法
### 拼接表单参数
        `$('#form1').autoSpliceForm()`
       
### 清空表单
        `$('#form1').autoEmptyForm()`
          
### 表单赋值
        `$('#form1').autoAssignmentForm()`
        
### 表单验证
        `$('#form1').autoEmptyForm()
        
        <div id='form1' data-autoVerify='true'>
            <input class='form-control' type='text' name='accessNumber'
                           data-expression='isNumber' data-error='XXX格式不正确'>
        </div>`
