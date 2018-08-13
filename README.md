# Session-5.2-assignment-rahul-sharma
Acagild session 5.2 assignment

1. Obtain the elements of the union between two character vectors.

vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[10:32,]))

Ans 1 ->

union(vec1, vec2)


2. Get those elements that are common to both vectors.

vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[10:32,]))

Ans 2 ->

intersect(vec1, vec2)


3. Get the difference of the elements between two character vectors.

vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[10:32,]))

Ans 3 ->

setdiff(vec1, vec2)

setdiff(vec2, vec1)


4. Test the equality of two character vectors.

vec1 = c(rownames(mtcars[1:15,]))

vec2 = c(rownames(mtcars[11:25,])) 

Ans 4 ->

setequal(vec1, vec2)
