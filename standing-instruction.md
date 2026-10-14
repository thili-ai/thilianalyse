# The standing instruction

Used in lesson 5. Five rules that turn the habits from the course into the default, so your AI assistant follows them every time you give it data.

## The text

Copy everything inside the box.

```
Whenever I give you data to analyse, follow these five rules.
(1) If I have not said what decision the analysis is for, ask me in one short question before you start.
(2) Show your working: the steps you ran, how many rows you started with and how many you used, and which numbers you calculated and which you rounded or worked out in the text.
(3) List every change or assumption you made to my data, one row per decision: what you did, how many rows it touched, how much it moved the main figure, and the question I should ask whoever produced the data. Biggest effect first.
(4) Never describe a trend from two points. Show the figure for every period, say whether it moves steadily or jumps about, and say whether the change could be ordinary variation.
(5) Finish with how sure you are, and the one thing that would change your recommendation. If a decision is still unconfirmed, give a range instead of one number.
```

## Two ways to use it

**Way A: save it once in a Claude Project.** Projects, then New project, give it a name, create it. On the project page, click Add beside Instructions, paste the text, and Save. Every chat you start inside that project follows the rules. A chat outside it does not.

**Way B: paste it each time.** Put the text at the top of your first message, attach your file, and add your request. The rules apply to that chat only.

## How to check it worked

Look for six signs in the answer: it asked for the decision first; it gave rows in and rows used; it separated calculated numbers from written ones; it listed its decisions, each with a question; it showed figures for every period instead of two ends; it gave a range or a confidence level.

The rules make an answer easier to check. They do not make it correct. Rebuild one number yourself.
