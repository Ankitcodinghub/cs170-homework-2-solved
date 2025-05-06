# cs170-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [CS170 Homework 2 Solved](https://www.ankitcodinghub.com/product/cs170-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96682&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS170 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

List the names and SIDs of the members in your study group. If you have no collaborators, write “none”.

2 Asymptotic Properties

Provide a proof of each of the following properties of Θ: (a) For all fixed c &gt; 0, 􏰅ni=1 ic = Θ(nc+1).

(b) Consider 􏰅ni=0 αi, where α is a constant. Three different things may happen, depending on the value of α:

(i) Show that if α &gt; 1, 􏰅ni=0 αi = Θ(αn). (ii) Show that if α = 1, 􏰅ni=0 αi = Θ(n).

(iii) Showthatif0&lt;α&lt;1,􏰅ni=0αi =Θ(1). 3 Median of Medians

The Quickselect(A, k) algorithm for finding the kth smallest element in an unsorted array A picks an arbitrary pivot, then partitions the array into three pieces: the elements less than the pivot, the elements equal to the pivot, and the elements that are greater than the pivot. It is then recursively called on the piece of the array that still contains the kth smallest element.

<ol>
<li>(a) &nbsp;Consider the array A = [1, 2, . . . , n] shuffled into some arbitrary order. What is the worst-case runtime of Quickselect(A, n/2) in terms of n? Construct a sequence of ‘bad’ pivot choices that achieves this worst-case runtime.</li>
<li>(b) &nbsp;The above ‘worst case’ has a chance of occurring even with randomly-chosen pivots, so the worst-case time for a random-pivot Quickselect is O(n2).
Let’s define a new algorithm Better-Quickselect that deterministically picks a better pivot. This pivot-selection strategy is called ‘Median of Medians’, so that the worst-case runtime of Better-Quickselect(A, k) is O(n).
</li>
</ol>
</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Median of Medians

1. Group the array into ⌊n/5⌋ groups of 5 elements each (ignore any leftover elements)

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>Find the median of each group of 5 elements (as each group has a constant 5 elements, finding each individual median is O(1))</li>
<li>Create a new array with only the ⌊n/5⌋ medians, and find the true median of this array using Better-Quickselect.</li>
<li>Return this median as the chosen pivot</li>
</ol>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Let p be the chosen pivot. Show that for least 3n/10 elements x we have that p ≥ x, and that for at least 3n/10 elements we have that p ≤ x.

(c) Show that the worst-case runtime of Better-Quickselect(A, k) using the ‘Median of Medians’ strategy is O(n).

Hint: Using the Master theorem will likely not work here. Find a recurrence relation for T (n), and try to use induction to show that T (n) ≤ c · n for some c &gt; 0.

4 Werewolves

You are playing a party game with n other friends, who play either as werewolves or citizens. You do not know who is a citizen and who is a werewolf, but all your friends do. There are always at least two more citizens than there are werewolves.

Your goal is to identify one player who is certain to be a citizen.

Your allowed ‘query’ operation is as follows: you pick two people. You ask each person if their partner is a citizen or werewolf. When you do this, a citizen must tell the truth about the identity of their partner, but a werewolf doesn’t have to (they may lie or tell the truth about their partner).

Your algorithm should work regardless of the behavior of the werewolves.

(a) Show how to solve this problem in O(n log n) queries (where one query is asking a pair of people to identify the other person).

You cannot use a linear-time algorithm here, as we would like you to get practice with divide and conquer.

Give a 3-part solution.

(b) (Extra Credit) Can you give a linear-time algorithm? Give a 3-part solution.

5 Hadamard matrices

The Hadamard matrices H0, H1, H2, . . . are defined as follows: 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
&nbsp;􏰎 H0 is the 1×1 matrix [1]

􏰎 Fork&gt;0,Hk isthe2k × 2k matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
(a) (b)

</div>
<div class="column">
Write down the Hadamard matrices H0, H1, and H2.

Compute the matrix-vector product H2 · v where H2 is the Hadamard matrix you found

</div>
</div>
<div class="layoutArea">
<div class="column">
(c)

(d)

(e)

</div>
<div class="column">
Note that since H2 is a 4 × 4 matrix, and the vector has length 4, the result will be a vector of length 4.

Now, we will compute another quantity. Take v1 and v2 to be the top and bottom halves of v respectively. Therefore, we have that

􏰏1􏰐 􏰏−1􏰐 􏰏v1􏰐 v1=−1,v2= 1 ,v=v2

Compute u1 = H1(v1 + v2) and u2 = H1(v1 − v2) to get two vectors of length 2. Stack u1 above u2 to get a vector u of length 4. What do you notice about u?

Suppose that

􏰏v1 􏰐 v= v2

is a column vector of length n = 2k. v1 and v2 are the top and bottom half of the vector, respectively. Therefore, they are each vectors of length n2 = 2k−1. Write the matrix-vector product Hkv in terms of Hk−1, v1, and v2 (note that Hk−1 is a matrix of dimension n2 × n2, or 2k−1 ×2k−1). Since Hk is a n×n matrix, and v is a vector of length n, the result will be a vector of length n.

Use your results from (c) to come up with a divide-and-conquer algorithm to calculate the matrix-vector product Hkv, and show that it can be calculated using O(nlogn) operations. Assume that all the numbers involved are small enough that basic arithmetic operations like addition and multiplication take unit time. You do not need to prove correctness.

</div>
</div>
<div class="layoutArea">
<div class="column">
above, and

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰏 Hk−1 Hk−1 􏰐 Hk = Hk−1 −Hk−1

</div>
</div>
<div class="layoutArea">
<div class="column">
1 v = −1

−1 1

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
6 Warmup: FFT

The n-th roots of unity are the n complex numbers ω such that ωn = 1. They are: e2πik/n, k = 0, 1, 2, . . . , n − 1

(a) Find an n-th root of unity ω such that for all n-th roots of unity z, z = ωk. In other words, find an ω such that all n-th roots of unity are powers of ω.

(b) Show that the squares of the 2n-th roots of unity are the n-th roots of unity.

Hint: This requires showing two things: (1) the square of every 2n-th root of unity is an n-th root of unity, and (2) every n-th root of unity is the square of some 2n-th root of unity.

(c) For a given n-th root of unity ω = e2πik/n, determine all of the 2n-th roots of unity whose squares are ω.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
