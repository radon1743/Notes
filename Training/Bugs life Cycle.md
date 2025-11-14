### Defects or Bugs life cycle in Software Testing

Defect is mismatch of expected result and actual result.

Defect life cycle is defect identification to closed into project
[[Bug life cycle.canvas|Bug life cycle]]
![[Bug life cycle.canvas]]
## Importance of defect logging 
- systematic approach to identifying and documenting issues encountered during testing or prod env
- Maintain transparency, facilitate communication and ensure accountability
- Might help to find the root cause of the defect and prevent future recurrences

# Best practices
1) Clear and descriptive description 
	- Clear and concise details, steps to reproduce, expected behaviour, actual behaviour, environment details and any error messages 
2) Assign severity and Priority 
3) Capturing comprehensive logs (Browser logs, screen shots, Network logs, Video)
4) Utilising defect tracking tools (collaboration, visibility throughout the defect's life cycle )
5) regular updates and follow-ups

Better Bugs extension (simplifies bus reporting by allowing users to the screen )


# Defect Management process

1) Discovery of Defect 
Detect defects before the users detects it. The test manager judges if the defect is valid
2) Categorisation

	Critical: Immediate fix
	High: Main features
	Medium: minimal deviation from the product
	Low: Very Minor defect 
3) Fixing or defect resolution 
	Assignment -> Schedule fixing -> Fix the defect -> Report the resolution 
4) Verification
	verify the defects are actually resolved
5) Defect closure
	Closure testing , closed bugs
6) Defect Reports
	The test managers prepare and send the defect report to management team for feedback on defect management.

Defect rejection ratio = $(numberOfDefectsRejected/Total) *100$
Defect leakage ratio = $(number Of Defects Missed/Total defects of software) * 100$





