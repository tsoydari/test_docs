# METHODS

## Request Methods
| HTTP type   | name             |
|:------------|:-----------------|
| PUT         | [/test1](#test1) |
| PUT         | [/test2](#test2) |
| POST        | [/test3](#test3) |
| POST        | [/test4](#test4) |


### /test1
Description of method 1

<b>Field list</b>  
- <i><b>token</b></i> (*required): string  
&nbsp;&nbsp;&nbsp; Registered token.
- <i><b>file</b></i> (*required): string($binary)  
&nbsp;&nbsp;&nbsp; JSON file.

File example:
```
{
	"type1" : [
		"shiba_inu", "husky"
	],
	"type2": [
		"maine_coon"
	]
}
```  
\
<b>Response</b>  
If successful, the response body contains data with the following structure:
```
{
  "success": "success"
}
```


### /test2
Description of method 2  
\
<b>Response</b>  
If successful, the response body contains data with the following structure:
```
{
  "success": "success"
}
```
\
Other response examples with errors check in [ERRORS](ERRORS.md#test2) section.

### /test3
Description of method 3   
\
<b>Response</b>  
If successful, file will be returned.
Other response examples with errors check in [ERRORS](ERRORS.md#test3) section.

### /test4
Description of method 4   
\
<b>Response</b>  
If successful, the response body contains data with the following structure:
```
{
  "status": "ok"
}
```
\
Other response examples with errors check in [ERRORS](ERRORS.md#test4) section.
