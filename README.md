# What I learned Week 7

During week 7 we went over string building and mapping arrays.

String building is taking strings and making changes to them and then placing them into a new string. Reason for this is because strings are immutable meaning you can't technically change them once made. So with this process we can make what changes what want to them but have to create a new string in the process.

Array mapping is similar but has some different processes. Heres a come difference when it comes to creating a new copy.

String building result goes like this:
result = result + str[i]

For arrays we push the results in like this:
result.push(arr[i] + '!')

Below are a couple syntaxes that were used during the assignments.

- Math.Abs() - Function returns the absolute value of a number.
- Slice() - Method returns a shallow copy of a portion of an array into a new array object selected from start to end (end not included) where start and end represent the index of items in that array. The original array will not be modified.
