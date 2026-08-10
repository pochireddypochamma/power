# Power Calculator in Java

A simple Java program to calculate the power of a number using the `Math.pow()` method.

## 📌 Description

The program takes two numbers from the user:

* **Base**
* **Exponent**

It then calculates the result using the formula:

```text id="z5n2ka"
Base^Exponent
```

### Example

```text id="q3x8pv"
2^5 = 32
```

## 💻 Technologies Used

* Java
* Scanner
* `Math.pow()`
* Variables

## 🚀 How to Run

### 1. Compile the program

```bash id="d6x4mz"
javac Power.java
```

### 2. Run the program

```bash id="w8c1qa"
java Power
```

## 📝 Example Output

```text id="k2v9rs"
Enter the base: 2
Enter the exponent: 5
2.0 raised to the power 5.0 is: 32.0
```

Another example:

```text id="p4h7nx"
Enter the base: 3
Enter the exponent: 4
3.0 raised to the power 4.0 is: 81.0
```

## 🔍 How It Works

The program uses Java's built-in `Math.pow()` method:

```java
double result = Math.pow(base, exponent);
```

For example:

```text id="r8m3fz"
Math.pow(2, 5) = 32
```

## 📂 Project Structure

```text id="n6w2qp"
power-java/
│
├── Power.java
├── .gitignore
└── README.md
```

## 📜 License

This project is created for learning and educational purposes.
