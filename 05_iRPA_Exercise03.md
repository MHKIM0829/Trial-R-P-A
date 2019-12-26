# iRPA Excercise 03

## 반복(Loop) 실행 Workflow

![images](./img/image121.png)

![images](./img/image122.png)

![images](./img/image123.png)

![images](./img/image124.png)

# 반복(Loop) 실행결과

![images](./img/image125.gif)


# Excel Export

![images](./img/image126.png)

![images](./img/image127.png)

![images](./img/image128.png)

![images](./img/image129.png)

![images](./img/image130.png)


![images](./img/image131.png)

![images](./img/image132.png)

![images](./img/image136.png)

![images](./img/image137.png)


```javascript
    var today = new Date();
	var dd = today.getDate();
	var mm = today.getMonth()+1;
	var yyyy = today.getFullYear();
	
	var oExcelFilePath = "C:\\Users\\weaver7\\Documents\\";
	var oExcelFileName = "테스트_"+yyyy + mm + dd;
	var oExcelExtension = ".xlsx";
	
	var oExcelFilePath = oExcelFilePath + oExcelFileName + oExcelExtension;
	
	ctx.log("@@@@@oExcelFilePath@@@ :" + oExcelFilePath);
	
	ctx.excel.file.saveAs(oExcelFilePath);
```

# 실행결과

![images](./img/image138.gif)

