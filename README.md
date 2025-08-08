# 👨‍💻 SupportNightmares 👻 🧟 🧛
A collection of SupportNightmares (unsolved problems / unpleasent experiences / unfair treatments, etc.) generated during interactions with various customer support teams while they were doing their best to solve problems blocking their paying customers from achieveing their goals. The cases are supplemented with proofs and analyses of the interactions.

## Motivation
Unpleasant experiences with various support teams exist. Such experiences may be shared by a large proportion of the population, but data on the global prevalence of the problem is scarce, scattered and disorganized. A large proportion of unpleasant experiences (e.g. unsolved cases, unfair handling of the case, decision against the interest of the user, failure to provide actual support, funds withheld illegally, etc.) may go unnoticed and unreported, due to various factors (e.g. time and effort required for documenting the events, unfairness just below a critical threshold, loss of motivation to persevere in strong headwind, opportunity costs, etc.). 

Data collection and sharing the experiences is motivated by the aforementioned considerations to enable:
- building a better overview of the prevalence of the problems,
- estimating the costs / losses more accurately on a global scale,
- building a better understanding of the tactics used by rogue support teams,
- developing strategies and actions to protect people against unfair treatment,
- orgnaizing collective actions aimed at balancing power imbalances when such imbalance is abused.

It is hoped that by having a better understanding through sharing the experiences, it will be possible to develop countermeasures and solve these meta-issues which exists on top of the underlying issues which triggered the initial support request.

## How to share your experiences / add your contributions

