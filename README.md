# Student Info

Matric : 272828

Name : Juliney A/P Sen

# Introduction

In this assigment I need to write pseudocode , draw the flow chart , and write a Java program to solve the problem.

I need to calculate monthly repayment according to the car price, downpayment, loan period, and rate based on user 

input. Then I also need to find and display value of principal, interest, and balance for every year based on loan 

period. I use looping in program code because there are condition like the value of price cannot less than RM 30 000. 

So, I learn how to use looping using while statement.

# Pseudocode


Start
     
     read price
    
        while price less than RM 30 000
        
        read price
        
        endwhile
        
    read downpayment
    
        while downpayment less than RM 0
        
        read downpayment
        
        endwhile
        
    read loan period
    
        while loan period less than 5 years or more than 9 years
        
        read laon period
        
        endwhile
        
    read rate
    
        while rate less than 3 % or more than 7 %
        
        read rate
        
        endwhile
        
    total interest = (price-downpayment)*loan*(rate/100)
    
    monthly repayment = (price - downpayment + total interest) /(loan*12)
    
    display monthly repayment

    intialize i=0
    
    while i less than loan
    
        years=i+1
        
        principal = monthly repayment*12*years
        
        interest = (price-downpayment)*(rate/100)*years
        
        balance = (monthly repayment*loan*12) - principal
        
        display years, principal, interest, balance
        
        i=i+1
        
    endwhile
    
 Stop
 
 # Flowchart
 
 ![Flowchart](https://user-images.githubusercontent.com/55243931/68543015-da6d9000-03ec-11ea-87f2-1df5155e5f22.png)
 
 # Screenshot for output
 
 ![Screenshot (361)](https://user-images.githubusercontent.com/55243931/68502239-e9442d80-029a-11ea-94d6-8906c4fd94eb.png)
