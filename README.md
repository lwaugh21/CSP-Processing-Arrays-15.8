# CSP-Processing-Arrays-15.8
Flags, Does it have a 5?
// Fill an array with some random values
var testArray = [];
for (var i = 0; i < 10; i++) {
  appendItem(testArray, randomNumber(0,10));
}
console.log("Original: " + testArray);

// Make a variable to count the 5's
var fiveCount = 0;

// Process the array
for (var I = 0; I < testArray.length; I++) {
  
  //your code here
  if (testArray[I] == 5) {
   fiveCount++;
  }

}
if (fiveCount>0) {
  console.log("true");
} else {
  console.log("false");
}
