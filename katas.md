# CodeWars 
# K A T A S 
Hello there! Here you will find the answers to some katas 8 kyu I've done(:  

> 8 kyu <

...

# Double Char 

function doubleChar(str) {

  let double = "";
  
  for (let i = 0; i < str.length; i++){
  
  double += (str[i]+str[i]);
  
  }
  
  return String(double)

}

...

# Count the Monkeys!

function monkeyCount(n) {

  let sumN = [];
  
  let count = "";

  for(let i = 0; i < n ; i++) {
  
  count = i + 1;
  
  if ( count !== 0) {
  
  sumN.push(count);
      
  }
  
  }
  
  return sumN;
    
  }

(other option, more reduced)

function monkeyCount(n) {

  let sumN = [];
  
  for(let i = 1; i < n+1 ; i++) {
  
   sumN.push(i);
      
}
  
  return sumN;
  
}

...








