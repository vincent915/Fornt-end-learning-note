# Javascript的基礎應用練習  
> 這些練習都是從 [W3Schools.com](https://www.w3schools.com/default.asp)上做參考使用。  
> 無任何商業用途，純屬個人學習用。  

<br>  

## 關於Javascript的概念：  
* Document  
* Objects  
* Event  
* Array  
* Var  
* Booleans  
* Switch  
* Loop  
* Conts / Let   
* Function 
* Classes   
  
<br>    

## Javascript延伸應用： 
* JSON  
* AJAX  
* JQUERY    

<br><br> 

# &#9989;JavaScript輸出(Output)

## JavaScript顯示的可能性
### JavaScript可以通過不同的方式“顯示”數據：
* 使用innerHTML寫入HTML元素。
* 使用document.write（）寫入HTML輸出。
* 使用window.alert（）寫入警報框。
* 使用console.log（）寫入瀏覽器控制台。    
  
<hr>    

## 1. 使用 innerHTML
要訪問HTML元素，JavaScript可以使用document.getElementById（id）方法。

id屬性定義HTML元素。 innerHTML屬性定義HTML內容。 
> 更改HTML元素的innerHTML屬性是在HTML中顯示數據的常用方法。   

<br>    

## 2. 使用 document.write() 
出於測試目的，使用document.write（）很方便。    
> 加載HTML文檔後使用document.write（），將刪除所有現有的HTML。  
> document.write（）方法應僅用於測試。  

<br>    

## 3. 使用 window.alert() 
可以使用警報框顯示數據。    
> 1. 您可以跳過window關鍵字。   
> 2. 在JavaScript中，窗口對像是全局範圍對象，這意味著變量，屬性和方法默認情況下屬於窗口對象。 這也意味著指定window關鍵字是可選的。  

<br>    

## 4. 使用 console.log()    
為了進行調試，可以在瀏覽器中調用console.log（）方法以顯示數據。 

<br><br><hr>    

# &#9989;JavaScript語法(Syntax) 

## JavaScript語法是規則集，如何構造JavaScript程序： 
```
 var x, y, z;       // 聲明變量   
 x = 5; y = 6;      // 賦值   
 z = x + y;         // 計算值  
```

<br>

## 1.JavaScript值
### JavaScript語法定義了兩種類型的值：

* 固定值    
* 可變值(變量值)    
> 固定值稱為文字。  
> 變量值稱為變量。  

<br>    

# &#9989;JavaScript變數(Variables)
>在編程語言中，變量用於存儲數據值。  
>JavaScript使用var關鍵字聲明變量。   
>等號用於為變量分配值。  
```
 /* 在此示例中，x被定義為變量。 然後，為x分配（給定）值6：  */
 
 var x;   
 x = 6;  
 ```  

<br>

# &#9989;JavaScript關鍵字(Keywords)
> JavaScript關鍵字用於標識要執行的動作。    
```  
/* var關鍵字告訴瀏覽器創建變量：  */    

 var x, y;  
 x = 5 + 6;    
 y = x * 10;  
``` 

<br>    

# &#9989;JavaScript標識符(Identifiers)
標識符是名稱。
在JavaScript中，標識符用於命名變量（以及關鍵字，函數和標籤）。  
在大多數編程語言中，法定名稱的規則幾乎相同。    
在JavaScript中，第一個字符必須是字母，下劃線（_）或美元符號（$）    。  
後續字符可以是字母，數字，下劃線或美元符號。    
> 不允許數字作為第一個字符。
這樣，JavaScript可以輕鬆區分標識符和數字。

<br>    

# &#9989;JavaScript區分大小寫
所有JavaScript標識符均區分大小寫。  
變量"lastName"和"lastname"是兩個不同的變量。   

<br>    

# &#9989;JavaScript賦值運算符(Assignment Operators)
賦值運算符將值分配給JavaScript變量。    
[JavaScript Assignment Operators](https://www.w3schools.com/js/js_assignment.asp) >>>>>>>> 運算子參考   
```   
 var x = 10;   
 x += 5; 
```
  
<br>    

```
 <p id="demo"></p> 

 <script>		
 var x = 10;   
 x += 5;   
 document.getElementById("demo").innerHTML = x; 
 </script>   
 
/* 實際HTML顯示出的結果如下：*/  
 x = 15 
 ‵``
