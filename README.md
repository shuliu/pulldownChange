pulldownChange
==============

下拉選單連動套件

todo：
 ```html
<select id="city" name="city" ></select>
<select id="town" name="town" ></select>
<input type="text" id="zip" name="zip" placeholder="zip" readonly maxlength="4" tabindex="-1" />
```
```javascript
$(function(){
  $('.userdata').pulldownChange('city','town','zip',twData,true,'please select');
});
```

API
===
6項參數
參數 | 作用 | 必填
--- | --- | ---
from | 控制起始欄位 | true
to | 控制連棟欄位 | true
zip | zip欄位 | **false**
data | 連動資料`json` | true
format | 若為*true*則可進行from欄位的format | **false**
defName | 預設文字，部輸入則為 "請選擇" | **false**

