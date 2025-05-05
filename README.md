# cs401-homework-6-range-only-based-localization-solved
**TO GET THIS SOLUTION VISIT:** [CS401 Homework 6-Range-only based localization Solved](https://www.ankitcodinghub.com/product/cs401-homework-6-range-only-based-localization-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99130&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS401 Homework 6-Range-only based localization Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Range-only based localization

Coding Homeworks. Your final submission should be a compressed package with extension .zip, which includes your codes and explanations (you need to know how to write the manuscript with Markdown or LATEX). Your code should be run step-by-step without any error. Real-time animation is also recommended.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Overview

Range only based localization is the technique of using only distance measurements from stations to determine the location of a target, with no information about the direction from which this distance was measured. Given a coordinate and a measured distance, the set of all points for which the target could be located forms a circle; the coordinate is the circle center and the distance is the circle radius. It is a classic problem in navigation and target tracking, and also applicable to problems such as using time-domain reflectometry to determine locations of faults in modem connections.

For example, a GPS receiver uses trilateration (a type of range only based localization algorithms) to determine its exact location from its measured distances from at least three satellites, each satellite is at the center of a sphere and where they all intersect is the position of the GPS receiver.

For detail of GPS localization, please refer to How GPS Receivers Work – Trilateration vs Triangulation.

Localization of a single target

To simplify the problem, here we only consider the location in the two-dimensional plane.

We simulates an 802.11az network consisting of a station (STA) and multiple access points (APs). With only one station (STA), there are infinitely many points on the circle where the targets could be located. With two stations whose distance circles intersect, the possible target location is reduced down to two possible points. With three or more stations that intersect at a single point, the target location can be isolated to that point.

Thus, to estimate the position of a STA, the network requires a minimum of three APs.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
file:///private/var/folders/tg/tgc3_g1x6mv153n6fbqclbxw0000gp/T/mume2022221-1370-1oqlnzq.a3tl.html 1/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
3/21/22, 2:53 PM readme

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
The following demo simulates a ranging measurement exchange for each STA-AP pair, then trilaterates the position of the STA by using these distance measurements.

Suppose the known coordinates of AP1, AP2 and AP3 are and

, respectively.

Also, the calculated distances from AP1, AP2, and AP3 to the STA are

and

, respectively.

Question 1

How to calculate the exact position

of the STA in the current coordinte space?

Note1: Linear least square method can be used to solve the problem analytically.

Mathematical Derivation

The distance equations between known APs and unknown STA are as following:

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
file:///private/var/folders/tg/tgc3_g1x6mv153n6fbqclbxw0000gp/T/mume2022221-1370-1oqlnzq.a3tl.html 2/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
3/21/22, 2:53 PM readme

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
As we can see these equations are nonlinear, and we substract the third equation from the first and second equations, after that we can can obtain a linear equation:

where

,

and

Least square method can be used to solve this linear equation and the solver is:

Question2

However, even with accurate sensors, it is unlikely that three circles would intersect at exactly the same point at which the STA is located. This means that attempts to tackle this problem analytically will almost always fail. Instead, an optimization-based approach can be used; it infers the STA’s location by finding the point which minimizes the squared euclidean distances between the STA and all the APs.

Please formulate an error function which calculates the euclidean distance between the STA and all APs:

where

is the total number of APs.

Question3

This problem is not convex. It is also worth noting that gradeint-based optimization methods such as Gauss-Newton(GN) and Levenberg–Marquardt (LM) algorithm used require a Jacobian (gradient) function. Thus, in this homework, we solve the problem using numerical optimization methods which are derivative-free methods. For example, Covariance matrix adaptation evolution strategy (CMA-ES) which uses the principle of biological evolution, namely the repeated interplay of variation (via recombination and mutation) and selection: in each generation (iteration) new individuals (candidate solutions) are generated by variation, usually in a stochastic way, of the current parental individuals. Then, some individuals are selected to become the parents in the next generation based on their fitness or objective function value. Like this, over the generation sequence, individuals with better

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
file:///private/var/folders/tg/tgc3_g1x6mv153n6fbqclbxw0000gp/T/mume2022221-1370-1oqlnzq.a3tl.html 3/4

</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
3/21/22, 2:53 PM readme

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
and better function values are generated.

Please use CMA-ES algorithm to solve the localization problem, you can refer to the usage of CMA- ES in python from the link.

Code for questions

Note1: The question one is simple, please finish the function code in trilateration.py by refering to

the above mathematical derivation.

Note2: Given the coordinates of a finite number of radio stations, and given their distances to the source (derived from the intensities of the signal they received in a previous step) computes the most probable coordinates of the source, please complete the quadratic function (the error function formulation) in distance_only_localization.py.

Note3: Please complete the optimization section of main function in the file distance_only_localization.py

</div>
</div>
</div>
</div>
</div>
