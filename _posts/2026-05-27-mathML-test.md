---
layout: post
title: "MathML Test"
permalink: /mathml.html
---
<p>
Assume, for a contradiction, that selecting the key <math><mi>k</mi></math> uniformly from
<math>
<!--K = {0,1}^λ\{0^λ}-->
    <mi>K</mi>
    <mo>=</mo>
    <msup>
        <mrow>
            <mo>{</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo>}</mo>
        </mrow>
        <mi>λ</mi>
    </msup>
    <mo>\</mo>
    <mo>{</mo>
    <msup>
        <mn>0</mn>
        <mi>λ</mi>
    </msup>
    <mo>}</mo>
</math>
satisfies the property of uniformly distributed ciphertexts on
<math>
<!--{0,1}^λ-->
<msup>
    <mrow>
        <mo>{</mo>
        <mn>0</mn>
        <mo>,</mo>
        <mn>1</mn>
        <mo>}</mo>
    </mrow>
    <mi>λ</mi>
</msup>
</math>
, which, formally, means
<math>
<!--∀ c ∈ {0,1}^λ Pr(EAVESDROP(m)=c) = 1/λ s.t. m ∈ Σ.M = {0,1}^λ-->
    <mo>∀</mo>
    <mi>c</mi>
    <mo>∈</mo>
    <msup>
        <mrow>
            <mo>{</mo>
            <mn>0</mn>
            <mo>,</mo>
            <mn>1</mn>
            <mo>}</mo>
        </mrow>
        <mi>λ</mi>
    </msup>
    <mspace width="4px" depth="0px" height="0px"/>
    <mi>Pr</mi>
    <mo>(</mo>
        <mspace width="2px" depth="0px" height="0px"/>
        <mi>EAVESDROP</mi>
        <mo>(</mo>
            <mi>m</mi>
        <mo>)</mo>
        <mo>=</mo>
        <mi>c</mi>
        <mspace width="2px" depth="0px" height="0px"/>
    <mo>)</mo>
    <mo>=</mo>
    <mfrac><mn>1</mn> <mi>λ</mi></mfrac>
</math>
s.t.
<math>
    <mi>m</mi>
    <mo>∈</mo>
    <mi>Σ</mi>
    .
    <mi>M</mi>
    <mo>=</mo>
    <msup>
        <mrow>
            <mo>{</mo>
            <mn>0</mn>
            <mo>,</mo>
            <mn>1</mn>
            <mo>}</mo>
        </mrow>
        <mi>λ</mi>
    </msup>
</math>.
Because
<math>
<!--K = {0,1}^λ\{0^λ}-->
    <mi>K</mi>
    <mo>=</mo>
    <msup>
        <mrow>
            <mo>{</mo><mn>0</mn><mo>,</mo><mn>1</mn><mo>}</mo>
        </mrow>
        <mi>λ</mi>
    </msup>
    <mo>\</mo>
    <mo>{</mo>
    <msup>
        <mn>0</mn>
        <mi>λ</mi>
    </msup>
    <mo>}</mo>
    <mo mathvariant="normal">,</mo>
</math>
<math>
<!--Pr(k = 0^λ) = 0-->
    <mi>Pr</mi>
    <mo>(</mo>
        <mspace width="2px" depth="0px" height="0px"/>
        <mi>k</mi>
        <mo>=</mo>
        <msup>
            <mn>0</mn>
            <mi>λ</mi>
        </msup>
        <mspace width="2px" depth="0px" height="0px"/>
    <mo>)</mo>
    <mo>=</mo>
    <mn>0</mn>
    <mo mathvariant="normal">.</mo>
</math>
Since
<math>
<!--Pr(k = 0^λ) = 0-->
    <mi>Pr</mi>
    <mo>(</mo>
        <mspace width="2px" depth="0px" height="0px"/>
        <mi>k</mi>
        <mo>=</mo>
        <msup>
            <mn>0</mn>
            <mi>λ</mi>
        </msup>
        <mspace width="2px" depth="0px" height="0px"/>
    <mo>)</mo>
    <mo>=</mo>
    <mn>0</mn>
    <mo mathvariant="normal">,</mo>
</math>
<math>
<!--Pr(EAVESDROP(m)=m) = 0-->
    <mi>Pr</mi>
    <mo>(</mo>
        <mspace width="2px" depth="0px" height="0px"/>
        <mi>EAVESDROP</mi>
        <mo>(</mo>
            <mi>m</mi>
        <mo>)</mo>
        <mo>=</mo>
        <mi>m</mi>
        <mspace width="2px" depth="0px" height="0px"/>
    <mo>)</mo>
    <mo>=</mo>
    <mn>0</mn>
</math>
for any chosen 
</p>