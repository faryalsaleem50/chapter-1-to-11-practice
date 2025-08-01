# chapter-1-to-11-practice
<!DOCTYPE html>
<html>
<head>
  <title>Greeting Page</title>
</head>
<body>

  <script>
    // CHAPTER 1 - QUESTION 1
    alert("Welcome to my website!");

    // QUESTION 2
    alert("Error! Please enter a valid password.");

    // QUESTION 3
    alert("Welcome to JS Land...\nHappy Coding!");

    // QUESTION 4
    alert("Welcome to JS Land");

    // QUESTION 5
    alert("Hello! I can run JS through my web browser's console");
    console.log("Hello! I can run JS through my web browser's console");

    // QUESTION 6 & 7 — 
    // JavaScript can be written:
    // - Inside <head> using <script>
    // - Inside <body> using <script>
    // - Before </html> tag
    // agar mein isme likhre hun tu code kharab horaha hai is wja se tag nhi use krhi

    // --- CHAPTER 1 COMPLETED ---

    // CHAPTER 2 - QUESTION 1
    var username = "faryal";
    console.log(username);

    // QUESTION 2
    var myName = "Faryal Saleem";
    console.log(myName);

    // QUESTION 3
    var message = "HELLO WORLD";
    alert(message);

    // QUESTION 4
    var studentName = "Faryal Saleem";
    alert(studentName);
    var studentAge = 20;
    alert(studentAge);
    var studentCourse = "Web Development";
    alert(studentCourse);

    // Alternative way (also is tarike se use kr sakte hain):
    // var bioData = "Name: " + studentName + "\nAge: " + studentAge + "\nCourse: " + studentCourse;
    // alert(bioData);

    // QUESTION 5
    var pizza = "PIZZA\nPIZZ\nPIZ\nPI\nP";
    alert(pizza);

    // QUESTION 6
    var email = "faryalsaleem50@gmail.com";
    alert("My email address is " + email);

    // QUESTION 7
    var book = "A smarter way to learn JavaScript";
    alert("I am trying to learn from the Book " + book);

    // QUESTION 8
    var htmlContent = "Yah! I can write HTML content through JavaScript";
    document.write(htmlContent);

    // QUESTION 9
    var design = "▬▬▬▬▬▬▬▬▬ஜ۩۞۩ஜ▬▬▬▬▬▬▬▬▬";
    alert(design);
    document.write("<br>" + design);

    // --- CHAPTER 2 COMPLETED ---

    // CHAPTER 3 - QUESTION 1
    var age = 20;
    alert("I am " + age + " years old");

    // QUESTION 2
    var visitCount = 14;
    alert("You have visited this site " + visitCount + " times");

    // QUESTION 3
   var birthYear = 2007;
document.write("My birth year is " + birthYear + "<br>Data type of my declared variable is " + typeof birthYear + "<br>");

    // QUESTION 4
    var visitorName = "John Doe";
    var productTitle = "T-shirt";
    var quantity = 5;
    document.write(visitorName + " ordered " + quantity + " " + productTitle + " on Faryal Clothing store");

    // --- CHAPTER 3 COMPLETED ---

    // CHAPTER 4 - QUESTION 1
    var variable1, variable2, variable3;

    // QUESTION 2
   var userName;
var $price;
var _value;
var firstName;
var total1;
//illegal variable names
// var 1stName; // Cannot start with a number
// var my-name; // Cannot contain hyphen
// var my name; // Cannot contain spaces
// var @name; // Cannot start with special character
// var function; // Cannot use reserved keywords

    // QUESTION 3
    document.write("<h1>Rules for naming JS variables</h1>");
