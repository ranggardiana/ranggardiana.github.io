# Portfolio

1. [Business Research: Real Time Cost Rollup for Custom Manufacturing BOMs](#real-time-cost-rollup-for-custom-manufacturing-boms)
2. [Self Mini Project: "Terserah" Date-Night Decision](#self-mini-project)

---
## Real Time Cost Rollup for Custom Manufacturing BOMs

**Author:** Ardiana Rangga

**Topic:** Enterprise Data Modeling, Production Systems Architecture & Supply Chain Engineering

**Context:** Independent Engineering & Systems Architecture Project (Inspired by Industry Experience in Precision Manufacturing)

---

Based on my work experience, a static bom from an excel file or spreadsheet usually erodes custom-made manufacturing projects.
Raw material prices often fluctuate up and down in the middle of processing an order.
A quotation can just become irrelevant so that once the goods are shipped, the expected margin of around 20% might not be achieved.

Relying on recursive queries directly on the active production data table will not survive at scale. This method directly locks production records.
So i think that there should be a solution. The solution is a Directed Acyclic Graph (DAG). The computer quietly calculates prices in real time so that if there are price changes, we can carry out a rescue mission much faster.

---

## Executive Summary

For high mix custom manufacturers, margin leakage already happens before the work comes in, so often the factory actually loses money due to miscalculation.
This happens because

1. The records are manual and rigid.
2. Forgot to count the wasted remaining resources
3. Late to know that material prices have already gone up
   
![BOM Breakdown Screenshot](https://raw.githubusercontent.com/ranggardiana/ranggardiana.github.io/main/assets/img/bom-screenshot.png)

[![Read More](https://img.shields.io/badge/read-more-brightgreen?style=for-the-badge)](https://github.com/ranggardiana/ranggardiana.github.io/blob/main/blogs/engineering-scalable-multi-level.md)

---

## Self Mini Project

### Solving the "Terserah" Paradoxfor Date-Night Decision Deadlock
WELCOME TO HACKTOBER FEST YEAY!!
In Indonesian dating culture, there is the "Terserah" Paradox.
So basically, I ask my girlfriend, what do you want to eat?
**Terserah**.
It just keeps going like that until we end up eating raw potatoes.

Or in mathematical terms:

<p data-sourcepos="38:1-40:2" dir="auto" style="text-align: center;">
  <math-renderer class="js-display-math" style="display: block; text-align: center;" data-run-id="7c5a276762474ebbb9f5dcdc855ec221" data-catalyst="">
    <math xmlns="http://www.w3.org/1998/Math/MathML" display="block">
      <mi mathvariant="normal">∀</mi>
      <mi>x</mi>
      <mo>∈</mo>
      <mtext>Suggestions</mtext>
      <mo stretchy="false">(</mo>
      <mi>A</mi>
      <mo stretchy="false">)</mo>
      <mo>,</mo>
      <mstyle>
        <mspace width="1em"></mspace>
      </mstyle>
      <mtext>Probability</mtext>
      <mo stretchy="false">(</mo>
      <mi>B</mi>
      <mtext>&nbsp;accepts&nbsp;</mtext>
      <mi>x</mi>
      <mo stretchy="false">)</mo>
      <mo accent="false" stretchy="false">→</mo>
      <mn>0</mn>
    </math>
  </math-renderer>
</p>

This paper explores the root psychological mechanics of this deadlock (Decision Paralysis, Risk Externalization, and Asymmetric Vetoes) and presents **TerserahSolver**: a lightweight, web-based bilateral blind swipe consensus engine. By combining anonymous zero-knowledge card mechanics, synchronous state matching, and hard-stop fallback arbitrators, this architecture eliminates relationship friction and delivers dinner resolutions in under 90 seconds.
