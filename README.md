## Context
 
At the company, the procurement team receives **construction award contracts** from contractors and suppliers. Each one sends them in their own format (a PDF, a CSV, an export from their ERP) and with their own way of naming things.
 
On the other side there is the **work items catalog** (*banco de partidas*): the internal catalog of construction work units, with code, description, unit and reference price. It is the source against which, in principle, whatever is being invoiced should be checked.
 
A procurement manager sums it up like this:
 
> *"I get contracts from everywhere and in every format. What I need is to know whether what I'm about to sign is in line with what we normally pay, and which line items I should look at closely before giving the OK. Right now one person does this by hand, contract by contract, and they can't keep up."*
 
## Available data
 
- `banco_de_partidas.xlsx`: the reference catalog. It is a real export, with all the noise of real data.
- `contratos/`: 7 award contracts for 7 different projects, exactly as they arrived, neither cleaned nor organized.
## The goal
 
Build a tool that is genuinely useful to the procurement person in their day-to-day work. The guiding question for the project is: **if this person spent five minutes using the tool, what decision could they make better than they can today?**
 
Specifically, the tool should help them:
 
- Know whether a contract is in line with the company's usual prices.
- Identify which line items deserve a detailed review before approval.
- Reduce the manual work of reviewing contracts one by one.
## Considerations
 
- **Non-technical user:** the result must be clear and usable by someone in procurement, with no programming knowledge.
- **Heterogeneous data:** contracts arrive in different formats and naming conventions, and the catalog contains noise. Part of the work is understanding and handling those inconsistencies.
- **Works for real:** the solution has to work with this specific data, not remain a theoretical approach.
- **Focused scope:** the priority is to solve first what brings the most value, and to document what is left out and what would be done in a next phase.
- **Explicit assumptions:** where information or context is missing, reasoned assumptions are made and documented.
