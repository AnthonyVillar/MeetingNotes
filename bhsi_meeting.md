# BHSI CLAIMS 

-- NON MEDICAID FUNDED CLAIMS 

OMH/OAS -- underinsured claims uninsured 

process : claim submited and reviewd to determin whos paying + other approvals 

STAKE HOLDERS 
-dbhids ppm managases allocations contracts 
-providers bill for services under a fee for service 
-state office of mental health and substance abuses services - regulatory basis for managing allocations consumers providers and services 
-xeohealth use same provider ids as CBH does 

### components of a claim -- provider, person, service needs all 3 -- if component is missing then need to correct 
- data is coming directly from the state


#### person 
- county and state use the same anonymous billing codes 
mhx number -- nmber is not altered on our side mhx number should be kept as VARCHAR 
anonymous billing has a seperate set of codes for billing 
xeo -> state adjucation -> rejections -> comeback to us-> we try and resolve 
--rejections usually occur do to timing issues
-- 

## datamarts we have only paid claims -- which is approved to be paid mainstay has the paid ie has been adjucated
-- ppm has the data where the actual payments are out

-- bhsi wants to see what was paid and was approved?

-- BHSI -- IS THE LOCAL SYSTEM FOR MANAGING PEOPLE IN OASIS SYSTEM clinicians access a state system to determine eligibility 
cardholder  ADE - is already adjudcated 

Eligibility 
-	geting data from the state 
- send inquiry to state with what is available to that person
- 271 form people outgoing -> services for those people incoming with eligiblity 

need an eligiblilty check that checks everywhere to ensure that they don't have eligilty elsewhere 

private insurance is checked on the providers side 

eligibilty is calculated at time of adjudication 

mhx number must be in hcsis

project one plus contracts services some philly services funded anonymoously but state not


promise enrollment -- locations , provider type, 9000 is a dummy value for location currently 

xeo gives -> jiffy number with locations -> jiffy logged on our end --> locations resolved -->submitted

provider --> register -> get provider type -> revalidate every 5 years -> location changes ->

from contracts 
sud -> ties to services 

## SErvices 

provider budject -> contract work statement -> ppm manages contracted services -> hcqa collaborates with ppm to ensure that contracted information is in line with state promise
-> hcqa maps to generate report of services
SUD validat














anonymous billing in Philadelphia can be used for any service that is apart of contract with the city


## NO COST


## PAID 