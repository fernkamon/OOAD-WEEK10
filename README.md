# OOAD-WEEK10
Sequence Diagram

# ส่งการบ้าน 

 การซื้อสินค้าออนไลน์
 
 ```
 @startuml

title Online Shopping

Customer -> WebOnline : Login
Customer -> WebOnline : Buy Order
WebOnline -> System : Send data is custemer\nand Order
System -> System : Check buy data \nof customer
System -> Customer : Send The amount to be paid
System -> Employee : Send buy data \nof customer
Customer -> Employee : transfer money
Employee -> Customer : delivery product

@enduml
 ```
 
 ![](https://github.com/fernkamon/OOAD-WEEK10/blob/master/img%20ooad%20week10/Online%20Shopping.png)

  E-Leanig
  
   ```
@startuml

title E-Leaning 

Student -> WEB : login
Student <- WEB : Show login
Student -> WEB : Complete login
WEB -> Server : Validation
Server -> Student : Show display index member
Student -> WEB : Into the lesson
Student <- WEB : Show the lesson
Student -> WEB : Choose lesson
WEB -> ELeaning : The lessons \nbe selected Send 
ELeaning -> Server : The lessons \nbe selected Send
Server -> Student : Show Display lesson

@enduml
 ```
 
 ![](https://github.com/fernkamon/OOAD-WEEK10/blob/master/img%2520ooad%2520week10/E-Leanig.png)
 
README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
