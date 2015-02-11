##Descriptions of Iterators

###Instructions
Below you will find a list of methods. In the space provided below each, please provide a brief description of what this method does based upon your review of the Docs. 

###Array methods:
May be helpful to look in [Enumerable](http://ruby-doc.org/core-2.2.0/Enumerable.html) as well...

####select:
Returns new array with elements that return true when executing the block
####reject:
Returns array with the values that return false when running the block
####map:
Creates new array with all the elements affected by the block
####detect:
Returns the first element that meets the condition
####inject:
Reduces all the elements to one by executing the block
####partition:
Creates a new array with two partions, showing at first the array that meets the condition
####sort:
Organizes the array from lowest to highest or alphabetically when elements are strings
####one:
returns true if at least one element meets the condition
####none:
Returns true if none of the elements meets the condition
####all:
Returns true if the condition passes at all elements in the array
####empty?:
Returns true if the array is empty
####eql?:
Returns true if two arrays are equal
####include?:
Returns true if the array includes the parameter
####nil?:
returns true when the variable or parameter is equal to nil
###Hash methods:

####has_key?:
return true if hash contains a key
####keys:
should return array with all the keys
####delete:
return new hash without the value of key that is deleted
####delete_if:
