# tupper-self-referential-formula

I tried to do the Tapper's Self-Referential formulation in perl.

<img src="https://wikimedia.org/api/rest_v1/media/math/render/svg/2c74e5046994470b148f2e386aebd1f12baa88a8">  
<pre>
1/2 < floor(mod(floor(y/17)*2^(-17*floor(x)-mod(floor(y),17)),2))  
</pre>
<pre>
k=960939379918958884971672962127852754715004339660129306651505519271702802395266424689642842174350718121267153782770623355993237280874144307891325963941337723487857735749823926629715517173716995165232890538221612403238855866184013235585136048828693337902491454229288667081096184496091705183454067827731551705405381627380967602565625016981482083418783163849115590225610003652351370343874461848378737238198224849863465033159410054974700593138339226497249461751545728366702369745461014655997933798537483143786841806593422227898388722980000748404719
</pre>
<img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Tupper%27s_self_referential_formula_plot.png"> (wikipedia)  

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







