# Prompts for lesson 1

Run both on `orders.csv`, each in a **new chat**, and compare. Do not edit either answer afterwards.

## Run A — the plain prompt

Type exactly this and nothing else:

```
Analyse this data.
```

## Run B — the four Ds

Write your decision first, in one sentence:

```
I am deciding ______ . If the data says ______ , I will ______ . If it says ______ , I will ______ .
```

The four parts of a good request:

1. **Decision** — the choice you are making, and what each result would change.
2. **Data** — what the file is and what each column means.
3. **Deliverable** — what you want back, how long, and which numbers it must show.
4. **Doubts** — ask it to say what it assumed or changed, and what would change its recommendation.

Then paste this into a fresh chat with `orders.csv` attached:

```
I own a small tea retailer, Chai & Co. I have ₹1 lakh to spend next quarter on ONE of these:
(1) A part-time helper for Saturdays and Sundays.
(2) Promotion for our Online and Marketplace channels.
(3) Extra stock of one product line.

The attached orders.csv has every order from one calendar year. Columns: order_id, order_date, customer_id (C = retail customer, W = wholesale account), product, category, quantity, unit_price, amount (order total in rupees), channel (Store, Online, Marketplace, Wholesale), city.

Tell me which of the three the data supports most, and why, in under 300 words. Show the three or four numbers you relied on. Then tell me what you assumed or changed in the data, and what would change your recommendation.
```

## Practice

Rewrite each of these as a decision sentence, using the shape above:

- "Take a look at our sales."
- "Tell me about our customers."
- "Is our marketing working?"
