prog-5-d5 : Algo

Coffee Machine – Basic Logic Simulation

Introduction

This repository contains a simple logic model for an automatic coffee machine. The goal is to simulate a typical user interaction flow, including payment, drink selection, and delivery — with basic error handling at each step. It’s a minimal prototype designed for an academic project, but could serve as the foundation for a more complete system later on.


---

What It Does

The machine allows a user to buy a hot beverage in three main steps:

1. Make a Payment


2. Pick a Drink


3. Get Your Coffee



Each step includes checks to handle common problems (e.g., out-of-stock issues, missing cup, etc.). We tried to keep it simple and realistic.


---

Step-by-Step Breakdown

1. Payment

The user can pay using:

Credit/debit card

Mobile payment (like Mobile Money)


Things that can go wrong:

Not enough funds

Payment failed

Connection issues



---

2. Choose a Drink

Once payment is confirmed, the user selects a drink (espresso, latte, etc.). For now, we just simulate a few basic types.

Possible issues:

No coffee pod detected

Water tank is empty

No power or internal error (e.g., temperature or pressure problems)



---

3. Dispense

If everything is fine, the machine tries to serve the drink.

But...

If there’s no cup, it stops the process and shows a warning.




