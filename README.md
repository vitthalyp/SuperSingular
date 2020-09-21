# SuperSingular
A collection of SAGE v8.7 notebooks that contain code either present in papers or referenced in them.    
   
   The [SIDH implementation notebook](https://github.com/vitthalyp/SuperSingular/blob/master/SIDH_Implementation.ipynb) implements the process described in the [SIDH protocol](https://eprint.iacr.org/2011/506.pdf).  
   
   The [Adaptive Attack notebook](https://github.com/vitthalyp/SuperSingular/blob/master/Adaptive_Attack.ipynb) presents a method to extract a user's static key by repeatedly querying the user with modified points. This method is detailed in [On The Security of Supersingular Isogeny Cryptosystems](https://eprint.iacr.org/2016/859.pdf) by Steven Galbraith, Christophe Petit, Barak Shani, and Yan Bo Ti. During the implementation of the attack, especially during the computation of the theta parameter, it was noted that SAGEMATH's method for computing square roots was a bottleneck. I sped this up by using the fact that <5,-5> generate the set of units of 2<sup>k</sup> for all k greater than 2, a fact I read from [Classical Introduction to Modern Number Theory](https://link.springer.com/chapter/10.1007/978-1-4757-2103-4_4) by Kenneth Ireland and Michael Rosen.  
     
