<h1>ASSIGNMENT THREE: ASBESTOS PERMITS DATA DIARY</h1>
<b>Matt Reynolds</b>
<b>July 2019</b>


Saved Sheet as: Allegheny Asbestos Permits_071619

Created a new sheet and renamed it “Transformations.”

Saved Allegheny Allegheny Asbestos Permits_Transformations_071619 as Excel Workbook

Select all >Paste Special>Values into Transformation Sheet 

Where applicable manually copied and pasted addresses from Column B into blank spaces on Column C 

Column C Edit >Find>AVENUE and REPLACE with AVE (14 Replacements)

Column C Edit >Find>STREET and REPLACE with ST (10 Replacements)

Column C Edit >Find>ROAD and REPLACE with RD (11 Replacements)

Column C Edit >Find>ROAD and REPLACE with RD (11 Replacements)

Column C Edit >Find>ROAD and REPLACE with RD (1 Replacements)

Insert>Column F to created new column. Named it cleaned_address

D2 Formula =TRIM(C2) to eliminate spaces found in C column addresses.

Insert>Column G to create new column. Named it cleaned_zip

G2 Formula =LEFT(F2,5) to shift zip to the left of column

Insert>Column H to create new column. Named it consolidated_address

H2 Formula =CONCATENATE(D2, ", ", E2, ", ", G2)






