**1. Save and collect all your supporting documents related to the case.**
  - Supporting documents may include any files such as pictures, recordings, screenshots, message exchanges, etc. that are relevant for your case and provide evidence of the process.

   > [!TIP]
   > Remove any [`personally identifiable information`](https://en.wikipedia.org/wiki/Personal_data)(PII) that you don't want to publicly disclose with the documents of the case. PII may include: (1) any information that can be used to distinguish or trace an individual's identity, such as name, social security number, date and place of birth, mother's maiden name, or biometric records; and (2) any other information that is linked or linkable to an individual, such as medical, educational, financial, and employment information" including meta-data stored in digital files.
   
**2. Compile all the supporting documents into a temporary case file and provide some explanation about the case and the events.**
  - The temporary case file ideally contains the following details to provide readers with a good overview of the events of the case:	
    - A short summary (~ 1 page) of the entire process at the beginning of this document including:
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
  
   > [!IMPORTANT]
   > While the files and supporting documents related to your case can be in any language, please use English for the temporary and main case file (e.g. when adding a summary, comments to the Events, additional details, etc.).

### Customize the template folders and the `.md` files within the [`Template`](./Template/) folder as follows:

**3. Copy / fork the [`YYMMDD_NameOfContributor_XXX`](./Template/YYMMDD_NameOfContributor_XXX) folder and rename it according to the following structure based on your specific details:**
- `YYMMDD_NameOfContributor_XXX`, where the 3 blocks of information are separated by `_`'s. The 3 blocks are as follows:
  - `YYMMDD`: start date of the support request / nightmare expressed as the last two digits of the year, the month and the day,
  - `NameOfContributor`: your github username or any other name,
  - `XXX`: ***number of your previous*** contributions in the given issue category `+ 1` (three digits).
	
- *Example of a folder for a concrete case: [`250228_drgalapagos_001`](./Entities/Google/Ads/Refund/250228_drgalapagos_001)*

**4. Use the [`caseResources`](./Template/YYMMDD_NameOfContributor_XXX/caseResources) folder inside the [`YYMMDD_NameOfContributor_XXX`](./Template/YYMMDD_NameOfContributor_XXX) folder to share all supporting documents related to your case.**
	
- *Example: [`ExampleScreenshot.jpg`](./Template/YYMMDD_NameOfContributor_XXX/caseResources/ExampleScreenshot.jpg) can be replaced with a screenshot of an event in the process.*

**5. Create a <ins>main case file</ins> from the temporary case file compiled in Step 2. by renaming the [`YYMMDD_NameOfContributor_XXX_0_case.md`](./Template/YYMMDD_NameOfContributor_XXX/YYMMDD_NameOfContributor_XXX_0_case.md) template case file using your specific details as defined in Step 3. Don't modify the '_0_case' part of the filename. Copy-paste all the details and supporting documents of your case from the temporary case file compiled in Step 2. into this <ins>main case file</ins>.**
	
- *Example: [`250228_drgalapagos_001_0_case.md`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_0_case.md) presents a Google Ads Refund Nightmare involving a legitimate automatic refund process blocked by the support team.*

####6. Optional step if you would like to provide an in-depth, subjective analysis of the process: rename the [`YYMMDD_NameOfContributor_XXX_1_analysis.md`](./Template/YYMMDD_NameOfContributor_XXX/YYMMDD_NameOfContributor_XXX_1_analysis.md) file according to your specific details as defined in Step 3. while leaving the '_1_analysis' part as it is.
- Use this file for:
  - Analysing the events and your experiences through the lens of some theoretical framework.
  - Identifying patterns of behavior that were especially problematic from the support team.
  - Providing suggestions for others how to avoid such cases.
  - Providing suggestions for organisations how to improve the performance of their support teams so that customers may actually benefit from the "support".
   
- *Example: [`250228_drgalapagos_001_1_analysis.md`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_1_analysis.md) presents a personal analysis of the Google Ads Refund Nightmare using principles from relevant fields of study.*

**7. Place the folders and the `.md` file(s) in the appropriate folder based on the following structure:**
  - **Entities:** are providers of various services (e.g. companies, organizations, etc.). They represent the top-level organizations that you had an issue with. To solve the issue you encountered, you requested help from the support team of one of these entities.

      - If the entity...

	    - you had an issue with is already present in this folder, choose that one!
	    - is not yet present, add it by defining its name.

	  - *Example: list of [`Entities`](./Entities) already present in the folder structure.*

  - **Sub-units:** the next level represents sub-units within the entity such as a branch, department or a smaller meaningful unit.

      - If the sub-unit of the entity...

	    - you had an issue with is already present in this folder, choose that one!
	    - is not yet present, add it by defining its name.

	  - *Example: list of [`Sub-units`](./Entities/Google) already present within an entity.*
	
  - **Issue:** this level represents the general type of your issue.

      - If the general type of issue is...
	  
	    - already present in this folder, choose that one!
	    - not yet present, add it by defining its name as succinctly as possible. Use max. 5 words without spaces with the first letter of each word capitalized. The following are valid names for issues: *BlockedAccount, DiscrepancyBetweenInstructionsVsInterface, Refund, DefectiveProduct*, etc.
	
	  - *Example: list of [`Issues`](./Entities/Google/Ads) already present within a sub-unit of an entity.*
	
  - **Case:** this level represents your concrete case.
    - Place your folders and `.md` file(s) created in Steps 3-6. describing the case that is worth sharing into the appropriate folder representing the general type of issue you tried to solve by asking for help from the support team.
	
      - *Example of a concrete case where:*
        - *the [`250228_drgalapagos_001`](./Entities/Google/Ads/Refund/250228_drgalapagos_001) case folder contains:*
          - *a [`caseResources`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/caseResources) folder for supporting documents such as the [`250228_00_01.jpg`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/caseResources/250228_00_01.jpg) file,*
          - *the [`250228_drgalapagos_001_0_case.md`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_0_case.md) <ins>main case file</ins>  documenting the events in the case,*
          - *along with the [`250228_drgalapagos_001_1_analysis.md`](./Entities/Google/Ads/Refund/250228_drgalapagos_001/250228_drgalapagos_001_1_analysis.md) analysis file  dissecting the case.*
		  
**8. Send a pull request / add your contributions to the main repository:**
  - Finalize your contribution and share it with everyone by adding it to the main repository.
  - Indicate if you want your contribution to be processed further into a blog post or any other artifact or send a ready-to-post document linking to all the resources used in the analysis.


## Contributions and suggestions are welcome 🙌 and highly encouraged 💪!










