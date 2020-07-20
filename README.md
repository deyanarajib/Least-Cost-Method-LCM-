# Least-Cost-Method--LCM-
 A method for solving Transportation Problem

Least Cost Method (LCM) Steps (Rule)
Step-1:	Select the cell having minimum unit cost cij and allocate as much as possible, i.e. min(si,dj).
Step-2:
	a. Subtract this min value from supply si and demand dj.
	b. If the supply si is 0, then cross (strike) that row and If the demand dj is 0 then cross (strike) that column.
	c. If min unit cost cell is not unique, then select the cell where maximum allocation can be possible
Step-3:	Repeact this steps for all uncrossed (unstriked) rows and columns until all supply and demand values are 0.

Source: https://cbom.atozmath.com/example/CBOM/Transportation.aspx?he=e&q=lcm
