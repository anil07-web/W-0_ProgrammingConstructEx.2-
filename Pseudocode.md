## Exercise 1:-Write a pseudocode for accepting radius and calculate the area of the circle.
```
begin
numeric r,a
accept r
a=3.14*r*r 
display a 
end
```
## Exercise 2:-Write a pseudocode for accepting a number and display the multiplication table of the given number.
```
begin
 numeric n,t
 accept n
 for(t=1;t<= 10;t++)
  begin
    n=n*t
    display n
  end
end
```
## Exercise 3:-Write a pseudocode for checking whether given number is perfect number or not.
```
begin
    numeric number
    accept number
    numeric i=1
    numeric sum=0
    while(i<number)
    begin
    if(number%i == 0)
     begin
      sum=sum+i
     end
     i++
    end
    if(sum==number)
        display "Number is perfect number"
    else
        display "Number is not perfect number"
end
```
## Exercise 4:-Write a pseudocode for accepting three numbers and display the lowest number out of three numbers.
```
begin
numeric a,b,c
accept a,b,c
if(a<b)
 begin
  if(a<c)
   begin
    display a is lowest
    break;
   end 
   else if 
   begin
    display c is lowest
    break;
   end
 end    
  else if(b<c)
    display b is lowest  
   else 
    display c is lowest   
end 
```
## Exercise 5:-Write a pseudocode to swap two numbers without using third variable.
```
begin
numeric a,b
accept a,b
a=a+b
b=a-b
a=a-b
display a
display b
end
```
## Exercise 6:-Write a pseudocode for accepting a number and check whether number is perfect square or not.
```
begin
numeric n,s
accept n
 s=ān
if(s-āsā==0)
 display number is perfect square
 else
 display number is not perfect square
end 
```
## Exercise 7:-Write a pseudocode for accepting a number from 1 to 7 and display the name of the week.
```
begin
numeric n
accept n
 if(n==1)
  display Monday
  else if(n==2)
  display Tuesday
  else if(n==3)
  display Wednesday
  else if(n==4)
  display Thursday
  else if(n==5)
  display Friday
  else if(n==6)
  display Saturday 
  else if(n==7)
  display Sunday 
  else
  display Invalid input 
end
```
## Exercise 8:-Write a pseudocode for implementing the concept of menu driven calculator which will accept two numbers and perform the calculation based upon users choice like (+,-,*,/).
```
begin
character n
numeric a,b
display "Enter choice(+,-,*,/) which want to perform"
accept n
display "Enter two numbers"
accept a
accept b
if(n=='+')
 display a+b
 else if(n=='-')
 display a-b
 else if(n=='*')
 display a*b
 else if(n=='/')
 display a/b
 else 
 display invalid input 
end
```
## Exercise 9:-Write a pseudocode for accepting firstname,middlename and lastname from the user in three different variables and concatenate the first character of firstname with second character of middlename and third character of lastname.
```
begin
character f,m,l
display enter firstname
accept f
display enter middlename
accept m
display enter lastname
accept l
display append.lengthf(0)+append.lengthm(1)
+append.lengthl(2)
end
```
## Exercise 10:-Write a pseudocode for accepting a five digit number and check whether the number is palindrome or not.
```
begin
numeric a,b,c,d,e
accept a
accept b
accept c
accept d
accept e
if(a==e && b==d)
 display number is palindrome
 else
 display number is not palindrome
end 
```
## Exercise 11:-Write a pseudocode for displaying the list of prime numbers in given range.
```
Begin
Numeric n,i,j
accept n
 i=1
 flag=0
 j=4
while(i<n)
begin
  flag=0
 if(i==1)
 begin
    display"Prime number are 1 "
     else if(i==2) then
           display "2"
     else if(i==3)
           display"3"
     else if(i>3)
           for(j=2;j<i;j++)
            if(i%j==0)
            begin 
                  flag=1
                  break
            end 
             if(flag==0)
             begin
                display i
             end
  end
end
end
```
## Exercise 12:-Write a pseudocode to accept student Details like (StudentID, StudentName, StudentAge, Marks1, Marks2,Marks3) Calculate Total and Percentage. If percentage is greater than 50 then display āPASSā else display āFAILā.
```
begin
character si,sn,sa
numeric m1,m2,m3,total,percentage
display enter studentid
 accept si
display enter studentname
 accept sn
display enter studentage
 accept sa
display enter marks1.
 accept m1 
display enter marks2.
 accept m2  
display enter marks3.
 accept m3
total=m1+m2+m3
pecentage=(m1+m2+m3)/3.0
if(percentage>50)
 display "PASS"
else
 display "FAIL"
end
```