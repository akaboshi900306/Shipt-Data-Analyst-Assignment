# Shipt-Marketing-Data-Analyst-Take-Home-Assignment
Shipt,  a grocery delivery unicorn company technical interview in marketing


There	are	four	data	sets	provided	with	these	questions.	For	the	most	part,	the	column	names	in	each	file	are	
self-explanatory,	but	for	“InterviewData_Activity.csv”,	here	is	a	quick	description	of	the	variables:
- userid (our	unique	identifier	of	a	member	in	the	database)
- date	the	member	last	placed	an	order
- age (an	integer	value)
- gender (“M”	or	“F”)	
- metropolitan_area (sample	metro	areas)
- device_type	used (Desktop,	Tablet,	or	Mobile)
- active (the	response	variable	and	a	binary	outcome, “0”	meaning	they	were	not	an	active	member	
and	“1”	meaning	they	were	active at	the	time	this	illustrative	data	was	generated)		

Questions	1,	2,	and	3 deal	with	“InterviewData_Cost.csv”	and	“InterviewData_Rev.csv”.
(1) Using	any	functions/packages	you	want,	join	these two	data	sets	by	“date”	and	“source_id”,	returning	
all	rows	from	both	regardless	of	whether	there	is	a	match	between	the	two	data	sets.
(2) Using	any	functions/packages	you	want,	join	these two	data	sets	by	“date”	and	“source_id”,	returning	
only	the	rows	from	the	“Cost”	file	that	have	no	corresponding	date	in	the	“Revenue”	file.
(3) Using	your	result	from	#1,	what	are	the	Top	4	sources	(“source_id”	values)	in	terms	of	total	revenue	
generation	across	this	data	set?	How	would	you	visualize	the	monthly	revenue	for	those	Top	4	sources?	
(note:	you	don’t	need	to	actually	create	a	plot; you	can	just	describe	what	your	ideal	visual	would	look	
like)
