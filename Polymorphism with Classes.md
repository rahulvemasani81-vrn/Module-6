# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
~~~
class Beans:
      def type(self):
          print("Vegetable")
      
      def color(self):
          print("Green")
  
  
  class Mango:
      def type(self):
          print("Fruit")
      
      def color(self):
          print("Yellow")
  
  def func(obj):
      obj.type()
      obj.color()
  beans_obj = Beans()
  mango_obj = Mango()
  print("Beans object:")
  func(beans_obj)
  
  print("\nMango object:")
  func(mango_obj)
~~~

## Output
<img width="522" height="297" alt="504030727-fc2bc161-201c-4317-9d84-bbe5f174355d" src="https://github.com/user-attachments/assets/c22688b8-4504-4059-b599-fe3eed370542" />

## Result
To create two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism. is executed successfully
