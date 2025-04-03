1/15
print👉🏻3 ways to quiz
1️⃣name=input("What's your major?")
  print(f"{name} is good.")
2️⃣name=input("What's your major?")
  print(name+" is good.")
3️⃣name=input("What's your major?")
  print=(name,"is good.")
1/16
name=input("What's your name?")
#remove whitespace from the str
#将光标移动到末尾：command+右箭头
name=name.strip()
#从上到下不断给name更新、赋值的过程
#capitalize user's name，大写每一个首字母；
#只大写第一个就用name=name.capitalize()
name=name.title()
print(f"hello, {name}")
4/3
🤎end 改变行末尾
#官方文件里末尾是换行，现在改为不换行
name=input("What's your name?")
print("Hello, ", end="")
print(name)
