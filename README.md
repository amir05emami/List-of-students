# List-of-students
l = []
while 1:
    choose = input('choose: 1.add 2.remove\n')
    if choose == '1':
        name = input('name: ')
        l.append(name)
        print("mission accomplished")
    else:
        choose == '2'
        name = input('name: ')
        l.remove(name)
        print("mission accomplished")


    for i, name in enumerate(l,1):
        print(str(i)+'.' , name)