document.write("Variable names can only contain letters, numbers, $ and _. For example: <b>$my_1stVariable</b><br>");
document.write("Variables must begin with a letter, $ or _. For example: <b>$name</b>, <b>_name</b> or <b>name</b><br>");
document.write("Variable names are case <b>Sensitive</b><br>");
document.write("Variable names should not be JS <b>keywords</b><br>");

    // --- CHAPTER 4 COMPLETED ---

    // CHAPTER 5 - QUESTION 1
    var num1 = 3;
    var num2 = 5;
    var sum = num1 + num2;
    document.write("Sum of " + num1 + " and " + num2 + " is " + sum + "<br>");

    // QUESTION 2
    var difference = num1 - num2;
    document.write("Difference of " + num1 + " and " + num2 + " is " + difference + "<br>");

    var product = num1 * num2;
    document.write("Product of " + num1 + " and " + num2 + " is " + product + "<br>");

    var quotient = num1 / num2;
    document.write("Quotient of " + num1 + " and " + num2 + " is " + quotient + "<br>");

    var remainder = num1 % num2;
    document.write("Remainder of " + num1 + " and " + num2 + " is " + remainder);

    // QUESTION 3
    var variable;
    document.write("<br>Value after variable declaration is: <b>" + variable + "</b>");
    variable = 5;
    document.write("<br>Initial value: <b>" + variable + "</b>");
    variable++;
    document.write("<br>Value after increment is: <b>" + variable + "</b>");
    variable += 7;
    document.write("<br>Value after addition is: <b>" + variable + "</b>");
    variable--;
    document.write("<br>Value after decrement is: <b>" + variable + "</b>");
    variable %= 3;
    document.write("<br>The remainder is: <b>" + variable);

    // QUESTION 4
   var ticketPrice = 600;
    var totalCost = ticketPrice * 5;
    document.write("<br>Total cost to buy 5 tickets to a movie is " + totalCost + " PKR");

    // QUESTION 5
    document.write("<h2>Table of 4</h2>");
    for (var i = 1; i <= 10; i++) {
      document.write("4 x " + i + " = " + (4 * i) + "<br>");
    }

    // QUESTION 6
    var celsius = 25;
    var fahrenheit = (celsius * 9/5) + 32;
    document.write("<br>" + celsius + "°C is " + fahrenheit + "°F");

    var fahrenheit = 70;
    var celsius = (fahrenheit - 32) * 5/9;
    document.write("<br>" + fahrenheit + "°F is " + celsius + "°C");

    // QUESTION 7
    var item1Price = 650;
    var item2Price = 100;
    var item1Quantity = 3;
    var item2Quantity = 7;
    var shippingCharges = 100;

    var totalCost = (item1Price * item1Quantity) + (item2Price * item2Quantity) + shippingCharges;
    document.write("<br><h2>Shopping Cart</h2>");
    document.write("Price of item 1 is " + item1Price + "<br>");
    document.write("Quantity of item 1 is " + item1Quantity + "<br>");
    document.write("Price of item 2 is " + item2Price + "<br>");
    document.write("Quantity of item 2 is " + item2Quantity + "<br>");
    document.write("Shipping Charges " + shippingCharges + "<br>");
    document.write("Total cost of your order is " + totalCost);

    // QUESTION 8
   var totalMarks = 980;
   var obtainedMarks = 804;
   var percentage = (obtainedMarks / totalMarks) * 100;
   document.write("<br><h2>Marks Sheet</h2>");
   document.write("Total Marks: " + totalMarks + "<br>");
   document.write("Marks Obtained: " + obtainedMarks + "<br>");
   document.write("Percentage: " + percentage + "%");
    // QUESTION 9
    var usDollar = 104.80;
    var saudiRiyal = 28;
    var totalCurrency = (10 * usDollar) + (25 * saudiRiyal);
    document.write("<br><h2>Currency in PKR</h2>");
    document.write("Total Currency in PKR: " + totalCurrency);

    // QUESTION 10
    var number = 5;
    var result = ((number + 5) * 10) / 2;
    document.write("<br><h2>Result of the calculation</h2>");
    document.write("Result: " + result);

    // QUESTION 11
    var currentYear = 2025;
    var birthYear = 2007;
    var age = currentYear - birthYear;
    document.write("<br><h2>Age Calculator</h2>");
    document.write("Current Year: " + currentYear + "<br>");
    document.write("Birth Year: " + birthYear + "<br>");
    document.write("Your Age: " + age + " years");

    // QUESTION 12
    var radius = 20;
    var circumference = 2 * Math.PI * radius;
    var area = Math.PI * radius * radius;
    document.write("<br><h2>Circle Properties</h2>");
    document.write("Radius: " + radius + "<br>");
    document.write("Circumference: " + circumference + "<br>");
    document.write("Area: " + area + "<br>");

    // QUESTION 13
    var favoriteSnack = "Chocolate Chip Cookies";
    var currentAge = 16;
    var maxAge = 65;
    var estimatedSnacksPerDay = 3;
    var daysInYear = 365;

    var totalSnacksNeeded = (maxAge - currentAge) * daysInYear * estimatedSnacksPerDay;
    document.write("<br><h2>Snack Calculator</h2>");
    document.write("Favorite Snack: " + favoriteSnack + "<br>");
    document.write("Current Age: " + currentAge + "<br>");
    document.write("Estimated Snacks Needed: " + totalSnacksNeeded + " snacks");
