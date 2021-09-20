# Homework 0 - The Zen of Python

###### tags: `Zen` `Python`

B07902130 周奕寬

`Beautiful is better than ugly.`
`Simple is better than complex.`
`Flat is better than nested.`
`Sparse is better than dense.`
`If the implementation is easy to explain, it may be a good idea.`

以上幾句是我在Python禪學之中最喜歡的部分。

我在Python禪學中最喜歡的部分就是它關於**程式碼要寫得簡單、漂亮、清楚**這些。
主要原因就是因為越簡單的程式碼越精煉，巢狀的程度越低，我們也越容易看懂它們，也就是英文俗諺中的`the simpler, the better`。
當一份程式碼融合了許多巧思而能寫的很簡單時，人們也會覺得它很漂亮。
我認為這應該也是Python設計者的想法。

在C/C++或是其他很多程式語言中，我們常常會因為語言上支援的功能沒那麼多而被迫要把某一些非常簡單的功能寫成很多行，或是包裝成一個較大的函數。
但是在Python的設計之上，常常能有許多**巧思**能讓我們以既有語法來在單行內表達出滿複雜的功能(至少在其他程式語言需要超過一行)。

幾個很常用的例子是:

    a,b=b,a
    
在一行裡面解決兩數字交換的問題。

    x=x[::-1]
    
輕鬆把整個陣列反轉。

    x=[(... if c==... else ...) for c in x]
    
簡單的把x陣列裡的所有物件依照條件處理為新的東西。

常常當我每次學到一個漂亮的新One-Liner時，總會令我非常驚豔於它的設計者的巧思、還有Python語言的無限潛能。
因此，這幾句是我最喜歡的Zen of Python句子，也代表了Python語言本身的設計美學。