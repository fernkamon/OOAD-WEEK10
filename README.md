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
 
 ![]

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
 
