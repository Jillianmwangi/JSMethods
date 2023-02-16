
//array

push() -adds element to array(at the end)
   const fruits = ["Banana", "Orange", "Apple", "Mango"];
   let newfruit = fruits.push("Kiwi");
shift() - removing from start
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  let fruit = fruits.shift(); 

unshift - adds element at the beginning
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  let newfruits = fruits.unshift("Lemon");


pop - removes last element of array
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  let fruit = fruits.pop();

length - provides easy way to append a new element
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  fruits[fruits.length] = "Kiwi"; 

splice - adds new item to array
  const fruits = ["Banana", "Orange", "Apple", "Mango"];
  fruits.splice(2, 0, "Lemon", "Kiwi");
1st parameter defines postion to add spliced element
2nd defines how many elements to be removed

reduce 

join - joins all array methods into a string

indexof - searches an element of an array and returns its position

includes - checks if an array contains a specified element
returns a boolean value

finc - returns the first value of an array element that passes a test

findIndex - returns the first index of an array element that passes a test    

map -  loops thru elements &returns index
 

filter - returns whichever array fulfilling a criteria


Fill - fills array w specified value


reverse - reverses elements in an array

//String methods 

charAt(index) - returns a char ata a specified index in a string
  let text = "HELLO WORLD";
  let char = text.charAt(3);

concat()-joins strings
   let text1 = "Hello";
   let text2 = "World";
   let text3 = text1.concat(" ", text2);
replace()- replacesspecified value w another value in the string
  let text = "Travel Tukizuru";
  let newtext= text.replace ("Tukizuru","African")
 
split() - coverts string to an array
  text.split("   ") 

substr(start, length) - similar except 2nd parameter specifies the length of extracted part
   let text = "hey, you, girl, over, there";
   let part = text.substr(9, 4)
if you omit the 2nd value it will slice the rest of the string

   
substring(start,end) - similar to slice except start andend values less than 0 are treated as 0 
   let text = "hey, you, girl, over, there";
   let part = text.substring(9, 13) 


slice(start, end) - extracts a part of a string and returns the extracted part 
   let text = "hey, you, girl, over, there";
   let part = text.slice(9, 13)

toLowerCase()- converts to lower case
  let text1 = "Hello World!";       
  let text2 = text1.toLowerCase(); 

toUpperCase() 
  let text1 = "Hello World!";       
  let text2 = text1.toUpperCase(); 

trim() removes whitespace
  let text1 = "      Hello World!      ";
  let text2 = text1.trim();
theres also trimstart() and trimend()

includes() 

search()  

 