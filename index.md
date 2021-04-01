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

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>a</mi><mo separator="true">,</mo><mi>b</mi><mo separator="true">,</mo><mi>c</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>a</mi><mo stretchy="false">|</mo><mi>b</mi><mo separator="true">,</mo><mi>c</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>b</mi><mo stretchy="false">|</mo><mi>c</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>c</mi><mo fence="true" stretchy="false">)</mo></math>

## Independence Rule:

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mtable columnwidth="100%" width="100%" columnalign="center"><mtr><mtd><mrow><mo form="prefix">∀</mo><mi>x</mi><mo form="infix">∈</mo><mi>X</mi><mo separator="true">,</mo><mspace is="true" width="0.66em"></mspace><mi>y</mi><mo form="infix">∈</mo><mi>Y</mi><mo separator="true">,</mo><mspace is="true" width="0.44em"></mspace></mrow></mtd></mtr><mtr><mtd><mrow><mspace is="true" width="1.32em"></mspace><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mo separator="true">,</mo><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>P</mi><mo fence="true" stretchy="false">(</mo><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo></mrow></mtd></mtr></mtable></math>

## Conditional Independence:

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mtable columnwidth="100%" width="100%" columnalign="center"><mtr><mtd><mrow><mo form="prefix">∀</mo><mi>x</mi><mo form="infix">∈</mo><mi>X</mi><mo separator="true">,</mo><mspace is="true" width="0.66em"></mspace><mi>y</mi><mo form="infix">∈</mo><mi>Y</mi><mo separator="true">,</mo><mspace is="true" width="0.88em"></mspace><mi>z</mi><mo form="infix">∈</mo><mi>Z</mi><mo separator="true">,</mo><mspace is="true" width="0.66em"></mspace></mrow></mtd></mtr><mtr><mtd><mrow><mspace is="true" width="0.88em"></mspace><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mo separator="true">,</mo><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mspace is="true" width="0.22em"></mspace><mo stretchy="false">|</mo><mspace is="true" width="0.22em"></mspace><mi>Z</mi><mo form="infix">=</mo><mi>z</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>X</mi><mo form="infix">=</mo><mi>x</mi><mspace is="true" width="0.22em"></mspace><mo stretchy="false">|</mo><mspace is="true" width="0.22em"></mspace><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>Y</mi><mo form="infix">=</mo><mi>y</mi><mspace is="true" width="0.22em"></mspace><mo stretchy="false">|</mo><mspace is="true" width="0.22em"></mspace><mi>Z</mi><mo form="infix">=</mo><mi>z</mi><mo fence="true" stretchy="false">)</mo></mrow></mtd></mtr></mtable></math>

## Expectation:
Average value which f takes on when x is drawn from P.
### Discrete

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="double-struck">E</mi><mi>x</mi><mi>~</mi><mi>p</mi><mo fence="true" stretchy="false">[</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">]</mo><mo form="infix">=</mo><munderover><mo largeop="true" movablelimit="true">∑</mo><mi>x</mi><mrow></mrow></munderover><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo></math>

### Continuous

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi mathvariant="double-struck">E</mi><mi>x</mi><mi>~</mi><mi>p</mi><mo fence="true" stretchy="false">[</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">]</mo><mo form="infix">=</mo><mo largeop="true">∫</mo><mi>p</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mi>F</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>d</mi><mi>x</mi></math>

## Variance:

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi>V</mi><mi>a</mi><mi>r</mi><mo fence="true" stretchy="false">(</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mi mathvariant="double-struck">E</mi><mo fence="true">[</mo><mo fence="true" stretchy="false">(</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">-</mo><mi mathvariant="double-struck">E</mi><mo fence="true" stretchy="false">[</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">]</mo><msup><mo fence="true" stretchy="false">)</mo><mn>2</mn></msup><mo fence="true">]</mo></math>

... how much f(x) varies from its value.

## Covariance:

Measures how two values are linearly related.

<math display="block" xmlns="http://www.w3.org/1998/Math/MathML"><mi>C</mi><mi>o</mi><mi>v</mi><mo fence="true" stretchy="false">(</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo separator="true">,</mo><mi>g</mi><mo fence="true" stretchy="false">(</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">)</mo><mo form="infix">=</mo><mi>E</mi><mo fence="true" stretchy="false">[</mo><mspace is="true" width="0.22em"></mspace><mo fence="true" stretchy="false">(</mo><mspace is="true" width="0.22em"></mspace><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">-</mo><mi>E</mi><mo fence="true" stretchy="false">[</mo><mi>f</mi><mo fence="true" stretchy="false">(</mo><mi>x</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">]</mo><mspace is="true" width="0.22em"></mspace><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mi>*</mi><mspace is="true" width="0.22em"></mspace><mo fence="true" stretchy="false">(</mo><mspace is="true" width="0.22em"></mspace><mi>g</mi><mo fence="true" stretchy="false">(</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mo form="infix">-</mo><mi>E</mi><mo fence="true" stretchy="false">[</mo><mi>g</mi><mo fence="true" stretchy="false">(</mo><mi>y</mi><mo fence="true" stretchy="false">)</mo><mo fence="true" stretchy="false">]</mo><mspace is="true" width="0.22em"></mspace><mo fence="true" stretchy="false">)</mo><mspace is="true" width="0.22em"></mspace><mo fence="true" stretchy="false">]</mo></math>

**Independant variables have 0 covariance.

