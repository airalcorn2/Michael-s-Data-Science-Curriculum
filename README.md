# Michael's Data Science Curriculum
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Michael's Data Science Curriculum</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://sites.google.com/view/michaelaalcorn/" property="cc:attributionName" rel="cc:attributionURL">Michael A. Alcorn</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Table of Contents
=================

* [**Math**](#Math)
  * [**Calculus**](#Calculus)
  * [**Linear Algebra**](#Linear-Algebra)
  * [**Differential Equations**](#Differential-Equations)
  * [**Advanced**](#Advanced-Math)
    * [**Analysis**](#Analysis)
    * [**Topology/Differential Geometry**](#Topology-Differential-Geometry)
    * [**Abstract Algebra**](#Abstract-Algebra)
* [**Statistics/Probability Theory**](#Statistics-Probability-Theory)
  * [**General**](#General-Statistics)
  * [**Bayesian**](#Bayesian)
  * [**Advanced**](#Advanced-Statistics)
    * [**Statistical Learning Theory**](#Statistical-Learning-Theory)
    * [**Theory of Probability**](#Theory-of-Probability)
* [**Econometrics**](#Econometrics)
* [**Algorithms**](#Algorithms)
* [**Machine Learning/Artificial Intelligence**](#Machine-Learning-Artificial-Intelligence)
  * [**General**](#General-Machine-Learning)
  * [**Natural Language Processing**](#Natural-Language-Processing)
  * [**Advanced**](#Advanced-Machine-Learning)
    * [**Deep Learning**](#Deep-Learning)
    * [**Reinforcement Learning**](#Reinforcement-Learning)
    * [**Probabilistic Graphical Models**](#Probabilistic-Graphical-Models)
* [**Other Topics**](#Other-Topics)
  * [**Big Data**](#Big-Data)
  * [**Social Networks and Game Theory**](#Social-Networks-and-Game-Theory)
  * [**Advanced**](#Advanced-Other-Topics)
    * [**Optimization**](#Optimization)
    * [**Information Theory**](#Information-Theory)
    * [**Digital Signal Processing**](#Digital-Signal-Processing)

Curriculum
==========

* [Michael's Guide to Becoming a Data Scientist](https://github.com/airalcorn2/Michael-s-Guide-to-Becoming-a-Data-Scientist)
* <a name="Math"></a>**Math**
  * Over the course of my math studies, I learned that the [French have a reputation for teaching math a particular way from a young age](https://www.quora.com/What-are-the-reasons-the-french-are-so-good-at-mathematics-What-are-some-best-practices-at-policy-level-in-school-or-university-that-could-be-emulated-in-a-developing-country), and I think I'm a fan.
  * <a name="Calculus"></a>**Calculus**
      * Textbooks
          * [Calculus, Vol. 1: One-Variable Calculus, with an Introduction to Linear Algebra](http://www.wiley.com/WileyCDA/WileyTitle/productCd-EHEP001951.html) (Apostol) - Apostol's textbooks are classics for a reason. They are a great introduction to calculus and do an excellent job of developing intuition for limits, derivatives, and integrals.
          * [Calculus, Vol. 2: Multi-Variable Calculus and Linear Algebra with Applications to Differential Equations and Probability](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471000078.html) (Apostol)
      * Courses
          * [MA101: Single-Variable Calculus I](https://learn.saylor.org/course/ma101/) (Saylor Academy) - good introduction to calculus. Provided links to different types of learning material from different sources, which I think encourages learning. Seeing/hearing different perspectives on the same material seems to help crystallize concepts often. Really delves into the "why" of differentiation and integration.
          * [MA102: Single-Variable Calculus II](https://legacy.saylor.org/ma102/Intro/) (Saylor Academy) - first two units were entirely redundant with the end of MA101. Unit 3 was fairly painful, with a lot of memorization of integration "tricks". Course felt like somewhat of a hodgepodge of different mathematical concepts without it being entirely clear why they were covered together (e.g., series, differential equations).
          * [18.02: Multivariable Calculus](http://ocw.mit.edu/courses/mathematics/18-02sc-multivariable-calculus-fall-2010/) (MIT) - enjoyed the first two parts, but I got lazy around double line integrals. The physical applications of concepts like curl and flux are interesting, but I was ready to move on to linear algebra. As an aside, MIT uses a two course sequence to teach calculus and I agree that's the way it should be done.
          * [Multivariable Calculus](https://www.khanacademy.org/math/multivariable-calculus) (Khan Academy) - Khan Academy produces extremely high quality content for a variety of subjects, and its offerings for multivariable calculus are no different.
  * <a name="Linear-Algebra"></a>**Linear Algebra**
      * Textbooks
          * [Linear Algebra and Its Applications](http://www.cengage.com/search/productOverview.do?N=16+4294922413+4294952008) (Strang) - linear algebra is probably my favorite math course. There is a lot of geometric intuition that is really satisfying, and the fact that linear algebra has tons of applications today doesn't hurt. Strang is a great teacher and writer, and his texts are classics for a reason.
          * [Linear Algebra Done Right](http://linear.axler.net/) (Axler)
      * Courses
          * [Coding the Matrix: Linear Algebra through Computer Science Applications](http://codingthematrix.com/) (Coursera) - an excellent introduction to linear algebra that develops a deep understanding of the subject beyond just matrices and vectors.
  * <a name="Differential-Equations"></a>**Differential Equations**
      * Textbooks
          * [Ordinary Differential Equations](http://store.doverpublications.com/0486649407.html) (Tenenbaum and Pollard)
          * [Matrix Differential Equations with Applications in Statistics and Econometrics](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047198633X.html) (Magnus and Neudecker) - if someone was trying to learn differential equations quickly and knew some linear algebra, I would tell them to skip ordinary differential equations and to go straight to this book. Almost all interesting problems today involve many variables interacting in complex ways, so partial differential equations are the more relevant differential equations, and, in my opinion, they can be taught entirely independently of ODEs.
          * [Nonlinear Dynamics and Chaos: With Applications to Physics, Biology, Chemistry, and Engineering ](http://www.stevenstrogatz.com/books/nonlinear-dynamics-and-chaos-with-applications-to-physics-biology-chemistry-and-engineering) (Strogatz)
      * Courses
          * [Introduction to Differential Equations](https://www.edx.org/course/introduction-differential-equations-bux-math226-1x-1) (edX) - highly enjoyable three course sequence on differential equations. Differential equations was the only math subject that I didn't initially enjoy. I tried a number of different textbooks, but nothing was engaging me. Part of my problem was that there are a number of "tricks" involved in coming up with analytical solutions to differential equations that I didn't find particularly satisfying. I also didn't ever feel like I was gaining new insight or intuition when studying the subject in isolation, which is not how I felt about other math subjects. When I first made this curriculum, I suggested differential equations would be more enjoyable if it were taught in combination with a science - something like a "Differential Equations in Physics" course - especially since most differential equations theory was motivated by the study of a physical system in the first place (as many of the biographical sketches of scientists and mathematicians in the Tenenbaum and Pollard textbook allude to). Indeed, revisiting differential equations after seeing some of the concepts pop up in other courses made the subject much more interesting to me.
          * [Nonlinear Dynamics: Mathematical and Computational Approaches](https://www.complexityexplorer.org/courses/60-nonlinear-dynamics-mathematical-and-computational-approaches-fall-2016) (Complexity Explorer) - an excellent course for developing some intuition for nonlinear dynamics. The only downside of the course is that there wasn't as much mathematical depth as I would've liked (by design, it seems), so it should be considered a complement to the Strogatz textbook.
  * <a name="Advanced-Math"></a>**Advanced**
      * These subjects are only necessary for those who want to achieve a deeper understanding of the math behind machine learning/probability.
      * <a name="Analysis"></a>**Analysis**
        * Textbooks
            * [Principles of Mathematical Analysis](http://www.mheducation.com/highered/product/principles-mathematical-analysis-rudin/007054235X.html) (Rudin) - analysis delves into the "why" of math and does so by deriving the existence of various mathematical concepts (e.g., the real and complex numbers, differentiation) from very simple initial building blocks (i.e., sets, addition, multiplication, and limits). Like abstract algebra, it is an interesting subject, but it's probably only practically relevant to individuals pursuing math-y subjects at higher levels. Subjects that use some analysis for derivations/proofs will generally provide the necessary background.
      * <a name="Topology-Differential-Geometry"></a>**Topology/Differential Geometry**
        * Textbooks
          * [Topology](https://www.pearsonhighered.com/program/Munkres-Topology-2nd-Edition/PGM56881.html) (Munkres) - felt like a continuation of analysis. Fun to think about, not very practical for most people (although, there is considerable interest in manifolds within the academic machine learning community; see [1](http://stats.stackexchange.com/questions/66939/what-is-the-manifold-assumption-in-semi-supervised-learning), [2](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/), [3](http://www.deeplearningbook.org/contents/representation.html), and [4](http://www.cs.cornell.edu/~kilian/research/manifold/manifold.html)).
        * Courses
          * [What is a Tensor?](https://www.youtube.com/playlist?list=PLRlVmXqzHjUQARA37r4Qw3SHPqVXgqO6c) - an excellent introduction to differential geometry. Not super useful unless you're studying [spacetime](https://en.wikipedia.org/wiki/Mathematics_of_general_relativity).
          * [Tensor Calculus, Multilinear Algebra and Differential Geometry](https://www.youtube.com/playlist?list=PLtku678e9yj725K6hjLqKhJ854nTWWR5e)
      * <a name="Abstract-Algebra"></a>**Abstract Algebra**
        * Textbooks
          * [Algebra](https://www.pearsonhighered.com/program/Artin-Algebra-2nd-Edition/PGM218164.html) (Artin) - this was the first math subject I encountered where it was clear that it was mostly for people who wanted to pursue math at a higher level (just to clarify, the subject I'm discussing here is typically referred to as "[abstract algebra](https://en.wikipedia.org/wiki/Abstract_algebra)", so it's not the same subject you learned in grade school). That is, there was very little that could be taken from this subject and applied in non-mathematical settings. With that being said, the subject is really interesting, and there are some applications in computer science (e.g., monads and monoids, which are concepts in [category theory](https://en.wikipedia.org/wiki/Category_theory), also come up in [functional programming](https://en.wikipedia.org/wiki/Functional_programming)).
          * [Abstract Algebra: Theory and Applications](http://abstract.ups.edu/download/aata-20160809-sage-7.3.pdf) (Judson) (free!)
* <a name="Statistics-Probability-Theory"></a>**Statistics/Probability Theory**
  * <a name="General-Statistics"></a>**General**
      * Textbooks
          * [All of Statistics: A Concise Course in Statistical Inference](http://www.stat.cmu.edu/~larry/all-of-statistics/) (Wasserman)
          * [OpenIntro Statistics](https://www.openintro.org/stat/index.php) (free!)
          * [Causal Inference](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) (Hernán and Robins) (draft: free!)
          * [Forecasting: Principles and Practice](https://otexts.org/fpp2/) (Hyndman and Athanasopoulos) (free!)
          * [Probability Theory: The Logic of Science](http://www.cambridge.org/gh/academic/subjects/physics/theoretical-physics-and-mathematical-physics/probability-theory-logic-science?format=HB&isbn=9780521592710) (Jaynes) (draft: free!)
      * Courses
          * [18.440: Probability and Random Variables](https://ocw.mit.edu/courses/mathematics/18-440-probability-and-random-variables-spring-2014/index.htm) (MIT)
  * <a name="Bayesian"></a>**Bayesian**
      * Textbooks
          * [Bayesian Data Analysis](http://www.stat.columbia.edu/~gelman/book/) (Gelman et al.)
          * [Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan](https://sites.google.com/site/doingbayesiandataanalysis/) (Kruschke)
          * [Think Bayes](http://www.greenteapress.com/thinkbayes/) (Downey) (free!)
          * [Probabilistic Programming & Bayesian Methods for Hackers](http://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/) (Davidson-Pilon) (free!)
          * [Data Analysis Using Regression and Multilevel-Hierarchical Models](http://www.stat.columbia.edu/~gelman/arm/) (Gelman and Hill)
  * <a name="Advanced-Statistics"></a>**Advanced**
    * <a name="Statistical-Learning-Theory"></a>**Statistical Learning Theory**
      * Textbooks
          * [Statistical Learning Theory](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471030031.html) (Vapnik)
    * <a name="Theory-of-Probability"></a>**Theory of Probability**
      * Courses
        * [18.175: Theory of Probability](http://math.mit.edu/~sheffield/fall2016math175.html) (MIT)
* <a name="Econometrics"></a>**Econometrics**
    * I used to have the "Econometrics" section below the "Other" section, but I decided to move it here because I've come to the conclusion that thinking like an economist is one of the most valuable skills a data scientist can have. Economists, like data scientists, often work with [observational data](https://en.wikipedia.org/wiki/Observational_study), which can make estimating the causal effect of any particular [intervention](https://plato.stanford.edu/entries/causation-mani/#Inte) rather challenging. As a result, economists tend to be *very* careful when using models to investigate causality—a skill that is sometimes [underrated by those in the data science community](https://www.linkedin.com/pulse/linear-models-actually-easily-interpretable-michael-a-alcorn).
    * Textbooks
        * [Mostly Harmless Econometrics: An Empiricist's Companion](http://www.mostlyharmlesseconometrics.com/) (Angrist and Pischke)
        * [Introductory Econometrics: A Modern Approach](https://www.cengage.com/c/introductory-econometrics-a-modern-approach-6e-wooldridge/9781305270107) (Wooldridge)
        * [Econonmetric Analayis of Cross Section and Panel Data](https://mitpress.mit.edu/books/econometric-analysis-cross-section-and-panel-data-second-edition) (Wooldridge)
        * [Econometric Analysis](http://pages.stern.nyu.edu/~wgreene/Text/econometricanalysis.htm) (Greene)
        * [Econometrics](http://press.princeton.edu/titles/6946.html) (Hayashi)
        * [Fundamental Mathematics of Mathematical Economics](http://www.amazon.com/Fundamental-Methods-Mathematical-Economics-Wainwright/dp/0070109109) (Wainwright and Chang)
    * Courses
        * [Applied Econometrics](http://people.stern.nyu.edu/wgreene/Econometrics/Econometrics.htm) (New York University)
        * [Econometric Analysis of Panel Data](http://people.stern.nyu.edu/wgreene/Econometrics/PanelDataEconometrics.htm) (New York University)
        * [Undergraduate Course](https://www.youtube.com/watch?v=M_5SLG7sUa0&list=PLwJRxp3blEvZyQBTTOMFRP_TDaSdly3gU)
        * [Graduate Course](https://www.youtube.com/watch?v=GMVh02WGhoc&list=PLwJRxp3blEvaxmHgI2iOzNP6KGLSyd4dz)
        * [Mathematical Methods for Economic Theory](http://mjo.osborne.economics.utoronto.ca/index.php/tutorial/index/1/int/i) (University of Toronto)
* <a name="Algorithms"></a>**Algorithms**
  * Textbooks
      * [Algorithms](https://algs4.cs.princeton.edu/home/) (Sedgewick and Wayne)
      * [Introduction to Algorithms](https://mitpress.mit.edu/books/introduction-algorithms) (Cormen et al.)
  * Courses
      * [Algorithms Specialization](https://www.coursera.org/browse/computer-science/algorithms) (Coursera)
      * [Introdcution to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-046j-introduction-to-algorithms-sma-5503-fall-2005/) (MIT)
      * [Bioinformatics Specialization](https://www.coursera.org/specializations/bioinformatics) (Coursera) - while the subject matter might not be relevant to everyone, I think most computer scientists would benefit from taking this course as it really gets you thinking about efficient algorithms in a real world context.
* <a name="Machine-Learning-Artificial-Intelligence"></a>**Machine Learning/Artificial Intelligence**
  * <a name="General-Machine-Learning"></a>**General**
      * Textbooks
          * [Pattern Recognition and Machine Learning](http://research.microsoft.com/en-us/um/people/cmbishop/prml/) (Bishop)
          * [Machine Learning: A Probabilistic Perspective](http://www.cs.ubc.ca/~murphyk/MLbook/) (Murphy)
          * [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) (James et al.)
          * [Machine Learning](http://www.cs.cmu.edu/~tom/mlbook.html) (Mitchell)
          * [Advanced Data Analysis from an Elementary Point of View](http://www.stat.cmu.edu/~cshalizi/ADAfaEPoV/) (Shalizi) (draft: free!)
          * [The Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) (Hastie, Tibshirani, and Friedman) (free!)
          * [Artificial Intelligence: A Modern Approach](http://aima.cs.berkeley.edu/) (Russell and Norvig)
      * Courses
          * [Machine Learning](https://www.udacity.com/course/machine-learning--ud262) (Udacity)
          * [Machine Learning](https://www.coursera.org/learn/machine-learning) (Coursera)
          * [Learning From Data](https://www.edx.org/course/learning-data-introductory-machine-caltechx-cs1156x-0) (edX) - warning: this one is more on the theoretical side.
          * [Artificial Intelligence for Robotics](https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373) (Udacity)
          * [Artificial Intelligence](https://www.edx.org/course/artificial-intelligence-uc-berkeleyx-cs188-1x) (edX)
  * <a name="Natural-Language-Processing"></a>**Natural Language Processing**
      * Textbooks
          * [Foundations of Statistical Natural Language Processing](http://nlp.stanford.edu/fsnlp/) (Manning and Schütze)
          * [Speech and Language Processing](http://www.cs.colorado.edu/~martin/slp.html) (Jurafsky and Martin)
      * Courses
          * [Natural Language Processing](https://www.coursera.org/course/nlangp) (Coursera) - no longer offered. Course notes available [here](http://www.cs.columbia.edu/~mcollins/notes-spring2013.html).
          * [Natural Language Processing](https://www.coursera.org/course/nlp) (Coursera) (different one) - no longer offered on Coursera, but can be found on [the professor's website](https://web.stanford.edu/~jurafsky/NLPCourseraSlides.html).
          * [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/) (Stanford)
  * <a name="Advanced-Machine-Learning"></a>**Advanced**
    * <a name="Deep-Learning"></a>**Deep Learning**
        * Textbooks
            * [Deep Learning](http://www.deeplearningbook.org) (Goodfellow, Bengio, and Courville) (draft: free!)
            * [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) (Nielsen) (free!)
        * Courses
            * [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) (Coursera)
            * [Neural Networks for Machine Learning](https://www.coursera.org/course/neuralnets) (Coursera)
            * [IFT6266 – H2015 Representation Learning](https://ift6266h15.wordpress.com/) (Université de Montréal)
            * [CS231n: Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/index.html) (Stanford)
    * <a name="Reinforcement-Learning"></a>**Reinforcement Learning**
        * Textbooks
            * [Reinforcement Learning: An Introduction](http://webdocs.cs.ualberta.ca/~sutton/book/the-book.html) (Sutton and Barto) (draft: free!)
        * Courses
            * [COMPM050/COMPGI13: Reinforcement Learning](http://www0.cs.ucl.ac.uk/staff/D.Silver/web/Teaching.html) (University College London)
            * [Reinforcement Learning](https://www.udacity.com/course/reinforcement-learning--ud600) (Udacity)
            * [CS 294: Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/) (University of California, Berkeley)
            * [CS234: Reinforcement Learning](http://web.stanford.edu/class/cs234/index.html) (Stanford)
    * <a name="Probabilistic-Graphical-Models"></a>**Probabilistic Graphical Models**
        * Textbooks
            * [Probabilistic Graphical Models: Principles and Techniques](http://pgm.stanford.edu/) (Koller and Friedman)
        * Courses
            * [Probabilistic Graphical Models](https://www.coursera.org/course/pgm) (Coursera)
* <a name="Other-Topics"></a>**Other Topics**
  * <a name="Big-Data"></a>**Big Data**
      * Textbooks
          * [Mining of Massive Datasets](http://www.mmds.org/) (Leskovec et al.) (free!)
      * Courses
          * [Data Science and Engineering with Spark](https://www.edx.org/xseries/data-science-engineering-apache-spark) (edX)
          * [Introduction to Hadoop and MapReduce](https://www.udacity.com/course/intro-to-hadoop-and-mapreduce--ud617) (Udacity)
          * [Algorithms for Big Data](http://grigory.us/big-data-class.html) (Indiana University)
          * [CMPSCI 711: More Advanced Algorithms](http://people.cs.umass.edu/~mcgregor/courses/CS711S12/) (University of Massachusetts)
          * [COSC 548: Streaming Algorithms](http://people.cs.georgetown.edu/jthaler/COSC548.html) (Georgetown University)
          * [Functional Programming in Scala Specialization](https://www.coursera.org/specializations/scala) (Coursera)
  * <a name="Social-Networks-and-Game-Theory"></a>**Social Networks and Game Theory**
    *  Textbooks
       * [Networks, Crowds and Markets: Reasoning about a Highly Connected World](http://www.cs.cornell.edu/home/kleinber/networks-book/) (Easley and Kleinberg) (draft: free!)
    *  Courses
       * [Networks, Crowds and Markets](https://www.edx.org/course/networks-crowds-markets-cornellx-info2040x-2) (edX)
       * [Game Theory](https://www.coursera.org/learn/game-theory-1) (Coursera)
  * <a name="Advanced-Other-Topics"></a>**Advanced**
    * <a name="Optimization"></a>**Optimization**
        * Textbooks
          * [An Introduction to Numerical Analysis](http://www.cambridge.org/gh/academic/subjects/mathematics/numerical-analysis/introduction-numerical-analysis-1?format=PB) (Süli and Mayers) - my first [applied math](https://en.wikipedia.org/wiki/Applied_mathematics) subject, it felt like a continuation of linear algebra (in fact, there was a fair amount of overlap). Probably not necessary unless you see yourself implementing numerical solvers in the future.
          * [Convex Optimization](http://web.stanford.edu/~boyd/cvxbook/) (Boyd and Vandenberghe) (free!)
        * Courses
          * [Discrete Optimization](https://www.coursera.org/learn/optimization) (Coursera) - a challenging but extremely rewarding course.
          * [Convex Optimization](https://lagunita.stanford.edu/courses/Engineering/CVX101/Winter2014/about) (Stanford Online)
          * [Machine Learning 10-725: Convex Optimization](http://www.stat.cmu.edu/~ryantibs/convexopt/) (Carnegie Mellon University)
    * <a name="Information-Theory"></a>**Information Theory**
      * Textbooks
        * [Elements of Information Theory](http://www.wiley.com/WileyCDA/WileyTitle/productCd-0471241954.html) (Cover and Thomas)
        * [Information Theory, Inference, and Learning Algorithms](http://www.inference.eng.cam.ac.uk/mackay/itila/book.html) (MacKay) (free!)
    * <a name="Digital-Signal-Processing"></a>**Digital Signal Processing**
        * Textbooks
          * [Discrete-Time Signal Processing](https://www.pearsonhighered.com/program/Oppenheim-Discrete-Time-Signal-Processing-3rd-Edition/PGM212808.html) (Oppenheim and Schafer)
          * [Foundations of Signal Processing](http://www.fourierandwavelets.org/) (Vetterli, Kovačević, and Goyal) (draft: free!)
        * Courses
          * [Digital Signal Processing](https://www.coursera.org/learn/dsp) (Coursera)
