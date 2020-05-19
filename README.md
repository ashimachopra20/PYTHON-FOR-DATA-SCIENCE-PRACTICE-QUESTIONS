# PYTHON-FOR-DATA-SCIENCE-PRACTICE-QUESTIONS
THE FOLLOWING CONTAINS THE CODE TO SOME FREQUENTLY ASKED PROBLEMS 
QUESTION 1:
REMOVE THE $ AND , TO CLEAN THE MESSY SALARY IN THE LIST "salaries"
SOLUTION:
print("CLEANING THE MESSY SALARY")
salaries = ['$876,001', '$543,903', '$2453,896']
sal=[]

for x in salaries:
    x=x[1:8:1]
    x=(x.split(','))
    "".join(x)
    x="".join(x)
    x= int(x)
    print(x)
    sal.append(x)
print(sal)
