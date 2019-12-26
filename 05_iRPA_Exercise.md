# iRPA Excercise

## 1. Capture

## Customer Packages

![images](./img/image054.png)

![images](./img/image055.png)

![images](./img/image056.png)

![images](./img/image057.png)

![images](./img/image058.png)

![images](./img/image059.png)

![images](./img/image060.png)

![images](./img/image061.png)

![images](./img/image062.png)

![images](./img/image063.png)

![images](./img/image064.png)

![images](./img/image065.png)

![images](./img/image066.png)

![images](./img/image067.png)

![images](./img/image067_1.png)



## Terminal Infos

![images](./img/image068.png)

![images](./img/image069.png)

![images](./img/image070.png)

![images](./img/image071.png)

![images](./img/image072.png)

![images](./img/image073.png)

![images](./img/image074.png)

![images](./img/image075.png)

![images](./img/image076.png)

![images](./img/image077.png)


## Terminal Details

![images](./img/image079.png)

![images](./img/image080.png)

![images](./img/image081.png)

![images](./img/image082.png)

![images](./img/image083.png)

![images](./img/image084.png)

![images](./img/image085.png)

![images](./img/image086.png)

![images](./img/image087.png)


## Partners

![images](./img/image088.png)

![images](./img/image089.png)

![images](./img/image090.png)

![images](./img/image091.png)

![images](./img/image092.png)

![images](./img/image093.png)

![images](./img/image094.png)

![images](./img/image095.png)

![images](./img/image096.png)

![images](./img/image097.png)

## Workflow

![images](./img/image098.png)

![images](./img/image099.png)

![images](./img/image100.png)

![images](./img/image101.png)

![images](./img/image102.png)

![images](./img/image103.png)

![images](./img/image104.png)

![images](./img/image105.png)

![images](./img/image106.png)

![images](./img/image107.png)

![images](./img/image108.png)

![images](./img/image109.png)

![images](./img/image110.png)

![images](./img/image111.png)

![images](./img/image112.png)

![images](./img/image113.png)

![images](./img/image114.png)

![images](./img/image115.png)

![images](./img/image116.png)

![images](./img/image117.png)

![images](./img/image118.png)

![images](./img/image119.png)

# 실행결과

![images](./img/image120.gif)


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


