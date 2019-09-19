# SuperSingular
A collection of SAGE v8.7 notebooks that contain code either present in papers or referenced in them.  

The Karatsuba notebook has code that uses 256 as its base, referenced in [Efficient algorithms for supersingular isogeny Diffie-Hellman](https://eprint.iacr.org/2016/413.pdf) by Craig Costello, Patrick Longa, and Michael Naehrig.    

The Three point montgomery ladder notebook has an implementation of the the algorithm of the same name mentioned in [Towards Quantum-Resisitant Cryptosystems  From Supersingular Elliptic Curve Isogenies](https://eprint.iacr.org/2011/506.pdf) by David Jao, Luca De Feo, and Jerome Plut. It is implemented over an elliptic curve with a j-invariant of unity over the finite field with a cardinality of 10354717741769305252977768237866805321427389645549071170116189679054678940682478846502882896561066713624553211618840202385203911976522554393044160468771151816976706840078913334358399730952774926980235086850991501872665651576831.   
(A prime field mentioned in [NEON-SIDH: Efficient Implementation of Supersingular Isogeny Diffie-Hellman Key Exchange Protocol on ARM](https://eprint.iacr.org/2016/669.pdf) by Brian Koziel, Amir Jalali, Reza Azaderakhsh, David Jao, Mehran Mozaffari-Kermani.)  

The Okeya Sakurai notebook has the implementation of the process of the same name mentioned in [Efficient Elliptic Curve Cryptosystemsfrom a Scalar Multiplication Algorithmwith Recovery of they-Coordinateon a Montgomery-Form Elliptic Curve](https://link.springer.com/content/pdf/10.1007/3-540-44709-1_12.pdf) by Katsuyuki Okeya and Kouichi Sakurai. It is implemented  over the same elliptic curve mentioned in the Montgomery ladder notebook, however it is over the quadratic extension of the above field. The idea of the distortion map was from [Efficient algorithms for supersingular isogenyDiffie-Hellman](https://eprint.iacr.org/2016/413.pdf) by Craig Costello, Patrick Longa, and Michael Naehrig.  
  
 The Isogeny Calculation notebook computes large smooth order isogenies using the initial method presented in [Towards Quantum-Resisitant Cryptosystems  From Supersingular Elliptic Curve Isogenies](https://eprint.iacr.org/2011/506.pdf), a paper by David Jao, Luca De Feo and Jerome Plut. This scheme is not optimal as it does not employ the optimizations suggested in the later sections of the paper. For completeness, the scheme has been implemented.  
   
   The SIDH implementation notebook uses all of the above notebooks to complete the process described in the [SIDH protocol](https://eprint.iacr.org/2011/506.pdf).
