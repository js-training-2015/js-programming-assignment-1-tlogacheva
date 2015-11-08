function solution1 (a,b,c) {
  return Math.ceil((b-a)/c);
}
 
function solution2 (a,b) {
  var max = 0;
 
  while (a < b) {
    var atmp = a++;
   
    while (atmp <= b) {
      var currmax = atmp ^ a;
     
      if (max < currmax) {
        max = currmax;
      }
           
      atmp++;
    
    }
   a++;
  }
 
return max; 
}
