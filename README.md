# Vlookup-project1
## Finding the Net sales amt for the given sales person
=VLOOKUP(K3,A3:D15,3,FALSE)    
![img alt](https://github.com/nsankareswari-70/Vlookup-project1/blob/4535d99e818cd4a36be77a9bc001f9cd2a80fd73/ex88.png)

## If we are looking for the data that is not available, what would be the case?

![img alt](https://github.com/nsankareswari-70/Vlookup-project1/blob/0ccce75f56601f578a3e6d96d20fdcf698f375c2/ex89.png)

## How to avoid this N/A Error in VLookup()?    
Solution: We can avoid this by using Iferror() in Excel    
=IFERROR(VLOOKUP(K3,A3:D15,3,FALSE),"Not found")   
![img alt](https://github.com/nsankareswari-70/Vlookup-project1/blob/d3b12d91e247588be2717ecbea9a0d31a3317ac1/ex90.png)   

## Find the number of customers for Josh using vlookup()
=VLOOKUP(K6,A3:D15,2,FALSE)     
![img alt](https://github.com/nsankareswari-70/Vlookup-project1/blob/06d8886425c96e2098770259ad85a86f1edd25c4/ex91.png)

## To find the location of a particular value in a range and get its index - We use the Match function

=MATCH(K9,C3:C15,0)   
![img alt](https://github.com/nsankareswari-70/Vlookup-project1/blob/ac53835e3c617048f29ebfc0ce92c97f123578ad/ex92.png)

## Questions
1. How many sales did John make?    
=VLOOKUP(C17,A3:D15,3,FALSE)    
Ans: 1088    
2. How many customers did Jammy have?    
=VLOOKUP(K6,A3:D15,2,FALSE)     
Ans : 9    

3. What is the profit of Jessy?    
   =VLOOKUP(D17,A3:D15,4,FALSE)     
   Ans: 236   
4. How many customers did Joshua have?    
   N/A (Joshua is not available in the range

5. How many sales did Jonathan make?
   1316
6. Who made more sales - Jamie or Jackie?
   
   
   
   
   

   











