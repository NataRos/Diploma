# Graduate work


**To run the collection use** `newman`

    newman run Graduate\ work.postman_collection.json -e Graduate\ work.postman_environment.json

or import collection and environment into Postman.

**Tests checklist and results are placed into:** https://docs.google.com/spreadsheets/d/1iyl0_3fJdrNbkMuYfxQU__HRm4o89GqLtS8QI3uYTYk/edit?usp=sharing

**Comments:**
1. Several tests were not implemented due of time, mostly for details endpoint.

2. Many tests are failed because `/word` does not return syllables property, which is error from my point of view. For TC-1-7 `/word` even does not return results array which is definitely unexpected. 