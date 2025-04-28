# sta4102-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [STA4102 Assignment #2 Solved](https://www.ankitcodinghub.com/product/assignment-2-sta410h1f-2102h1f-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117146&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA4102 Assignment #2  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (1 vote)    </div>
    </div>
Instructions: Solutions to problems 1 and 2 are to be submitted on Quercus (PDF files only). You are strongly encouraged to do problems 3–6 but these are not to be submitted for grading.

1. An interesting variation of rejection sampling is the ratio of uniforms method. We start by taking a bounded function h with h(x) ≥ 0 for all x and . We then define the region

and generate (U,V ) uniformly distributed on Ch. We then define the random variable X = V/U.

(a) The joint density of (U,V ) is

for (u,v) ∈ Ch

where |Ch| is the area of Ch. Show that the joint density of (U,X) is

q

for 0 ≤ u ≤ h(x)

and that the density of X is γ h(x) for some γ &gt; 0.

(b) The implementation of this method is somewhat complicated by the fact that it istypically difficult to sample (U,V ) from a uniform distribution on Ch. However, it is usually possible to find a rectangle of the form Dh = {(u,v) : 0 ≤ u ≤ u+,v− ≤ v ≤ v+} such that Ch is contained within Dh. Thus to draw (U,V ) from a uniform distribution on Ch, we can use rejection sampling where we draw proposals (U∗,V ∗) from a uniform distribution on the rectangle Dh; note that the proposals U∗ and V ∗ are independent random variables with Unif(0,u+) and Unif(v−,v+) distributions, respectively. Show that we can define u+, v− and v+ as follows:

q q q u+ = max h(x) v− = minx h(x) v+ = maxx h(x). x x x

(Hint: It suffices to show that if (u,v) ∈ Ch then (u,v) ∈ Dh where Dh is defined using u+, v−, and v+ above.)

(c) Implement (in R) the method above for the standard normal distribution taking h(x) =

exp(−x2/2). In this case, u+ = 1, v− = −q2/e = −0.8577639, and v+ = q2/e = 0.8577639.

What is the probability that proposals are accepted?

2. Suppose we observe y1,···,yn where

yi = θi + εi (i = 1,···,n)

where {εi} is a sequence of random variables with mean 0 and finite variance representing noise. We will assume that θ1,···,θn are smooth in the sense that θi = g(i) for some continuous and differentiable function g. The least squares estimates of θ1,···,θn are trivial — for all i — but we can modify least squares in a number of ways to accommodate the “smoothness” assumption on {θi}. In this problem, we will consider estimating {θi} by minimizing

n n−1

X 2 X 2

(yi − θi) + λ (θi+1 − 2θi + θi−1)

i=1 i=2

where λ &gt; 0 is a tuning parameter that controls the smoothness of the estimates . (This method is known as Whittaker graduation in actuarial science and the HodrickPrescott filter in economics.)

(a) Show that if {yi} are exactly linear, i.e. yi = a × i + b for all i then for all i.

(b) In principal, we could compute θb1,···,θbn using ordinary least squares estimation. Show

that minimizes

ky∗ − Xθk2

where y∗ is a vector of length 2n−2 and X is an (2n−2)×n matrix. What are y∗ and X?

(c) When n is large, computing directly, for example, using the OLS formulation in part (b) is computationally expensive when n is large. Alternatively, we could use the Gauss-Seidel algorithm but it converges slowly, particularly for larger values of λ. One possible alternatively is a randomized modification of the Gauss-Seidel algorithm, which at each stage solves a ) variable least squares problem.

The basic algorithm is as follows:

0. Initialize θb.

1. Randomly sample a subset w of size p from the integers 1,···,n. Define Xw to be the submatrix of X with column indices w and Xw¯ to be the submatrix of X with column indices in the complement of w; define θw and θw¯ analogously so that Xθ = Xwθw + Xw¯θw¯.

2. Define to minimize

with respect to θw.

3. Repeat steps 1 and 2 until convergence.

Show that the objective function is non-increasing from one iteration to the next.

(d) On Quercus, there is a function HP in a file HP.txt, which implements the randomized block Gauss-Seidel algorithm outlined in part (c). This function can be used as follows

&gt; r &lt;- HP(x,lambda=2000,p=20,niter=100)

where lambda is the value of λ, p is the value of p, and niter specifies the number of iterations of the algorithm. The output of the function (contained here in r) consists of two components: the estimates of {θ} in r$xhat and the values of the objective function for each iteration in r$ss.

