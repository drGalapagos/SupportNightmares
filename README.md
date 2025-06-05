# SupportNightmares 👻 🧟 🧛
A collection of nightmares (unsolved problems / unpleasent experiences / unfair treatments, etc.) generated during interactions with various customer support teams while they were doing their best to solve problems blocking their paying customers from achieveing their goals. The cases are supplemented with proofs and analyses of the interactions.

## Motivation
Unpleasant experiences with various tech support teams motivate the analysis to better understand the factors contributing to these undesriable situations (from the perspective of the paying customer). Only by having a better understanding first, can we come up with ideas on how to counter and solve these meta-issues on top of the underlying issues which triggered the initial support request.
Some relevant factors:
- Power imbalance,
- Abuse of monopolistic advantages,
- Effort required to change cervice provider (customer lock-in),
- Lack of competence at support teams,
- etc.

## Suggestions for improvements / activities to counter unfair handling of customers
- Customer rights organizations
- etc.

## How to add your contributions
1. Make a directory named according to the following structure based on your specific details:
    - `YYMMDD_NameOfContributor_XXX`, where the 3 blocks of informatuon are separated separated by `_`'s. The 3 blocks are as follows:
      - `YYMMDD`: start date of the support request / nightmare expressed as the last two digits of the year, the month (two digits) and the day (two digits),
      - `NameOfContributor`: your github username,
      - `XXX`: number of existing contributions in the given issue category + 1 (three digits).
    - *Example: `250228_drgalapagos_001`*

2. Make a directory named `assets` inside the directory created in Step 1. for any supporting documents, files, pictures, recordings, etc. that may be relevant for your case.

3. Create a `.md` file using the same name as for the directory created in Step 1. This is the main file for the instance of your concrete case containing all the details of the events.
   - Provide a short summary (~ 1 page) of the entire process at the beginning of this .md file including:
     - Short description of case providing a big picture,
     - Start date of process / support request,
     - Date of latest update to the request,
     - Number of interactions with support to date,
     - Current status of the case (e.g. unsolved / solved in such and such a way / gave up, etc..).
   - For each message exchange / event you can provide the following details in a short format:
       - Event number,
       - Event date,
       - Event description,
       - Issue with event,
       - Step taken by customer,
       - etc.
   - Use relative links when adding supporting documents.
   - *Example: [`250228_drgalapagos_001.md`](Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001.md) presents a Google Ads Refund Nightmare involving a legitimate automatic refund process blocked by the support team.*

4. *(Optional)* If you would like to provide an in-depth, subjetive analysis of the process, create another `.md` file and name it using the same name as for the directory (Step 1.) and for the main `.md` file (Step 3.), then append the word `analysis` with a `_`  after the last 3-digit number block. *Example: [`250228_drgalapagos_001_analysis.md`](Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_analysis.md) presents a personal analysis of the Google Ads Refund Nightmare using key principles from various fields of study.*

5. Place the directory and the `.md` file(s) in the appropriate folder based on the following structure:
   - **Entities:** these are providers of various services (e.g. companies, organizations, etc.). They represent the top-level organizations that you had an issue with. To solve the issue you encountered you requested help from the support team of one of these entities.
     - If the entity you had an issue with is already present in this directory, chose that one! If the entity is not yet present, add it by defining its name. *Example: Google.*
   - **Sub-units:** the next level is a sub-unit within the previous entity representing a branch, department or a smaller unit within the entity.
     - If the sub-unit of the entity you had an issue with is already present in this directory, chose that one! If the sub-unit of the entity is not yet present, add it by defining its name. *Example: Ads (a sub-unit within Google dealing with ads).*
   - **Issue:** This level represents the general type of your issue.
     - If the general type of issue is already present in this directory, chose that one! If the general type of issue is not yet present, add it by defining its name as succinctly as possible. Use max 5 words without spaces with the first letter of each word capitalized, *Example: Refund, BlockedAccount, DiscrepancyBetweenInstructionsVsInterface, etc.*
   - **Concrete case:** Place your directory(ies) (created in Steps 1. and 2.) and the `.md` file(s) (created in Steps 3. and 4.) into this directory.














