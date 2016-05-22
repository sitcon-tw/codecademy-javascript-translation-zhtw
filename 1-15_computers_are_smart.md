電腦好聰明
=============
讚！我們成功使用 `if` 陳述句來回答一個是與非，也就是 Javascript 裡面的真與假。
此外，除了在條件成立時( `true` )執行程式碼，我們也可以再條件不成立時( `false` )執行一些程式碼。舉例來說，如果你的名字小於七個字，我們可以回應 "You have a short name!"。我們可以用 `if` / `else` 來做到這一點。

```
if( "myName".length >= 7 ) {
    console.log("You have a long name!");
}
else {
    console.log("You have a short name!");  
}
```

如同以往，如果 _if_ 條件為真（ `true` ），那只有第一對大括號內的程式碼會被執行，否則，條件為假（ `false` ）時，只有在關鍵字 `else` 後面的第二對大括號內的程式碼會被執行。

在上述的舉例之中， `"myName".length >= 7` 為假（ `false` ），因為 "myName" 只有六個字，既然條件為假，只有關鍵字 `else` 之後的大括號內的程式碼會被執行，故會印出 `You have a short name!`。

說明
---------

1. 在第一行填入一個條件式使陳述句為假（ `false` ）。
2. 在 `else` 所引導的部分寫入一些程式碼（也就是只有條件式為假的時候會執行的部分）。在此用 `console.log` 做測試即可。