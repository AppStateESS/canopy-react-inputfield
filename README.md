Creates a input field for a form. Granted, may be overkill, but it helps
with labels and such.

|Prop name|Type|Description|
|----|----|----|
|name|string|Name parameter of input|
|label|string|A label that displays before the input|
|type|string|text, password, date, datetime, etc.|
|value|string,number|Value to appear in the field. Should couple to the state|
|change|function|Function called on change|
|blur|function|Function call when input blurred|
|placeholder|string|Default placeholder text shown in the input|
|errorMessage|string|Error message you want to appear under the input field|
|iid|string|Id parameter of input|
|autocomplete|boolean|The autocomplete status. Default true (not shown)|
|required|boolean|Whether input field is required for form. Will warn when blurred|
|disabled|boolean|If true, input will be disabled and unaccessible|
|size|string,number|Size of input (will not affect width due to Bootstrap 100%)|
|maxLength|number|Maximum number of characters allowed in field|
|wrap|function|Function that will receive the input field only. Useful if you want to wrap the input in tag but not the label|
|selectOnClick|boolean|If true, the value in the input will be highlighted for replacement|
|onEmpty|function|Function that should be run if the input is empty and blurred|
|disableRequireCheck|boolean|Disable the blur empty check when flagged as required. Lets you set your own way of handling empty inputs.|
