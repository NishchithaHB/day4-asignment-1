# day4-asignment-1
Bizzword display

for(i=1; i<101; i++){
  x=i/3;
  y=i/5; 
  z=i/15; 
  if(Number.isInteger(x)){
    console.log("Fizz"); 
    
  } else if(Number.isInteger(y))
  { console.log("Buzz"); 
    
  } else if(Number.isInteger(z))
  { console.log("FizzBuzz"); 
    
  }else{ console.log(i); } 
  
}
