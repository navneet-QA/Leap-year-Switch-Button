# Leap Year & Month Days Finder in Java 📅

A well-structured Java program that calculates the exact number of days in a specific month using `switch-case` conditional handling and leap year identification logic. This project serves as an excellent reference for handling multi-branch routing, logic grouping, and date calculations in console applications.

## 🧐 How It Works

The program takes a year and a month number (1-12) as inputs:
1. **Leap Year Logic:** It determines if the year is leap using standard rules (divisible by 4, not by 100 unless also divisible by 400).
2. **Switch-Case Button Structure:** It passes the month into a `switch` block. Months with 31 days and 30 days are grouped together efficiently, while February dynamically returns `29` days for a leap year or `28` days for a common year.

## 🚀 Features

* **Dynamic February Days:** Automatically toggles between 28 and 29 days depending on the leap year calculation.
* **Fall-Through Case Optimization:** Uses grouped switch statements to handle months with identical day counts seamlessly.
* **Input Validation:** Prevents out-of-bounds errors for invalid month inputs (outside the 1-12 range).

## 🛠️ Built With

* **Java Development Kit (JDK):** Version 8 or higher

## 💻 Getting Started

### Prerequisites
Make sure you have the Java Development Kit (JDK) installed on your system. Verify by running:
```bash
java -version
```

### Installation & Execution
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Navigate into the project folder:
   ```bash
   cd YOUR_REPOSITORY_NAME
   ```
3. Compile the Java source file:
   ```bash
   javac MonthDays.java
   ```
4. Run the compiled application:
   ```bash
   java MonthDays
   ```

## 📊 Example Output

```text
Enter year: 2024
Enter month number (1-12): 2

Result: February 2024 has 29 days (Leap Year).
```
