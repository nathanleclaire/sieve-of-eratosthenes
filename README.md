# Sieve of Eratosthenes

This is an implementation of the [Sieve of Eratosthenes](http://en.wikipedia.org/wiki/Sieve_of_Eratosthenes) in C.  I originally wrote something similar in PHP for an interview question and found it to be a fun little exercise.  PHP was going painfully slow for values greater than 10000 or so, so I decided to get closer to the metal.

# Usage

Usage is fairly straightforward.  Invoke the executable from the command line with an argument indicating the number to calculate up to.

    ./primes 1000

will calculate all the primes up to 1000.