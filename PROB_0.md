# Strictly Increasing
Given an array, determine if the array is strictly increasing with up to 3 exceptions.

def strictIncrExc(array);  
  countEx = 0;  
  last = -1  
  for i in array:  
    if last > 1  
      countEx += 1  
    if countEx > 3  
      return false  
    last = i  
  return true  
