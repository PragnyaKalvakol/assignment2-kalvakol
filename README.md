# assignment2-kalvakol
# PRAGNYA #
#### CREAM STONE
Cream Stone is one of the most popular ice cream parlours Chain in India. ***Cream Stone Menu is filled with delicious ice cream***. It's made up of homemade waffles bowls and cones with different fusion falvors.
--------

# Way to my favourite place

1. Catch a flight to india
2. Go to Hyderabad
3. Then go to chaitanyapuri
4. There you find a place called creamstone

[me](https://github.com/PragnyaKalvakol/assignment2-kalvakol/blob/main/AboutMe.md)
-------
# Sports
I like playing sports such as batminton, basket ball, table tennis, cricket.
I would recommend these sports if someone asks me to.

---------------------------------------
|Name of the sport  | Location | Price|
|-------------------|----------|------|
|Batminton          |  Park    | 50$  |
|Basket ball        |Rec center| 30$  |
|Table tennis       |Rec center| 40$  |
|Cricket            |Ground    | 70$  |
-------------------------------------

--------------------------------------------------

# Quotes

>Gratitude is not only the greatest of virtues but the parent of all others.
 *- Marcus Tullius Cicero* 

 >Follow your bliss and the universe will open doors where there were only walls.
 *- Joseph Campbell*

 -------------------------------------------------------------
 # Algebra

In number theory, integer factorization is the decomposition of a composite number into a product of smaller integers. If these factors are further restricted to prime numbers, the process is called prime factorization.
When the numbers are sufficiently large, no efficient, non-quantum integer factorization algorithm is known.

[More information on Number of divisors / sum of divisors]<(https://en.wikipedia.org/wiki/Integer_factorization)>

```
vector<long long> trial_division1(long long n) {
    vector<long long> factorization;
   for (long long d = 2; d * d <= n; d++) {
       while (n % d == 0) {
           factorization.push_back(d);
           n /= d;
       }
   }
   if (n > 1)
      factorization.push_back(n);
    return factorization;
}
```

[More details](https://cp-algorithms.com/algebra/factorization.html)
