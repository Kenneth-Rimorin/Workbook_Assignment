# Q1
# Q2
# Q3
# Q4
# Q5
# Q6
# Q7
# Q8
# Q9
# Q10
# Q11
# Q12
Problem : The problem with the code is the user input is being interpretted as a string.
```
celsius = gets
fahrenheit = (celsius * 9 / 5) + 32
print "The result is: "
print fahrenheit
puts "."
```
Solution : The solution should put ".to_i" method after the gets method in celsius variable, to return the value of the user input as an integer. 
```
celsius = gets.to_i
fahrenheit = (celsius * 9 / 5) + 32
print "The result is: "
print fahrenheit
puts "."
```

 
# Q13
# Q14
# Q15
# Q16