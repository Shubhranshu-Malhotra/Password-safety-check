# Password-safety-check  

This program has been built to **check the safety of passwords without exposing them to the internet**.   
  
Many leaks of user data of big companies like Amazon, Google, Microsoft, Adobe, LinkedIN, yahoo, etc. have occured in the past and continue to occur from time to time.   
**The complete list of user detail leaks can be found here: [ Wikipedia's list of user data leaks](https://en.wikipedia.org/wiki/List_of_data_breaches)**  
  
This program checks whether your password has been leaked on the internet in any of these leaks or not.    
The program can run on your local computer. This helps to avoid exposing your passwords online.    
This is an extremely secure way to check your paassword's security.  
  

## Running Instructions:  

#### To use this program to check safety of your passwords:  

1)  Download the `password_safety_checker.py file/ Password-safety-check repo`.
2)  Get the `path` where the `password_safety_checker.py` file is saved.
3)  Open command prompt.
4)  Navigate to the directory where you saved the downloaded program file (using cd command).
5)  Type `[python password_safety_checker.py <password 1> <password 2> <...>]` ( without [] and <>) in command line and press Enter.
6)  Check the response.

*  **Any number of passwords can be checked in a single call.**  
*  **Your passwords are not sent over the internet (they stay within your local machine) but you require an active internet connection to run this program.**  
  
### Running Example:   
**[If saved password_safety_checker.py on Desktop]**  
**The path below might differ depending on your user_name**  
    
      
`cd C:\Users\user_name\Desktop`  
`python password_safety_check.py password123 hellopassword hello`  

