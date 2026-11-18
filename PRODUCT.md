# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Lunch Money and YNAB users preparing a zakat estimate from their actual balances.

## Product Purpose

Mizan uses balances from Lunch Money to estimate zakat and show how that estimate was calculated. Reviewing balances supports that calculation; the goal is to understand the zakat estimate.

## Positioning

A community project that reads Lunch Money balances directly, provides a traceable calculation and accommodates different scholarly methods. Lunch Money does not make or support it.

## Operating Context

Users connect with a Lunch Money or YNAB access token or explore fictional sample data, review balances and debts, choose calculation methods, and review an estimate and balance history.

## Capabilities and Constraints

- The site is a static web application; calculations run in the browser.
- It uses read requests, does not save tokens or balances, and saves only calculation preferences locally.
- It must preserve traceable amounts, method choices, incomplete and partial-data states, and historical coverage limitations.
- It provides an estimate and recognizes differences in scholarly methods; it cannot confirm a completed hawl.

## Brand Commitments

Mizan means balance. The user has requested a calm, trustworthy, modern Islamic technology feel.

## Messaging

Agreed with the owner in November 2026.

- **Reader:** someone new to working out zakat comes first. Keep it short enough that people who already know the rules are not slowed down.
- **Main message:** your zakat is worked out from your real balances, not a guess.
- **Voice:** first person from the maker ("I built this") on the home page and the guide pages. The calculator steps (connect, review, estimate) stay short and neutral, speaking to "you" with no "I".
- **Islamic terms:** nisab and hawl stay as the main words. Give each a one-line plain meaning the first time it appears on a page. The Quran and hadith quotes stay where they are.
- **Certainty:** be confident about the figure and show its working. Say once, clearly, that it is an estimate and that scholars differ; do not repeat the caveat at every step.
- **After the result:** a short warm closing line and a way to copy or print the summary. No advice on where to give.
- **Names:** "access token" (not API token or key), "balances" for imported figures, "estimate" for the result, "untick" for checkboxes, "Mizan" as the actor (not "the page").

## Evidence on Hand

The calculator, fictional sample data, product explanations and source references are in `index.html`, the guide pages and `README.md`.

## Product Principles

- Make the source and effect of every amount clear.
- Protect users' private financial information.
- Support informed choices without implying a single scholarly method.
- Make missing information and limits visible.
