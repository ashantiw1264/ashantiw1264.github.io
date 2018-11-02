layout : post
tittle : "ashanti williams week 6"
date: 2018-11-2
---
...
#week6
theis week we have been learning about function and contract and how to create them so i have been learnig how to do that .   
!{github logo}(images/shapes.html.png.)
...
So Functions in a programming language have domains and ranges, too, and a contract can ensure that a function receives
only values in its domain and produces only values in its range. A -> creates such a contract for a function. The forms 
after a -> specify contracts for the domains and finally a contract for the range.
so this is what a contract and function looks like.
contract Conference { 
  address public organizer;
  mapping (address => uint) public registrantsPaid;
  uint public numRegistrants;
  uint public quota;

  // so you can log these events
  event Deposit(address _from, uint _amount); 
  event Refund(address _to, uint _amount);

  function Conference() { // Constructor
    organizer = msg.sender;
    quota = 500;
    numRegistrants = 0;
    or it looks like this 
    
#|
	For each of the word problems below, design a function by creating a contract, several test cases, and a definition. 

	Enter your design below the word problem.
|#

#-------------------------------------------------------------------------------#

# 0. Design a function called double, which takes in a number and doubles it.

# 1. Design a function called triple, which takes in a number and triples it.

# 2. Design a function called plus1, which takes in a number and adds one to it.

# 3. Design a function called multiplicative inverse, which takes in a number and produces its multiplicative inverse.

# 4. Design a function called mystery, that takes in a number and subtracts 4.

# 5. Design a function called red-spot, which takes in a number and draws a solid red circle, using the number as the radius.

# 6. Design a function called double-radius, which takes in a radius and a color. It produces an outlined circle of whatever color was passed in, whose radius is twice as big as the input.

# 7. Design a function double-width which takes in a height and a color. The function produces a solid rectangle, which is whatever height and color were passed in. Its width is twice the height.

# 8. Design a function called golden-rectangle, which takes in a height and a color and produces a solid rectangle, which is whatever height and color were passed in. Its width is in the golden ratio to its height. You will need to conduct an internet search to find the golden ratio.

# 9. Design a function called hypotenuse, which takes in the length of two legs of a right triangle and produces the length of its hypotenuse.

# 10. Design a function called distance, which takes in two coordinates as x1, y1, x2, y2 and produces the linear distance between the two points.

# 11. Design a function called first-char, which takes in a string and returns the first character.

# 12. Design a function called first-to-last, which consumes a string and returns a string where the first character has been moved to the end.

# 13. Design a function called remove-ith, which consumes a string and a number and returns a string with the character at the index of the given number removed.

# 14. Design a function called pig-latin, which takes the first consonant  of an English word, moves it to the end of the word and suffixes an ay, or if a word begins with a vowel you just add way to the end. For example, pig becomes igpay, banana becomes ananabay, and ardvark becomes ardvarkway.
so thats all for today people.















	


	