document.write("<br><br>"); 
    // --- CHAPTER 5 COMPLETED ---

        //CHAPTER 6 TO 9 QUESTION 1
   var a = 10;
document.write("Result:<br>");
document.write("The value of a is: " + a + "<br><br>");

++a;
document.write("The value of ++a is: " + a + "<br>");
document.write("Now the value of a is: " + a + "<br><br>");

document.write("The value of a++ is: " + a + "<br>");
a++;
document.write("Now the value of a is: " + a + "<br><br>");

--a;
document.write("The value of --a is: " + a + "<br>");
document.write("Now the value of a is: " + a + "<br><br>");

document.write("The value of a-- is: " + a + "<br>");
a--;
document.write("Now the value of a is: " + a);
document.write("<br><br>");

          //QUESTION NO 2
        
var a = 2, b = 1;
document.write("<h2>Initial values:</h2>");
var a = 2, b = 1;

document.write("Initial values: a = " + a + ", b = " + b + "<br>");

var result = --a - --b + ++b + b--;

document.write("After --a: a = " + a + "<br>");        // a = 1
document.write("After --b: b = " + b + "<br>");        // b = 0
document.write("After ++b: b = " + (++b) + "<br>");    // b = 1
document.write("Value used in b--: 1, then b becomes " + (--b) + "<br>");  // b becomes 0 after b--

document.write("Final result = " + result + "<br>");
document.write("Final values: a = " + a + ", b = " + b);

      //  QUESTION 3
var userName = prompt("What is your name?");
alert("Hello, " + userName + "! Welcome to our website.");

      // QUESTION 4
var number = prompt("Enter a number for multiplication table:", "5");

// If user cancels or enters nothing, use 5 as default
if (number === null || number.trim() === "") {
  number = 5;
}

number = Number(number); 

document.write("<h3>Multiplication Table of " + number + "</h3>");
for (var i = 1; i <= 10; i++) {
  document.write(number + " x " + i + " = " + (number * i) + "<br>");
}

      // QUESTION 5
var subject1 = prompt("Enter name of Subject 1:");
var subject2 = prompt("Enter name of Subject 2:");
var subject3 = prompt("Enter name of Subject 3:");

var totalMarksPerSubject = 100;
var totalMarks = totalMarksPerSubject * 3;

var marks1 = +prompt("Enter obtained marks for " + subject1);
var marks2 = +prompt("Enter obtained marks for " + subject2);
var marks3 = +prompt("Enter obtained marks for " + subject3);

var obtainedMarks = marks1 + marks2 + marks3;
var percentage = (obtainedMarks / totalMarks) * 100;

document.write("<table border='1' cellpadding='10'>");
document.write("<tr><th>Subject</th><th>Total Marks</th><th>Obtained Marks</th></tr>");
document.write("<tr><td>" + subject1 + "</td><td>100</td><td>" + marks1 + "</td></tr>");
document.write("<tr><td>" + subject2 + "</td><td>100</td><td>" + marks2 + "</td></tr>");
document.write("<tr><td>" + subject3 + "</td><td>100</td><td>" + marks3 + "</td></tr>");
document.write("<tr><th>Total</th><th>" + totalMarks + "</th><th>" + obtainedMarks + "</th></tr>");
document.write("<tr><th colspan='2'>Percentage</th><th>" + percentage.toFixed(2) + "%</th></tr>");
document.write("</table>");
    // --- CHAPTER 6 TO 9 COMPLETED ---

    // CHAPTER 9 TO 11 - QUESTION 1
    var city = prompt("Enter your city:");
    if (city.toLowerCase() === "karachi") {
      alert("Welcome to the city of lights!");
    }

    // QUESTION 2
    var gender = prompt("Enter your gender:");
    if (gender.toLowerCase() === "male") {
      alert("Hello Sir!");
    }else if (gender.toLowerCase() === "female") {
      alert("Hello Ma'am!");
    } else {
alert("Hello!");
    }
    // QUESTION 3
  var signalColor = prompt("Enter the traffic signal color (Red, Yellow, Green):");

document.write("<h2>Traffic Signal</h2>");
document.write("Signal Color: " + signalColor + "<br>");

