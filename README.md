pulldownChange
==============

下拉選單連動套件

example：
 ```html
<select id="city" name="city" class="control-group" ></select>
<select id="town" name="town" class="control-group" ></select>
<input type="text" id="zip" name="zip" placeholder="zip" class="control-group" readonly maxlength="4" tabindex="-1" />
```
```javascript
$(function(){
  $('.userdata').pulldownChange('city','town','zip',twData,true,'please select');
});
```
