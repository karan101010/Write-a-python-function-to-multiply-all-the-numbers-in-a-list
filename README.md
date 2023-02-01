# Write-a-python-function-to-multiply-all-the-numbers-in-a-list
def multiply(mylist):
    num=1
    for n in mylist:
        num*= n
    return num
list=[9,10,11]
print(multiply(list))