Use this function (with λ = 2000) on data on monthly yields on short-term British securities over a 21 year period (252 months). Try out various values of p between 5 and 50 (using 1000 iterations). Describe how the objective function decreases with each iteration as p varies between 5 and 50.

(e) (Optional) Methods such as the randomized block Gauss-Seidel algorithm are essentialin problems where the number of unknown parameters is extremely large. The goal is not to minimize the objective function but merely to find a solution that’s close to the minimum. In the context of the randomized block Gauss-Seidel algorithm, what factors should you consider in choosing p, the numbers of parameters being optimized at each step? Keep in mind that for least squares, the number of floating point operations needed increases with p like p2.

Supplemental problems (not to hand in):

3. To generate random variables from some distributions, we need to generate two independent two independent random variables Y and V where Y has a uniform distribution over some finite set and V has a uniform distribution on [0,1]. It turns out that Y and V can be generated from a single Unif(0,1) random variable U.

(a) Suppose for simplicity that the finite set is {0,1,···,n − 1} for some integer n ≥ 2. For

U ∼ Unif(0,1), define

Y = bnUc and V = nU − Y

where bxc is the integer part of x. Show that Y has a uniform distribution on the set {0,1,···,n − 1}, V has a uniform distribution on [0,1], and Y and V are independent.

(b) What happens to the precision of V defined in part (a) as n increases? (For example, if U has 16 decimal digits and n = 106, how many decimal digits will V have?) Is the method in part (a) particularly feasible if n is very large?

Suppose we want to generate a continuous random variable from a density f(x) and that f(x) = f1(x) + f2(x) (where both f1 and f2 are non-negative) where f1(x) ≤ g(x) for some density function g. Then the A-C method works as follows:

1. Generate two independent random variables U ∼ Unif(0,1) and X with density g.

2. If U ≤ f1(X)/g(X) then return X.

3. Otherwise (that is, if U &gt; f1(X)/g(X)) generate X from the density

.

Note that we must be able to easily sample from g and in order for the A-C method to be efficient; in some cases, they can both be taken to be uniform distributions.

(a) Show that the A-C method generates a random variable with a density f. What is the probability that the X generated in step 1 (from g) is “rejected” in step 2?

(b) Suppose we want to sample from the truncated Cauchy density

using the A-C method with f2(x) = k, a constant, for −1 ≤ x ≤ 1 (so that 2 is a uniform density on [−1,1]) with

f1(x) = f(x) − f2(x) = f(x) − k (−1 ≤ x ≤ 1).

If g(x) is also a uniform density on [−1,1] for what range of values of k can the A-C method be applied?

(c) Defining f1, f2, and g as in part (b), what value of k minimizes the probability that X generated in step 1 of the A-C algorithm is rejected?

5. Suppose we want to generate a random variable X from the tail of a standard normal distribution, that is, a normal distribution conditioned to be greater than some constant b. The density in question is

for x ≥ b

with f(x) = 0 for x &lt; b where Φ(x) is the standard normal distribution function. Consider rejection sampling using the shifted exponential proposal density

g(x) = bexp(−b(x − b)) for x ≥ b.

(This proposal density is used by the Monty Python algorithm to sample from the tail of the normal distribution.)

(a) Define Y be an exponential random variable with mean 1 and U be a uniform random variable on [0,1] independent of Y . Show that the rejection sampling scheme defines X = b + Y/b if

.

(Hint: Note that b + Y/b has density g.)

(b) Show the probability of acceptance is given by

.

What happens to this probability for large values of b? (Hint: You need to evaluate M = maxf(x)/g(x).)

(c) Suppose we replace the proposal density g defined above by

gλ(x) = λexp(−λ(x − b)) for x ≥ b.

(Note that gλ is also a shifted exponential density.) What value of λ maximizes the probability of acceptance? (Hint: Note that you are trying to solve the problem

for λ. Because the density gλ(x) has heavier tails, the minimax problem above will have the same solution as the maximin problem

6. (a) Suppose that E1,E2,··· are independent Exponential random variables with density f(x) = λexp(−λx) for x ≥ 0. Then the distribution of Tk = E1 + ··· + Ek is a Gamma

distribution whose density is

for x ≥ 0.

Show that

(Hint: Use integration by parts.)

(b) How might you use the result of part (a) to generate random variables from a Poisson distribution with mean λ?
