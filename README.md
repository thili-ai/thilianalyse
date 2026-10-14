# thilianalyse

The practice file and prompts for **[Ask AI to Analyse Your Data](https://ask.thili.ai)** — a short
course on getting an analysis from an AI assistant that you can actually trust: say what the decision
is, check what the assistant did to your data, run it again, and write down how sure you are.

There is no code here. It is a spreadsheet to practise on and some text to copy.

> ⚠️ **A practice file, not a real business.** `orders.csv` is invented: a fictional tea shop, fictional
> customers, one calendar year. It is deliberately imperfect, the way real exports are. **Do not clean it
> before you use it** — finding out what is wrong with it is part of the course. There are no answers in
> this folder.

## If you have never used GitHub

You do not need an account and you do not need to understand this site.

**To get just the practice file** (all you need for the first lesson):

1. Click **`orders.csv`** in the list above.
2. Click the **download icon** near the top right of the file view.
3. Open the downloaded file in Excel or Google Sheets.

**To get everything in this folder:**

1. Click the green **`< > Code`** button near the top of this page.
2. Click **Download ZIP**.
3. Unzip it somewhere you will find again — your Documents folder is fine.

## What is here

| File | Used in | What it is |
|---|---|---|
| `orders.csv` | Lessons 1 to 4 | One year of orders from the fictional tea shop, about 1,900 rows. Upload it to your AI assistant as it is |
| `prompts.md` | Lesson 1 | The two prompts you compare: the plain one everyone types, and the four-part one. Copy them as written |
| `decision-ledger.md` | Lesson 3 | A blank table for every change an AI assistant made to your data, with a status for each. Fill it in as you go |

More files are added as the lessons that use them are published.

## What the columns mean

| Column | Meaning |
|---|---|
| `order_id` | One per order |
| `order_date` | When the order was placed |
| `customer_id` | Who bought. Retail customers start with `C`, wholesale accounts with `W` |
| `product`, `category` | What was sold |
| `quantity`, `unit_price`, `amount` | How many, the price of one, and the order total in rupees |
| `channel` | Store, Online, Marketplace or Wholesale |
| `city` | Where the order was delivered or sold |

## Where this comes from

**[Ask AI to Analyse Your Data](https://ask.thili.ai)** is part of the Learn Fast founder track, for
people who run a business or a team and use AI on the numbers without writing code.

## License

MIT © thili.ai — use these in your own training, change them, share them.
