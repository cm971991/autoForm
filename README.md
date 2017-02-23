# autoForm
jquery 表单插件

## 使用方法

        
### 表单验证  
        ``` html
        $('#form').autoEmptyForm()
        
        <div id='form' data-autoVerify='true'>
            <input type='text' name='name'
                           data-expression='isNumber' data-error='XXX格式不正确'>
        </div>
        ```
