# Section 7 Challenge

Write a C++ program as follows:

Declare two empty vectors of integers named vector1 and vector2, respectively.

Add 10 and 20 to vector1 dynamically using push_back
Display the elements in vector 1 using the at() method as well as its size using the size() method

Add 100 and 200 to vector2 dynamically using push_back
Display the elements in vector2 using the at() method as well as its size using the size() method

Declare an empty 2D vector called vector_2d
Remember, that a 2D vector is a vector of vector<int>

Add vector1 to vector_2d dynamically using push_back
Add vector2 to vector_2d dynamically using push_back

Display the elements in vector_2d using the at() method

Change vector1.at(0) to 1000

Display the elements in vector_2d again using the at() method

Display the elements in vector1

What did you expect? Did you get what you expected? What do you think happened?

*I thought that I was going to get 1000 in the Vector_2d 0 1. However it remained at 10. So, this means that once we add another vector into the Vector_2d it no longer references the vector1.*