https://chatgpt.com/s/w_6ad5a4f7976c8191aba667d21bb1fde9
# Binary Search in C

A simple C program that implements the **Binary Search algorithm** to find an element in a sorted array.

## 📌 About the Project

Binary Search is an efficient searching algorithm that repeatedly divides a sorted array into two halves until the target element is found or the search range becomes empty.

## 🚀 Features

- Searches for an element in a sorted array.
- Accepts array elements and the search key from the user.
- Displays the position of the element if found.
- Displays a message if the element is not found.
- Uses an iterative approach.

## 🛠️ Technologies Used

- **Language:** C
- **Compiler:** GCC (or another standard C compiler)
- **Editor:** Visual Studio Code (VS Code)

## 📂 Project Structure

```text
binary-search-c/
├── binary_search.c
└── README.md
```

## 💻 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/IzhaanTech123/binary-search-c.git
```

### 2. Open the project folder

```bash
cd binary-search-c
```

### 3. Compile the program

```bash
gcc binary_search.c -o binary_search
```

### 4. Run the program

**Windows:**

```bash
.\binary_search.exe
```

**Linux/macOS:**

```bash
./binary_search
```

## 🧪 Example Output

```text
Enter the number of elements: 5
Enter 5 elements in sorted order:
10 20 30 40 50
Enter the element to search: 30
Element found at position 3
```

## ⚙️ Algorithm

1. Initialize `low` to `0` and `high` to `n - 1`.
2. Calculate the middle index.
3. Compare the middle element with the search key.
4. If they match, display the position.
5. If the key is larger, search the right half.
6. If the key is smaller, search the left half.
7. Repeat until the element is found or the search range is empty.

**Important:** The input array must be sorted in ascending order.

## ⏱️ Time and Space Complexity

| Case | Complexity |
|---|---|
| Best case | O(1) |
| Average case | O(log n) |
| Worst case | O(log n) |
| Auxiliary space | O(1) |

## 🎯 Learning Objectives

- Understand the Binary Search algorithm.
- Practice arrays and loops in C.
- Learn algorithmic time complexity.
- Practice using Git and GitHub for version control.

## 📄 License

This project is open for learning and educational use.
