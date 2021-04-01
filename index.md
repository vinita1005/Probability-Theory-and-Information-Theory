# Probability Theory for ML basics

## Probability Mass Function (PMF):
Probability over Discrete variables.

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo form="prefix">∀</mo><mi>x</mi><mo form="infix">∈</mo><mi>X</mi><mo separator="true">, </mo><mspace is="true" width="0.22em"></mspace><mn>0</mn><mo form="infix">⩽</mo><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">⩽</mo><mn>1</mn></math>

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><munderover><mo largeop="true" movablelimit="true">∑</mo><mrow><mi>x</mi><mo form="infix">∈</mo><mi>X</mi></mrow><mrow></mrow></munderover><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mn>1</mn></math>


## Probability Density Function (PDF):
Probability over continuous functions.

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mtable columnwidth="100%" width="100%" columnalign="center"><mtr><mtd><mrow><mo form="prefix">∀</mo><mi>x</mi><mo form="infix">∈</mo><mi>X</mi><mo separator="true">,</mo><mspace is="true" width="0.66em"></mspace><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">⩾</mo><mn>0</mn></mrow></mtd></mtr><mtr><mtd><mrow></mrow></mtd></mtr></mtable></math><math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mo largeop="true">∫</mo><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>d</mi><mi>x</mi><mo form="infix">=</mo><mn>1</mn></math>

## Marginal Probability:
Joint Distribution of several variables can be computed using:

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mtable columnwidth="100%" width="100%" columnalign="center"><mtr><mtd><mrow><mo form="prefix">∀</mo><mi>x</mi><mo form="infix">∈</mo><mi>X</mi><mo separator="true">,

</mo><mspace is="true" width="0.22em"></mspace></mrow></mtd></mtr><mtr><mtd><mrow></mrow></mtd></mtr><mtr><mtd><mrow><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><munderover><mo largeop="true" movablelimit="true">∑</mo><mi>y</mi><mrow></mrow></munderover><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mo separator="true">,</mo><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mo fence="true" stretchy="false">)
  
</mo></mrow></mtd></mtr><mtr><mtd><mrow></mrow></mtd></mtr><mtr><mtd><mrow><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mo largeop="true">∫</mo><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo separator="true">,</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>d</mi><mi>y</mi></mrow></mtd></mtr></mtable></math>

## Conditional Probability:
Probability of an event, given that some other event has happened.

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>Y</mi><mo form="infix"> = </mo><mi>y</mi><mo stretchy="false">|</mo><mi>X</mi><mo form="infix"> = </mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix"> = </mo><mfrac><mrow><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>Y</mi><mo form="infix"> = </mo><mi>y</mi><mo separator="true">,</mo><mi>X</mi><mo form="infix"> = </mo><mi>x</mi><mo fence="true" stretchy="false">)</mo></mrow><mrow><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix"> = </mo><mi>x</mi><mo fence="true" stretchy="false">)</mo></mrow></mfrac></math>

# Basic Rules and Terminologies:

## Chain Rule:

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-5.png" width="160" height="25" />

## Independence Rule:

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-6.png" width="170" height="40" />

## Conditional Independence:

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-7.png" width="160" height="40" />

## Expectation:
Average value which f takes on when x is drawn from P.
### Discrete

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-8a.png" width="140" height="60" />

### Continuous

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/8b.png" width="140" height="60" />

## Variance:

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-10.png" width="140" height="60" />

## Covariance:
Measures how two values are linearly related.

<img src="https://github.com/vinita1005/Probability-Theory-and-Information-Theory/blob/gh-pages/math-11.png" width="140" height="60" />

**Independant variables have 0 covariance.

