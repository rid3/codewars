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

## (other option, more reduced)

function monkeyCount(n) {

  let sumN = [];
  
  for(let i = 1; i < n+1 ; i++) {
  
   sumN.push(i);
      
}
  
  return sumN;
  
}

...

# The feats of Many Beasts 

function feast(beast, dish) {
  
  for (let i = 0; i < beast.length; i++ ){
  
   for ( let j = 0; j < dish.length; j ++) {
      
   if (beast[0] === dish[0] && beast[beast.length-1] === dish[dish.length -1] ) {
   
   return true;
   
   } else {
    return false
     }
    }
   }
  }
    
## (other option, more reduced)
 
 function feast(beast, dish) {

  return beast[0] === dish[0] && beast[beast.length - 1] === dish[dish.length - 1]
   
}

...





