# dslsofmath-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [DSLsofMath Assignment 1 Solved](https://www.ankitcodinghub.com/product/dslsofmath-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98682&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSLsofMath Assignment 1 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
1

In this assignment the focus is on the following three learning outcomes:

• organize areas of mathematics in DSL terms

• develop adequate notation for mathematical concepts

• discuss and compare different software implementations of mathematical concepts

1.1 DSLs, sets and von Neumann

In this assignment you will build up a domain-specific language (a DSL) for finite sets. The domain you should model is pure set theory where all members are sets.

Define a datatype TERM v for the abstract syntax of set expressions with variables of type v and a datatype PRED v for predicates over pure set expressions.

Part 1. TERM should have constructors for

• the Empty set

• the one-element set constructor Singleton • Union, and Intersection

– you can also try Powerset

• set-valued variables (Var :: v → TERM v )

PRED should have contructors for

• the two predicates Elem, Subset

• the logical connectives And, Or, Implies, Not

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Part 2. A possible semantic domain for pure sets is newtype Set = S [Set ]

Implement the evaluation functions

eval ::Eq v ⇒Env v Set →TERM v →Set check :: Eq v ⇒ Env v Set → PRED v → Bool

type Env var dom = [(var,dom)]

Note that the type parameter v to TERM is for the type of variables in the set expressions, not

the type of elements of the sets. (You can think of pure set theory as “untyped” or “unityped”.)

Part 3. The von Neumann encoding of natural numbers as sets is defined recursively as

vonNeumann 0 = Empty

vonNeumann (n + 1) = Union (vonNeumann n)

(Singleton (vonNeumann n))

Implement vonNeumann and explore, explain and implement the following “pseudocode” claims

as functions in Haskell:

claim1 n1 n2 = {- if (n1 􏰀 n2 ) then (n1 ⊆ n2 ) -}

claim2 n = {- n = { 0, 1, …, n − 1 } -}

You need to insert some embeddings and types and you should use the eval and check functions. (For debugging it is useful to implement a show function for Set which uses numerals to show the von Neumann naturals.)

</div>
</div>
</div>
