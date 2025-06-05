# 🔺 Right-Angle Triangle Pattern – Python Program

This is a simple Python program that prints a **right-angle triangle** made of asterisks (`*`). It demonstrates basic use of loops and pattern printing, perfect for beginners.

## 📌 Description

* The user is prompted to enter an integer `a`, which defines the **height of the triangle**.
* The program prints a triangle of `*` symbols where each row contains an increasing number of stars.

### 🧾 Sample Input & Output

**Input:**

```
Enter height: 5
```

**Output:**

```
*  
* *  
* * *  
* * * *  
* * * * *  
```

## 🧠 Logic

* Start with `counter = 1`
* Use a `while` loop to print rows from `1` to `a`
* In each iteration, print `counter` number of stars separated by spaces
* Increment the counter by 1 each time

## 🧾 Code

```python
a = int(input("Enter height: "))
counter = 1
while counter <= a:
    print("* " * counter)
    counter = counter + 1
```

## 🛠️ How to Run

1. Save the code in a file like `triangle_pattern.py`
2. Run the file using Python:

```bash
python triangle_pattern.py
```

3. Input the height value when prompted and see the triangle pattern printed.

## 🎯 Use Case

* Ideal for practicing:

  * `while` loops
  * Pattern-based logic
  * Basic input/output in Python

* Can be easily extended to:

  * Hollow triangles
  * Inverted triangles
  * Number or alphabet patterns

## 📬 Contact  

For any inquiries or feedback, feel free to reach out:    
🔗 **GitHub**: [Rachana-Hegde](https://github.com/Rachana-Hegde)  

