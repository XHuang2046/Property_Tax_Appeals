Cook County Assessor’s Office: ‘Appeals’ Data Dictionary  

pin14  = unique Permanent Identification Number for each property.
         All PINs are 14 digits: 2 digits for area + 2 digits for sub area + 2 digits for block + 2 digits for parcel + 4 digits for the multicode  
         https://www.cookcountyclerk.com/service/about-property-index-number-pin
         
tri = geographic location variable divided into 3 areas: Chicago, Northwest suburb, southwest suburb
pdir = abbreviation for direction in property street address (N,S,E,W, etc.)
pstreet = property street name
pcity = property city
tcity = taxpayer mailing address city
condo = property classified as condominium or non-condominium
av1 = first pass assessed value.  Assessed value from CCAO prior to any appeal
value = property’s actual sale value when it sold
taxes = amount of annual taxes paid by property owner
homeowner = homeowner occupied flag
white = percentage of associated property census tract inhabitants identified as White on US census
black = percentage of associated property’s census tract inhabitants identified as Black on US census
hispanic = percentage of associated property’s census tract inhabitants identified as Hispanic on US census
asian = percentage of property’s census tract inhabitants identified as Asian on US census
medhinc = median household income of the property’s census tract
poverty = percentage of property’s census tract inhabitants earning below the federal poverty rate 
college = percentage of eligible adults in the property’s census tract with a 4 year college degree
squarefoot = building square footage
beds = Number of bedrooms in the property, defined based on building squarefoot and the judgement of the person in the field.
walkscore = walkability score on a 100 point scale, using property distance to amenities. https://www.walkscore.com/methodology.shtml
walkfac = walkscores transferred into a 4 level category variable ranging from “car-dependent” to “Walker’s Paradise” https://www.walkscore.com/methodology.shtml
appeal = dollar amount deducted from assessed value after property owner appealed. If NA there was no appeal. 
elem_score = Greatschools rating for closest public neighborhood elementary school (distance measured with haversine formula) Greatschools Rating based on the Test Score Rating, Student or Academic Progress Rating, College Readiness Rating, and Equity Rating)  https://www.greatschools.org/gk/ratings/
high_school_score = Greatschools rating for closest public neighborhood high school (distance measured with haversine formula) Greatschools Rating based on the Test Score Rating, Student or Academic Progress Rating, College Readiness Rating, and Equity Rating)  https://www.greatschools.org/gk/ratings/
avg_sch_score = average of associated elementary and high school Greatschools ratings

