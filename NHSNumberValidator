test_nhs = "6080491923"
test_digit = (int(test_nhs[9:10]))

nhs = test_nhs[:-1] #"608049192" # check digit should be 3
#print nhs


#print test_digit
total = 0

for (index, value) in enumerate(nhs):
 #print (index, value)
 multiply_value = 10 - index


 result = int(value) * multiply_value

 total = total + result
 #print (index, value, multiply_value, result)

#print (total)

remainder = total % 11

check_digit = 11 - remainder

# print (remainder)
#print (check_digit)

if check_digit == test_digit:
 print "Valid NHS Number"
else:
 print "Invalid NHS Number"
