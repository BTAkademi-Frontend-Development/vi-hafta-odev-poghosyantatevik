# vi-hafta-odev

- JavaScript'te nesne(object) örnekleri yaratarak örnekler içerisinde metodlarla birlikte kullanmaya çalışınız.

   [here is the link of my example](https://github.com/poghosyantatevik/homework-no-6/blob/9da62876d51867c88d8221334e8faf8ed8edfc9c/index4.html)

- 'return' ve 'console.log' arasındaki farkı açıklayınız. Örneklerle destekleyiniz.

   :dart: as a matter of fact there are several differences between return and console log. To name a few: return value will not appear in console. Console.log will display the parameter in the console.  Console.log is just a print statement, all languages have something like that. When you use return it will end loop or function, so the code below it will not be executed(important to note the code in the block scope). RETURN will also allow you to use the value returned in some other part of your program.
  
 **console.log:**
 
 let country = 'Venezuela';
 
 console.log('I love ' + country);
 
 
 
 **return:**
 
 const getLog = (country) => {
 
 return 'I love ' + country;
 
 }
 
 console.log(getLog('Venezuela'));
 

- JavaScript'te primitive types ve reference types kavramlarını araştırınız. Bu sınıflandırmalara dahil olan türleri sıralayınız.

  :dart:  **Primitive types or values**
  
  - string
  - number
  - boolean 
  - undefined 
  - null
  - symbol (ES6)


  The size of a primitive value is fixed, therefore, JavaScript stores the primitive value on the stack.
  When you assign a variable that stores a primitive value to another, the value stored in the variable is created and copied into the new variable.
  
  let x = 5;
  
  let y = x;
  
  y = 20; 
  
  console.log(x); // 5
  
  console.log(y); // 20
  
  
  as **x** and **y** have no relationship, when you change the value stored in the **y** variable, the value of the **x** variable doesn’t change.
  
  **Reference types**
    
  - Objects 
  - Arrays
  - functions(arrays and functions are also objects)
           
  The size of a reference value is dynamic so JS stores the reference value on the heap.
      
  Vriable that stores an object is accessed by reference.
      
  When you assign a reference value from one variable to another, the value stored in the variable is also copied into the location of the new variable.

The difference is that the values stored in both variables now are the address of the actual object stored on the heap. As a result, both variables are referencing the same object.

const a = {surname: 'Adams'};

const b = a;

b.surname = 'Johnson';

console.log(a); // 'Johnson';

      
  
- 'for in' ve 'for of' döngülerini açıklayınız ve örneklerle destekleyiniz.
- 

 :dart:  [link added to my homework-6 repository in 3 different HTML files](https://github.com/poghosyantatevik/homework-no-6.git)
 
 
   
- 'for' ve 'while' döngüleri ile ilgili örnekler yapınız.

  :dart:  **For Loop**
 
  There are 3  important pieces of information separated by semicolons ;:
 
  -The initialization defines where to begin the loop by declaring (or referencing) the iterator variable
  -The stopping condition determines when to stop looping (when the expression evaluates to false)
  -The iteration statement updates the iterator each time the loop is completed

  for (let i = 0; i < 4; i ++) {

  };
 
  **while Loop**
 
   The while loop creates a loop that is executed as long as a specified condition evaluates to **true**. 
   The loop will continue to run until the condition evaluates to **false**. 
   The condition is specified before the loop, and usually, some variable is changed in the while loop body to determine when the loop should stop.
 
    while (i < 10) {
 
    detailedInfo += "The number is " + i;
  
    i++;
}
