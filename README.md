### Summary

Benefits are being made contingent upon other benefits. If a plan is contingent upon another plan or a plan type, then it is or is not offered based upon the configuration of the election it is contingent upon.

### Requirement Tests
 
#### New Hire Enrollment

[ ] Contingent Plan is offered for a type of plan
[ ] Contingent Plan is not offered for a type of plan
[ ] Contingent Plan is offered for a specific plan
[ ] Contingent Plan is not offered for a specific plan

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class 
[ ] Contingent Plan is not offered for a plan type with a ineligible class type
[ ] Contingent Plan is offered for a specific plan with a eligible class type
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived
[ ] All plans are offered for a plan type if it is Waived


#### Work Service Event

[ ] Contingent Plan is termed for a specific plan with a eligible class type
[ ] Contingent Plan is not termed for a specific plan with an eligible class type

#### Self Service Life Event

[ ] Contingent Plan is offered for a type of plan
[ ] Contingent Plan is not offered for a type of plan
[ ] Contingent Plan is offered for a specific plan
[ ] Contingent Plan is not offered for a specific plan

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class 
[ ] Contingent Plan is not offered for a plan type with a ineligible class type
[ ] Contingent Plan is offered for a specific plan with a eligible class type
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived
[ ] All plans are offered for a plan type if it is Waived

#### Open Enrollment

[ ] Contingent Plan is offered for a type of plan
[ ] Contingent Plan is not offered for a type of plan
[ ] Contingent Plan is offered for a specific plan
[ ] Contingent Plan is not offered for a specific plan

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class 
[ ] Contingent Plan is not offered for a plan type with a ineligible class type
[ ] Contingent Plan is offered for a specific plan with a eligible class type
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived
[ ] All plans are offered for a plan type if it is Waived


### Regression Tests

[ ] Feature is available with feature toggle contingent_benefits
[ ] Feature is not available without feature toggle contingent_benefits
[ ] All plans are offered if no contingent plans exist


### Edge Case Tests

[ ] A plan may be either contingent on several specific plans
[ ] If there a two contingent plans then both are offered
[ ] If a contingent plan is contingent upon another contingent plan then both plans are offered
