# OOAD-WEEK10
Sequence Diagram

# ส่งการบ้าน 

 1. การซื้อสินค้าออนไลน์
 
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

 2. E-Leanign
  
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
 
 3. Register Leaning
 
  ```
 @startuml

title register Leaning

Student -> System : Login
System -> System : Vality
System -> Student : Show Display
Student -> System : Choose ID Subject
System -> System : Vality
System -> Student : Show Display Subject
Student -> System : Confirm registration
System -> Register : Send Data
System <- Register : The amount to be paid
System -> Student : The amount to be paid
Register <- Student : Pay

@enduml
 ```
 
 ![](https://github.com/fernkamon/OOAD-WEEK10/blob/master/img%2520ooad%2520week10/Register.png)
 
   
 4. การยืมหนังสือ
   
  ```  
   @startuml

title Borrowing books

Member -> librarian : tell Data member
Member <- librarian : Vality
Member -> Book : Borrow
librarian -> Book : Vality Book Details
Member <- librarian : Date return Book
librarian -> recordBook : Details filling

@enduml
 ``` 
 ![](https://github.com/fernkamon/OOAD-WEEK10/blob/master/img%252520ooad%252520week10/Borrow.png)
 
  
 5. โรงพยาบาล
 
 ```
 @startuml

title Hospital

patient -> staff : Filed cue cards
staff -> staff : Vality Data \npatient
staff -> nurse : Send Data patient
nurse -> patient : The queue of patients
nurse -> patient : Ask preliminary symptoms
nurse -> Doctor : Sent Data preliminary \nsymptoms of patient
Doctor -> patient : cure
Doctor -> apothecary : Prescriptions
apothecary -> apothecary : Find prescription drugs
apothecary -> clerk : Send Values medicines
apothecary -> patient : medication
patient -> clerk : pay money

@enduml
  ```
 
 ![](https://github.com/fernkamon/OOAD-WEEK10/blob/master/hotpital.png)
 
  
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
 