if (signalColor.toLowerCase() === "red") {
  document.write("Message: Must Stop");
} else if (signalColor.toLowerCase() === "yellow") {
  document.write("Message: Ready to move");
} else if (signalColor.toLowerCase() === "green") {
  document.write("Message: Move now");
} else {
  document.write("Message: Invalid color entered");
}
           // QUESTION 4
var fuel = +prompt("Enter remaining fuel in liters:");

if (fuel < 0.25) {
  alert("Please refill the fuel in your car");
}
    // QUESTION 5
    var a = 4;
    if (++a === 5) {
      alert("Given condition for variable a is true");
    }

    var b = 82;
if (b++ === 83) {
  alert("given condition for variable b is true");
}

    var c = 12;
    if (c++ === 13) {
      alert("Condition 1 is true");
    }
    if (c === 13) {
      alert("Condition 2 is true");
    }
    if (++c < 14) {
      alert("Condition 3 is true");
    }
    if (c === 14) {
      alert("Condition 4 is true");
    }

    var materialCost = 20000;
    var laborCost = 2000;
    var totalCost = materialCost + laborCost;

    if (totalCost === laborCost + materialCost) {
      alert("The cost equals");
    }

    if (true) {
      alert("True");
    }

    if (false) {
      alert("False");
    }
    if ("car" < "cat") {
      alert("car is smaller than cat");
    }

    // QUESTION 6
    var sub1 = +prompt("Enter marks for Subject 1:");
var sub2 = +prompt("Enter marks for Subject 2:");
var sub3 = +prompt("Enter marks for Subject 3:");
var totalMarks = +prompt("Enter total marks:");

var obtained = sub1 + sub2 + sub3;
var percentage = (obtained / totalMarks) * 100;
var grade, remarks;

if (percentage >= 80) {
  grade = "A-one";
  remarks = "Excellent";
} else if (percentage >= 70) {
  grade = "A";
  remarks = "Good";
} else if (percentage >= 60) {
  grade = "B";
  remarks = "You need to improve";
} else {
  grade = "Fail";
  remarks = "Sorry";
}

document.write("<h2>Marks Sheet</h2>");
document.write("Total Marks: " + totalMarks + "<br>");
document.write("Marks Obtained: " + obtained + "<br>");
document.write("Percentage: " + percentage.toFixed(2) + "%<br>");
document.write("Grade: " + grade + "<br>");
document.write("Remarks: " + remarks);

    // QUESTION 7
   var secretNumber = 7;
var userGuess = +prompt("Guess the secret number (1 to 10):");

if (userGuess === secretNumber) {
  alert("Bingo! Correct answer");
} else if (userGuess === secretNumber + 1 || userGuess === secretNumber - 1) {
  alert("Close enough to the correct answer");
} else {
  alert("Wrong guess, try again!");
}


    // QUESTION 8
   var number = +prompt("Enter a number:");

if (number % 3 === 0) {
  alert("The number is divisible by 3");
} else {
  alert("The number is not divisible by 3");
}


    // QUESTION 9
    var number = +prompt("Enter a number:");

if (number % 2 === 0) {
  alert("The number is Even");
} else {
  alert("The number is Odd");
}


    // QUESTION 10
   var temp = +prompt("Enter temperature:");

if (temp > 40) {
  alert("It is too hot outside.");
} else if (temp > 30) {
  alert("The Weather today is Normal.");
} else if (temp > 20) {
  alert("Today’s Weather is cool.");
} else if (temp > 10) {
  alert("OMG! Today’s weather is so Cool.");
} else {
  alert("It's very cold!");
}

    // QUESTION 11
var num1 = +prompt("Enter the first number:");
var num2 = +prompt("Enter the second number:");
var operator = prompt("Enter operation (+, -, *, /, %):");

var result;

if (operator === "+") {
  result = num1 + num2;
} else if (operator === "-") {
  result = num1 - num2;
} else if (operator === "*") {
  result = num1 * num2;
} else if (operator === "/") {
  result = num1 / num2;
} else if (operator === "%") {
  result = num1 % num2;
} else {
  result = "Invalid operator";
}

document.write("<h2>Simple Calculator</h2>");
document.write("First Number: " + num1 + "<br>");
document.write("Second Number: " + num2 + "<br>");
document.write("Operation: " + operator + "<br>");
document.write("Result: " + result);
        //CHAPTER 9 TO 11 COMPLETED
</script>
</body>
</html>
