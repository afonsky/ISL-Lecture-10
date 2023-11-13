# Overview

<Anim spec="strong ^ @step 1 | @step 2 | @step 3 ^ @step 4 | @step 5 | @step 6 | @step 7 ^ figure | @step 8">

<div class="grid grid-cols-[5fr,2fr]">
<div>
Increasingly sophisticated decision boundaries: <span class="step"/>
<br>
<br>

* **Separating hyperplane** is any plane separating two classes <span class="step"/>
* **Maximal Margin Classifier (MMC)** seeks the best separating (linear) hyperplane <span class="step"/>
  * Requires perfect **linear separability** <span class="step"/>
</div>
<div>
  <figure>
    <img src="/Vladimir_Vapnik_by_Robert_Williamson.jpg" style="width: 300px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 11px; float: right;"><span>Image source:
     Vladimir Vapnik. Photo by Robert Williamson</span>
    </figcaption>
  </figure>
</div>
</div>

* **Support Vector Classifier (SVC)** adds **soft margins** to MMC to allow some violations with non-separable classes <span class="step"/>
* **Support Vector Machine (SVM)** adds non-linear decision boundary via non-linear kernel weights <span class="step"/>

* This stack of algorithms
  * <a href="http://www.cs.cmu.edu/~pakyan/compbio/references/Drucker_NIPS_1996.pdf">Invented</a> by <a href="https://news.itmo.ru/ru/blog/315/">Vladimir Vapnik</a> from <a href="http://www.mathnet.ru/links/775149f334df6549afff004af4eac367/at11885.pdf">MMC</a> (1963) to <a href="https://link.springer.com/content/pdf/10.1007/BF00994018.pdf">SVM with kernel trick</a> (1993) <span class="step"/>
  * Works for binary classification, multi-class is possible via one-vs-rest, one-vs-one

</Anim>

<!--
If we consider a classification problem, we will have to deal with a decision boundary. When it comes to nearest neighbors or tree or even neural network we can use very simple ideas that work very often. Today we will discuss very sophisticated idea that still have simple implementation.
-->

