# csed332-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CSED332 Assignment 2 Solved](https://www.ankitcodinghub.com/product/csed332-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115989&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED332&nbsp;Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

Objectives

• Unit testing and coverage

• Maven (adding dependencies to pom.xml)

• Learn Java programming language

Maven and Testing

• Your code need to be compiled using only Maven in a command line for grading. Unlike the previous assignment, your pom.xml must be modified to include extra dependencies.

• Maven can generate coverage reports using JaCoCo plugin. We have already added this plugin in pom.xml (see the provided pom.xml and understand how the plugin is added to the build).

• To run your tests with JaCoCo and produce code coverage results, you can go to where your pom.xml is and execute the following commands: mvn test and mvn jacoco:report.

• The command mvn jacoco:report generates human readable reports of coverage information of your unit tests. The reports will be stored in the target/site/jacoco directory.

• You MUST ensure that your tests pass on your code. You will get overall 0 points if your submitted code and tests do not work with mvn test.

Problem 1

• The goal of this problem is to create a library management application with unit tests, to evaluate quality of these tests, and to automate build.

• You will create a simple model for this library application, including books and collections (see the skeleton code for more details).

– Books are organized in collections.

– A book can be added or removed from a collection.

– A collection contains a various number of books, and can also contain other sub-collections.

For example, a collection Computer Science can contain a series of books about computer science in general and other sub-collections such as Operating System, Software Verification, etc.

• Books, collections, and libraries can be exported to or imported from a file in the JSON format (see https://www.json.org).

• You will have to write at least one (separate) JUnit test for each method of the classes Book, Collection, and Library in the corresponding test classes.

– Each test method should test a single behavior with appropriate assertions. Do not write a single method that checks multiple behaviors.

– Your submitted tests need to achieve at least 80% statement coverage (instruction coverage for JaCoCo). Do not add arbitrary code to your test method to just increase coverage.

Problem 2

• The goal of this problem is to implement several functions for Boolean expressions. The syntax of Boolean expressions is given as follows:

Boolean formula φ ::= c | v | ! φ | φ &amp;&amp; φ | φ || φ

Boolean constant c ::= true | false

Boolean variable v ::= p1 | p2 | p3 | ···

A Boolean expression is constructed by constants (true and false), variables of the form pi for natural number i &gt; 0, and logical operators such as ! (negation), &amp;&amp; (and), and || (or).

– We provide a parser for Boolean expressions using ANTLR4 (https://www.antlr.org), but you must modify your pom.xml to include extra dependencies for ANTLR4 (antlr4-runtime).

• A Boolean expression e evaluates to a truth value (either true or false), given a truth assignment that assign a truth value to each Boolean variable in the expression e.

– For example, the expression (p1 || p2) &amp;&amp; (p2 || ! p3) evaluates to true, given the truth assignment {p1 →7 true, p2 7→ false, p3 7→ false}.

• We can simplify a Boolean expression into an equivalent expression by logical equivalence laws as follows (see https://en.wikipedia.org/wiki/Logical_equivalence):

(1) Identity and idempotent laws

φ &amp;&amp; true ≡ φ, φ || false ≡ φ,

(2) Domination and negation laws φ &amp;&amp; φ ≡ φ, φ || φ ≡ φ

φ &amp;&amp; false ≡ false, φ || true ≡ true,

(3) De Morgan’s laws φ &amp;&amp; ! φ ≡ false, φ || ! φ ≡ true

! (φ1 &amp;&amp; φ2) ≡ ! φ1 || ! φ2,

(4) Absorption laws ! (φ1 || φ2) ≡ ! φ1 &amp;&amp; ! φ2

φ1 || (φ1 &amp;&amp; φ2) ≡ φ1,

(5) Double negation law φ1 &amp;&amp; (φ1 || φ2) ≡ φ1

! (! φ) ≡ φ

(6) Distributive laws

φ1 || (φ2 &amp;&amp; φ3) ≡ (φ1 || φ2) &amp;&amp; (φ1 || φ3), φ1 &amp;&amp; (φ2 || φ3) ≡ (φ1 &amp;&amp; φ2) || (φ1 &amp;&amp; φ3)

To simplify Boolean expressions, these rules are applied repeatedly—from the left-hand side to the right-hand side for each rule—in order from (1) to (6), with respect to the associativity and commutativity of &amp;&amp; and ||, until no more rule can be applied. For example:

– p1 &amp;&amp; (p2 &amp;&amp; ! p1) can be simplified into false.

– (p1 &amp;&amp; true) &amp;&amp; (p2 &amp;&amp; ! (! p1 &amp;&amp; ! p2)) can be simplified into p1 &amp;&amp; p2.

• Similarly, you will have to write at least one (separate) JUnit test for each method of the classes Constant, Variable, Negation, Conjunction, and Disjunction, in the test class ExpTest.

– Each test method should test a single behavior with appropriate assertions. Do not write a single method to check multiple behaviors.

– Your submitted tests need to achieve at least 80% branch coverage. Do not add arbitrary code to your test method to just increase coverage.

General Instruction

• Download the attached file homework2.zip, which contains two directores problem1 and problem2. Each of them can be imported as a separate project into IntelliJ IDEA.

• Initially, mvn test will fail, because no dependencies are declared in pom.xml. Modify your pom.xml to include required libraries, including JUnit5 (org.junit.jupiter), ANTLR4 (antlr4-runtime), etc.

• The src/main directory contains the skeleton code. You should implement all the methods marked with TODO. Before writing code, read the description in the source code carefully.

• The src/test directory contains test classes. Use JaCoCo to find out how much coverage your tests have. Upload the JaCoCo report in CSV format from target/site/jacoco/jacoco.csv.

• As usual, do not modify the existing interfaces, the class names, and the signatures of the public methods. You can add more methods or classes if you want.

Turning in

1. Create a private project with name homework2 in https://csed332.postech.ac.kr, and clone the project on your machine.

2. Commit your changes in your homework2 project that includes two directories problem1 and problem2, including JaCoCo coverage reports, and push them to the remote repository.

3. The JaCoCo coverage report for each problem, generated by mvn jacoco:report, will be uploaded to the directory homework2 as follows:

• homework2/jacoco1.csv for Problem 1 • homework2/jacoco2.csv for Problem 2

4. Tag your project with “submitted” and submit your homework. We will use the tagged version of your project for grading.

Reference

• Java Language Specification: https://docs.oracle.com/javase/specs/

• Maven Getting Started Tutorial: https://maven.apache.org/guides/getting-started/
