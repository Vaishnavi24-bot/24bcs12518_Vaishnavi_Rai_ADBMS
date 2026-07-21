Select * from Arts
union
Select * from Science;

Select emp_name 
from employee
Union All
Select emp_name from pt_employee;

Select f_name from fruit
INTERSECT
Select inv_name from inventory;

Select f_name from fruit
except
Select inv_name from inventory;
