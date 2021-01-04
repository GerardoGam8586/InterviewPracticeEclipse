# Interview Practice 

Unicorn

Given a number 'n', implement a method that prints in a different line:
- "My name is: unicorn" every time that 'n' value ends in 1 (1,11,21...).
- "My name is: unosquare" every time that 'n' value is divisible by 5 (5,10,15,etc).
- "My name is: number" for every other 'n' value.
Considerations:
- Input must be an Integer bigger than 0.
- Method signature must be void detectUnicorn(int)
- Code must not exceed 22 lines.

Examples:
  Input: 3
  
  Output: 
  
     My name is unicorn
     
     My name is number
     
     My name is number 

Examples:
  Input: 6
  
  Output:
  
     My name is unicorn
     
     My name is number
     
     My name is number
     
     My name is number
     
     My name is unosquare
     
     My name is number

----------------------------------------------------------------------------
Chess

Given a number 'n', implement a method that prints a chess board where black cells must be represented by a number sign (#) and white cells must be represented by a blank space ( ).
Considerations:
- Input must be an Integer bigger than 0.
- Method signature must be void printChessBoard(int)
- Code must not exceed 20 lines.

Examples:
  Input: 2
  
  Output: 
  
     #  
     
      #
      

  Input: 3
  
  Output: 
  
     # #
     
      # 
      
     # # 
     
     
  Input: 4
  
  Output: 
  
     # # 
     
      # #
      
     # # 
     
      # #
      

----------------------------------------------------------------------------
Dissapear

Given a String 'phrase', implement a method that removes every single character inside the word "uno" from 'phrase' and prints the resultant phrase.
Considerations:
- Input must not be null or blank.
- Method signature must be void unoDissapear(String)

Examples:
  Input: I work for unosquare
  Output: I wrk fr sqare

Examples:
  Input: I want to become a unicorn
  Output: I wat t becme a icrn
