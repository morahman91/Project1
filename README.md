# Project1
https://teams.microsoft.com/l/meetup-join/19%3ameeting_OGIyZTc5ZjYtNjg0OC00NmEzLThjOTQtNzExM2JhOTg2ZTEz%40thread.v2/0?context=%7b%22Tid%22%3a%223b06518d-2bac-4bbf-95d4-d731899ce4e2%22%2c%22Oid%22%3a%22882977a3-f110-4bd3-9fa1-e7bc56bbe660%22%7d
Quality Characteristics (If applicable):
Requirements Acceptance Criteria:
(Guide to writing Requirements: Major distinct Components should include FR, NFR, and BR – discreet requirements… that testable. If the testing seems multipart, then break the Requirement)
1.	Intent: The intent is UI to reflect that the output is private industry only: “Chart 10. Incidence rates by size class, private industry”. to 
1.	Chart 10. Incidence rates by size class, private industry update 
•	 National
•	Regional
•	State
2.	SuperuserAsk Question:
•	
3.	Chart 10. Title update in UI: 
3.1.	Path: Reports tab->Report Type: Nonfatal Occupational Injuries and Illnesses by Industry ->State selection -> Table Type: Summary Charts -> Chart10. Incidence rates by size class.
	
3.2.	Chart 10. Incidence rates by size class, industry tile should be updated to ‘Chart 10. Incidence rates by size class, private industry ‘in UI.
	
3.3.	Design Screenshot.

Table 2. Pcts - Worker characteristics by major industry sector


Description
As a Profiles user, I need to have the following changes made to Table 2:



Acceptance criteria: 

Publication Report Table 2 should get generated based on the selected biennial SY
Generate table by each case type (DAFW, DJTR, DART)
Update table title to reflect case type selected
Update all applicable footnotes
Update table title to reflect biennial year: "YYYY-YYYY"
Update stored procedure to reflect series break from CS to CB effective SY 2023 onward


to accommodate multi-year (biennial) SOII case and demographic estimates starting with outputs for the 2021-2022 biennial reference years (RY).







Following are the titles updated in Table 2. Excel downloaded reports if the user selects the multi-year (biennial) and corresponding Case types.

Case type -DAFW: New output title: Table & Chart:
Table 2. Percent distribution of nonfatal occupational injuries and illnesses involving days away from work (DAFW) by selected worker characteristics and major industry sector, <ownership>, <state>, YYYY-YYYY

Example: Table 2.  Percent distribution of nonfatal occupational injuries and illnesses involving days away from work (DAFW) by selected worker characteristics and major industry sector, Alabama, 2022-2023.


Case type -DJTR: New output title: Table & Chart:
Table 2. Percent distribution of nonfatal occupational injuries and illnesses involving days of job transfer or restriction (DJTR) by selected worker characteristics and major industry sector, <ownership>, <state>, YYYY-YYYY


Case type – DART: New output title: Table& Chart:
Table 2.  Percent distribution of nonfatal occupational injuries and illnesses involving days away from work, job transfer, or restriction (DART) by selected worker characteristics and major industry sector, <ownership>, <state>, YYYY-YYYY
