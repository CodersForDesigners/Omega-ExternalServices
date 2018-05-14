# Omega-ExternalServices


## Enquiries
An enquiry can be in one of many phases – Verify, Allocate, Negotiate and Close.

Each phase has a timeout duration following which the enquiry is auto-reassigned or brought to the attention of the manager.

Each type of saleperson user has a upper limit of enquiries per phase that they are allowed to manage.

## Events
1. "Customer No Response": When a salesperson set a "Customer No Response" status on an enquiry.
	The enquiry is re-assigned.
	
2. "Agent No Response": When a salesperson does makes no progress or does not pursue an enquiry for the cycle time of that phase. More specifically, this involves (a) Reject-ing, (b) Setting a "Customer No Response" status, or (c) Ticking all the qualifiers
The enquiry is re-assigned. Once re-assigned, the timeout is reset.
	
3. "Transfer": When a salesperson re-assigns an enquiry to another salesperon or class of salespeople.
	The enquiry is re-assigned.

## Resource allocator
Evenly distributes enquiries to all the salespeople alphabetically.

If a saleperson is saturated, then she/he is exempt from consideration.

A user who is on leave is not assigned an enquiry.
