# tupper-self-referential-formula

I tried to do the tapper self-referential formulation in perl.

<img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Tupper%27s_self_referential_formula_plot.png"> (wikipedia)  
<pre>
1/2 < floor(mod(floor(y/17)*2^(-17*floor(x)-mod(floor(y),17)),2))  
</pre>
## Usage
perl taptest.pl

# Requirement
use Math::BigInt;

## Execution
<pre>
        *                   *                * ** *     *                *  * *     *    * ** *      *   *
         *                   * *      *       *  * *     *                *  * *     *    *  * *      *   *
 **      *                  *  *      *    ** *  * * * * * ** ****  *** *** *  * * * *    *  *  *      *  *
  *      *                  *  *  * * *       * *  *  *  *    * * * * * * * *  * * * *    * *   *      *  *
  *      *                  *  *  * * *       * *  * * * *    * * * *** *** *  *  *  *    * *   *      *  *
  *      *               * *   *   *  *  **        *     *                  *  * *   *  *       *   **  * *
 ***   * *               * *   *  *   * *  *       *     *                   * *     *  *      *   *  * * *
      *  * ** *   **   *** *   *      *   *        *** ***                   * *** *** *       *     *  * *
 *** *   * * * * *  * *  * *   * **** *  *                                                          *   * *
      *  * * * * *  * *  * *   *      * *                                                          *    * *
 **    * * * * *  **   *** *   * * ** * ****                                                       **** * *
   *     *                 *   * *  * *                                                          *      * *
  *      *                  *  * *  * *                                                          *     *  *
 *       *                  *  * * *  *                                                         *      *  *
 ***     *                  *  * * *  *                                                                *  *
         *                   * *      *                                                               *   *
         ***                 * ***  ***                                                               * ***
</pre>

## Author  
PicoLix Design / Naeba [Twitter nae2sho](https://twitter.com/nae2sho)







