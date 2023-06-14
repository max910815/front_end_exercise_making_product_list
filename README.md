
1). C# 事件與委派函式的運作原理:

在C#中，事件是一種特殊的委派，它可以將多個方法附加到自己身上。當事件被觸發時，所有附加到該事件的方法都會被調用。不過事件增加了一層封裝，使得只有宣告該事件的類別能夠觸發它，而外部的程式碼不能直接調用委派的方法。

例如，當使用者點擊一個按鈕時，如果按鈕有關聯的 <Button.click> 事件，則該事件會被觸發，並調用所有註冊到該事件的委派方法。

2). JavaScript 的事件處理函式:

與C#不同，JavaScript的事件處理比較靈活。在JavaScript中，可以使用事件監聽器將一個或多個函式附加到特定事件上。當該事件被觸發時，所有附加的函式都會被調用。不過，這些函式不僅可以作為事件處理器使用，還可以獨立調用。

例如，如果你有一個函式負責更改背景顏色，你可以將它附加到按鈕的點擊事件上，也可以在程式的其他地方直接調用它。

3). submit 事件與 click 事件的區別:

submit 事件通常與HTML表單元素相關聯。當使用者在表單中填寫資料並點擊提交按鈕時，submit 事件被觸發，通常用於處理表單的資料提交。

而 click 事件是更通用的，可以應用於許多元素。當使用者點擊這些元素時，就會觸發 click 事件。它不僅可以用於表單提交按鈕，還可以用於其他任何可以點擊的元素，如一般按鈕、連結等。
