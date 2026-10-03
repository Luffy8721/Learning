# NUMBER THEORY
## Things to Remember in  this lecture
1. Divisibilty definition only and properties if u wanna save your brain power or nah if you can manifest them from thin air tremondous concentartion yet hearing things needed 
2. The FUNDAMENTAL THEOREM OF ARITHEMETIC for which i dont know proof and beware it says a **unique** construction of primes ofcourse after u sort it by any rule that is accepted as a rule  lets say ascending order a very powerful statement
## DIVISIBILITY
### DEFINITION
- An integer lets call it A is said to be divisible by an integer K if A = K.X where X is an **integer**
- This is denoted as K|A (K divides A) or A ⋮ K (A divisible by K )
### PROPERTIES
1. If an integer say A is divisible by K then for any integer say B A.B is divisible by K
  - proof :
    Given A = K.X  then we can say A.B = K.X.B So it means A.B is divisible by K as per defintion
2. If two integers say A and B is divisible an integer K then A +/- B is divisble by K
 - proof:
    Given A = K.X and B = K.Y then  A + B = K. (x+Y) so it means A+B is divisible by K same for -
3. If one integer say A is divisible a **positive** integer K and another integer say B is not divisble by K then A+/-B is not divisible by K
 -proof:
   Given A = K.X and B = K.Y + d here d can be made such that d>0 and d < K so now A+B is K.(X+Y) + d so its impossible to make A+B as something like K.Z you can proove it by contradiction as it would mean d to be a multiple of K hence we can say A+B is not divisible by K
4. If two integers say A and B is not divisible by a **positive** integer K then A+/-B may or maynot be divisible by K 
 - proof:
     Given A= K.X + d1 and B= K.Y + d2 so lets say A+B then its K.(X+Y) +d1+d2 we may have d1+d2 multiple of K more specifically equal to K or 0 so its not certain same for -

#### Things to remember here
 1. ** ONLY the definition of divisibilty is enough ** But good to have some knowledge of properties 

## FUNDAMENTAL THEOREM OF ARITHMETIC
- Prime a **positive integer** is a prime if it is divisible by 1 and itself only .
- How to check if its a prime well see lets say the number be called x then for any integer greater than x say y it will not divide x why? cause if it does we mean y.some integer is x which doesnt hold as no will be greater than x and so search space to see is from 1 to x now if u dont find any numiber dividing x in ceil(sqrt(x)) no point in checking rest so search space is reduced ! why sqrt(x) cause if lets say both numbers making x be gretae than it it means we cross x 
- ** Any integer say N >1 can be written as product of primes such that the power of the primes is an positive integer and the prime factorisation is unique if we sort the primes order **
- proof:
   I dont Know yet ! (ASK mam or internalize it as an axiom)
- ALGORITHM:
   order ={}
   while N is not 1
      for K=2 to infinity (doesnt matter as N will be 1 any way)
         while K| N  
           N = N/K
           add K to order.
### PROPERTIES
1. A positive integer lets say A is divisible by a postive integer M if and only if every prime divisor of M divides A and also every prime divisor has its exponnet in M atmost to that of in A
 - proof :
   Given A = M . K Then by FUNDAMENTAL THEOREM OF ARITHMETIC uniquely in sorted order of primes we can write A = p1.p1.p2.p2.p3....
   and M = p'1.p'1.p'2.p'2....... then so for every prime divisor of M say p'1 it is can be rewritten as A = (p'1) .rest so p'1|A 
2. If a positive integer is divisible by coprime positive integers m and n, then it is divisible by their product mn
 -proof :
    You do 
3. If for positive integers a,b,c the product ab is divisible by c anda and c are coprime, then b is divisible by c.

#### Things to remember here 
 1. THE Theorem for which i dont know proof and be where of the theorem it says a unique construction a very powerful statment