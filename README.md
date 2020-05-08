# assignment-2

Accessing Elements from a Tuple

exam_list = [(1, 'Tia', 21), (2, 'Seema', 20), (3, 'Jill', 19), (4,'Jack', 18)]
print ("The original list is : " + str(exam_list)) 
res = [lis[1] for lis in exam_list]
print ("List with only names : " + str(res))

Deleting different dictionary elements

sixMonths = {1:31, 2:28, 3:31, 4:30, 5:31, 6:30}
print(sixMonths.pop(6)) 
print(sixMonths)

sixMonths = {1:31, 2:28, 3:31, 4:30, 5:31, 6:30}
sixMonths.clear()
print(sixMonths)

sixMonths = {1:31, 2:28, 3:31, 4:30, 5:31, 6:30}
del sixMonths[5]
print(sixMonths)

Assigning elememt to a list

my_list = [35,15,20,30]
print(my_list)
my_list.append(25)
print(my_list)

