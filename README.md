# RecruiterRepo

This is a proof of ocncept to confirm the idea of matching job descriptions to github repo works. In this snippet, the job description inputincludes mention of specific packages which is usually not the case in job listings. To address this, we could have used Open AI's API to generate a list of package names and used these as the criteria.

### Technical design
Each github profile is turned into a job match percentage by parsing each repo under the profile and mapping the packages, style if code, language used to those requested in the job listing.
