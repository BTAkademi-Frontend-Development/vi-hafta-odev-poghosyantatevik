# vi-hafta-odev

- JavaScript'te nesne(object) örnekleri yaratarak örnekler içerisinde metodlarla birlikte kullanmaya çalışınız.

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

- 'for in' ve 'for of' döngülerini açıklayınız ve örneklerle destekleyiniz.

- 'for' ve 'while' döngüleri ile ilgili örnekler yapınız.
