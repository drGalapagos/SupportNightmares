# SupportNightmares
A collection of support nightmares with evidence and analysis of behavior

## Motivation
Unpleasent experiences with various tech support teams require understanding factors contributing to these undesriable situations (from the perspective of the paying user).
Relevant factors:
- Power imbalance,
- Abuse of monopolistic advantages,
- Effort required to change cervice provider (customer lock-in),
- Lack of competence at support teams,
- etc.

## Suggestions for improvements / activities to counter unfair handling of customers
- Customer rights organizations
- etc.

## How to add your contributions
1. Make a directory named according to the following structure based on your case:
    - YYMMDD_NameOfContributor_XXX, where
      - YYMMDD: start date of the support request / nightmare expressed as the last two digits of the year, month (two digits), day (two digits),
      - NameOfContributor: your github username,
      - XXX: number of existing contributions in the given issue category + 1 (three digits),
      - blocks separated by "_".

2. Make a directory named "assets" inside the directory created in Step 1. for any supporting documents, files, pictures, recordings, etc. that may be relevant for your case.

3. Create a main .md file using the same name as for the directory created in Step 1. This is the main file for the instance of your concrete case containing the details of the events.
   - Provide short factual descriptions of the events in this .md file including:
     - Short description of case providing a big picture,
     - Start date of process / support request,
     - Date of latest update to the request,
     - Number of interactions with support to date,
     - Current status of the case (e.g. unsolved / solved in such and such a way / gave up, etc..).
     - For an example see the following case involving a legitimate refund request being blocked by the support team: [Google Ads Refund Nightmare](Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001.md)
   - Add any supporting documents using (relative?) links.
   - Etc. 

4. Place the directory and .md file(s) in the appropriate folder based on the following structure:
   - **Entities:** these are providers of various services (e.g. companies, organizations, etc.). They represent the top-level organizations that you had an issue with. To solve the issue you encountered you requested help from the support team of these entities.
     - If the entity you had an issue with is already present in this directory, chose that one! If the entity is not yet present, add it by defining its name e.g. *Google*.
   - **Sub-units:** the next level is a sub-unit within the previous entity representing a branch, department or a smaller unit within the entity.
     - If the sub-unit of the entity you had an issue with is already present in this directory, chose that one! If the sub-unit of the entity is not yet present, add it by defining its name e.g. *Ads* (sub-unit within Google).
   - **Issue:** This level represents the general type of your issue.
     - If the general type of issue is already present in this directory, chose that one! If the general type of issue is not yet present, add it by defining its name as succinctly as possible. Use max 5 words without spaces with the first letter of each word capitalized, e.g. *Refund, BlockedAccount, DiscrepancyInstructionsVsInterface*, etc.
   - **Concrete case:** Place your directory (created in Step 1. and 2.) and your .md file(s) in this directory.    
       
5. *(Optional)* If you would like to provide an in-depth, subjetive analysis of the process, create another .md file and name it using the same name as for the directory (Step 1.) and for the main .md file (Step 3.), then append the word "analysis" with a "_"  after the last 3 digit number block. Example: *[`250228_drgalapagos_001_analysis.md`](Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_analysis.md)*














