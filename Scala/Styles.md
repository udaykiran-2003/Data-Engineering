Styles: It refer to different ways of writing scala program.
It is based on various programming paradigms supported by language.

1. Functional Style
2. Object-Oriented Style
3. Pattern-Matching Styles
4. For-Comprehensions
val num = List(1,2,3,3,4,5,6,7,9)
val result = for {
  n <- num
  squared = n * n
} yield squared
println(result)

5. If-Comprehension 
6. Type Class
6. Traits and Mixins
7. Imperative Styles