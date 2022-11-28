# Exploration
[Design Doc](/designDoc.md) | [Discovery](/discovery.md) | Exploration | [Go to market](/goToMarket.md)
  
---
## Ideation
Keep the refined problem statement in mind when exploring solutions:  
In what ways might we help Hughes users feel informed, secure and untroubled, in order to purchase their product & purchase a warranty?

---
### Hypotheses
Get help with a [hypothesis framework](https://docs.google.com/forms/d/1YJZIdEaZPN2K59O-gOHGNW2kXPRtLsPwiM32BSd0pHI/edit?usp=sharing).
  
| If | then | due to |
| --- | --- | --- |
| The warranty is integrated into the purchase journey in a seamless, informative, and reassuring manner | Users will purchase the warranty | It being an easy action that adds value to the purchase |
  
---
### Artifacts
Drawings, surveys, flow charts, prototypes. UI, code repos, and more.  

| Date | Creator | Artifact |
| --- | --- | --- |
| 24/11/22 | Growth Design | [Sniper Links](https://growth.design/case-studies/sniper-link) |
| 24/11/22 | Argos - Example | [Side tab](https://www.argos.co.uk/product/7950445?clickPR=plp:1:149) |
| 24/11/22 | Currys - Example | [Side tab](https://www.currys.co.uk/products/hoover-hwash-300-h3w410tagge-nfc-10-kg-1400-spin-washing-machine-graphite-10240395.html) |
| 24/11/22 | John Lewis - Example | [Further explanation and outbound links](https://www.johnlewis.com/bosch-serie-4-wan28281gb-freestanding-washing-machine-8kg-load-1400rpm-spin-white/p5142516) |
| 24/11/22 | AO - Example | [Pop-up / More info page redirect](https://ao.com/product/wth85222gb-bosch-series-4-heat-pump-tumble-dryer-white-84548-126.aspx) |
| 25/11/22 | JC | [Sketches/Ideation](https://www.figma.com/proto/UEk3HJKgCiHUskfMfnct2p/J-Clohessy_D%26G-Stage-2-Test?page-id=14%3A148&node-id=40%3A3072&viewport=325%2C-88%2C0.05&scaling=scale-down) |
| 28/11/22 | JC | [Concept 1 prototype](https://www.figma.com/proto/UEk3HJKgCiHUskfMfnct2p/J-Clohessy_D%26G-Stage-2-Test?page-id=40%3A158&node-id=40%3A2595&viewport=339%2C-361%2C0.2&scaling=scale-down-width&starting-point-node-id=40%3A2595) |
| 28/11/22 | JC | [Concept 3 prototype](https://www.figma.com/proto/UEk3HJKgCiHUskfMfnct2p/J-Clohessy_D%26G-Stage-2-Test?page-id=40%3A158&node-id=46%3A6655&viewport=339%2C-361%2C0.2&scaling=scale-down-width&starting-point-node-id=46%3A6655) |

---
#### Solution brainstorm
For when multiple ideas to solve the problem statement are needed. Use the table below or this [google sheet](https://docs.google.com/spreadsheets/d/1QCye8bQ4Nvg6S0Vlzem7flVsTL73BDOMhGFVaLgBE98/edit?usp=sharing).

| Person | Concept |
| --- | --- |
| JC | **Widget 1** Warranty shown in expanding box on appliance selection. Box expands like Paypal one, showing top tier information. Read more link either opens popup box, or new window in new tab with full information |
| JC | **Widget 1** Warranty can also be shown, alongside price in services tab? Again with a read more link |
| JC | **Widget 1** Could warranty have its own tab? More space for explanation |
| JC | **Widget 1** More invasive, but could have some kind of interactive badge over the product, as they have in some pages. Opens up a pup up window or anchor links to tabbed warranty section below |
| JC | **Widget 1** Could people opt in at this stage or the Basket item added stage, alongside other services? Opt in here would mean after product purchase they are taken to a reconfirmation / direct debit setup page automatically. |
| JC | **Widget 2** Green CTA section  with a line of two re-iterating warranty value and price. This can lead to full terms / signup page.|
| JC | **Widget 2** If opt in was given earlier (Widget 1), can just have CTA to complete warranty set up > through to setup page. |
| JC | **Widget 2** If opt in was given earlier (Widget 1), can just have CTA to complete warranty set up > through to setup page. |
| JC | **Widget 2** Can warranty be included in confirmation email? Danger of it not being checked. Sniper link to email? |
| JC | **Widget 2** Can the order progress bar be amended to include an "extended warranty" tab at the end? "Continue for warranty options" button|
| JC | **Widget 2** Can an above the fold ad space be included for the warranty on the confirmation page? Between the "Washer on its way header and the progress bar? Lrg leaderboard? |
| JC | **Widget 2** Anchor link somewhere near top of order confirmation page. More info below and cta through to signup website/domain. |

### Grouped concepts
| Ref | Concept |
| ---| --- |
| 1 | Info is shown on the left, same as paypal and expands, giving warranty info. On confirmation page, similar expandable section reiterates main points and links out to setup page. Include warranty tab also to explore. |
| 2 | Info is shown on the left again but with opt-in at this stage. Opt in repeated on additional services page. On confirmation page, CTA links out to finish purchasing warranty. |
| 3 | Info is shown on the left again but in less details at this stage. Progress bar is amended to include warranty tab at the end, and "warranty options" button is included, as per previous checkout pages. This brings user to a new page where they receive full info on the warranty, and the chance to opt in / out. In = taken to setup page. Potentially requires least cognitive load on user. Can be on same server? |
  
---
#### Concept selection matrix
For ranking solutions against the right problems. Use the table below or this [google sheet](https://docs.google.com/spreadsheets/d/1QCye8bQ4Nvg6S0Vlzem7flVsTL73BDOMhGFVaLgBE98/edit?usp=sharing).
| Needs | Grouped concept 1 | Grouped concept 2 | Grouped concept 3 |
| --- | --- | --- | --- |
| The journey is easy | 1 | 1 | 1 |
|The journey is trustworthy | 0 | 0 | 1 |
| The journey is transparent | 1 | 1 | 0 |
| The journey explains the product | 0 | 0 | 1 |
| Cost/Difficulty | 1 | -1 | 0 |
| Wow factor | 0 | 0 | 1 |
| Elegance & beauty | 0 | 0 | 1 |
| Scalability | - | - | - |
| Totals| 3 | 1 | 5 |

**Conclusion - A/B test concept 1 and 3 prototypes on users**
  
---
## Validation

---
### Test Plan
Use the following questions to understand what you need to learn from your user test.  

**General**  
What business challenges are being addressed?  
What questions are being answered?  
What needs to be understood from this study?  

**Users**  
Who might be using this part of the product, experience, service, app, site, etc?  

**Goals**
What specific questions need answers?  
How will the insights be used from this study?  

---
### User testing results
| Version | KPI 1 | KPI 2 |
| --- | --- | --- |
|  |  |  |

---
## Notes
- Can appliance / address details be transferred to D&G owned website? Assuming yes. 
- How beneficial is the warranty to hughes? How much modification to current journey is too much?
- What to do when multiple items are added to basket but only some have warranty option?
- Concept 3 - address and email need to be ticked for user to continue to warranty purchase site. Can info be transferred over?

---
Next is [go-to-market](/goToMarket.md)
