# Python-lessons-N-2
#erkrord dasy tnayin sax xndirnery hamarakalaca
"Das-2"
       "N-1"

            num = int(input("input five digit num: "))
            while num != 0:
                a = num % 10
                result = a
                num = num // 10
                print(result)
        "N-2"
            name = str(input("input name: "))
            a = len(name)
            print(a)

        "N-3"
            P = int(input("Enter a number: "))
            a = False
            if P > 1:
                for i in range(2, P):
                    if (P % i) == 0:
                        a = True
                        break
            if a:
                print("The number is not Prime")
            else:
                print("The number is Prime")

        "N-4"
            num = 0
            zero = 0
            while num < 5:
                num += 1
                print(str(num)+", "+str(zero))

        "N-5"
            a = int(input("input num a: "))
            b = int(input("input num b: "))
            c = int(input("input num c: "))

            if a+b == c or a+c == b or c+b == a:
                print("Yes")
            else:
                print("No")

        "N-6"
            num = 0
            for i in range(0, 15):
                num += i
            print("The sum of nums are: " + str(num))
