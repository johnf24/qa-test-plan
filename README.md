### Summary

Benefits are being made contingent upon other benefits. If a plan is contingent upon another plan or a plan type, then it is or is not offered based upon the configuration of the election it is contingent upon.

### Requirement Tests
 
#### New Hire Enrollment

[ ] Contingent Plan is offered for a type of plan<br>
[ ] Contingent Plan is not offered for a type of plan<br>
[ ] Contingent Plan is offered for a specific plan<br>
[ ] Contingent Plan is not offered for a specific plan<br>

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class<br>
[ ] Contingent Plan is not offered for a plan type with a ineligible class type<br>
[ ] Contingent Plan is offered for a specific plan with a eligible class type<br>
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type<br>

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived<br>
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived<br>
[ ] All plans are offered for a plan type if it is Waived<br>


#### Work Service Event

[ ] Contingent Plan is termed for a specific plan with a eligible class type<br>
[ ] Contingent Plan is not termed for a specific plan with an eligible class type<br>

#### Self Service Life Event

[ ] Contingent Plan is offered for a type of plan<br>
[ ] Contingent Plan is not offered for a type of plan<br>
[ ] Contingent Plan is offered for a specific plan<br>
[ ] Contingent Plan is not offered for a specific plan<br>

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class<br>
[ ] Contingent Plan is not offered for a plan type with a ineligible class type<br>
[ ] Contingent Plan is offered for a specific plan with a eligible class type<br>
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type<br>

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived<br>
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived<br>
[ ] All plans are offered for a plan type if it is Waived<br>

#### Open Enrollment

[ ] Contingent Plan is offered for a type of plan<br>
[ ] Contingent Plan is not offered for a type of plan<br>
[ ] Contingent Plan is offered for a specific plan<br>
[ ] Contingent Plan is not offered for a specific plan<br>

-	Class Type

[ ] Contingent Plan is offered for a plan type with a eligible class<br>
[ ] Contingent Plan is not offered for a plan type with a ineligible class type<br>
[ ] Contingent Plan is offered for a specific plan with a eligible class type<br>
[ ] Contingent Plan is not offered for a specific plan with an ineligible class type<br>

-	Waive

[ ] Contingent Plan is not offered for a plan type if that plan type is Waived<br>
[ ] Contingent Plan is not offered for a specific plan if a plan type is Waived<br>
[ ] All plans are offered for a plan type if it is Waived<br>


### Regression Tests

[ ] Feature is available with feature toggle contingent_benefits<br>
[ ] Feature is not available without feature toggle contingent_benefits<br>
[ ] All plans are offered if no contingent plans exist<br>


### Edge Case Tests

[ ] A plan may be either contingent on several specific plans<br>
[ ] If there a two contingent plans then both are offered<br>
[ ] If a contingent plan is contingent upon another contingent plan then both plans are offered<br>
