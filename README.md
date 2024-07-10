//function declaration
function sum(...args) {
    let sum = 0;
    for (let arg of args) sum += arg;
    return sum;
  }
  
  let x = sum(4, 9, 16, 25, 29, 100, 66, 77);
  console.log(x);

//arrow function 
  const greet = (name) => {
    return `Hello, ${name}!`;
  };
  
  
  console.log(greet("vinayak"));

  //default parameters
  function okk(name = "Guest", greeting = "Hello") {
    return `${greeting}, ${name}!`;
  }
  
  
  console.log(okk()); 
  console.log(okk("vinayak")); 

  //Destructuring Parameters
  function yes({ name = "Guest", greeting = "Hello" } = {}) {
    return `${greeting}, ${name}!`;
  }
  console.log(yes()); 
  console.log(yes({ name: "vinayak" })); 
  console.log(yes({ name: "radhe", greeting: "radhe" })); 
  
  //Function Naming Conventions
  function sendEmail(recipient, subject, body) {
    
  }
  
  function calculateInterest(principal, rate, time) {
    
  }

  //pure function
  function add(a, b) {
    return a + b;
  }
  
  
  console.log(add(2, 3));
  
   
