# 42 Piscine – BSQ

The **BSQ (Biggest Square)** project is a classic 42 Piscine assignment where you must find the largest possible square on a map while avoiding obstacles.
Your program reads a map from a file or standard input, processes it, and outputs the same map with the biggest valid square marked.

---

## 📌 Project Description

* The program takes a map consisting of:

  * A header line describing the number of rows and the map symbols.
  * A grid made of:

    * **empty characters**
    * **obstacle characters**
* The goal is to **compute the largest square** consisting only of empty positions.
* The final output replaces the found square with the **fill character**.

---

## 🧠 Key Objectives

* Parsing and validating map files.
* Implementing dynamic programming or efficient scanning algorithms.
* Handling invalid or malformed maps gracefully.
* Working with standard input and file descriptors.
* Improving performance on large maps.

---

## 🛠️ Features

* Supports **multiple input files**.
* Works from **standard input** when no file is provided.
* Detects and handles:

  * Invalid header
  * Wrong line lengths
  * Invalid characters
  * Inconsistent rows
* Prints the solved map with the largest square filled.

---

## 🚀 Usage

### Compile

```
make
```

### Run with a file

```
./bsq map.txt
```

### Run with multiple maps

```
./bsq map1.txt map2.txt map3.txt
```

### Run from standard input

```
cat map.txt | ./bsq
```

---

## 📄 Map Format Example

**map.txt:**

```
9.ox
.........
....o....
.........
.........
..o......
.........
.........
.......o.
.........
```

---

## 🧩 Output Example

```
.........
....o....
.....xxxx
.....xxxx
..o..xxxx
.....xxxx
.....xxxx
.......o.
.........
```

---

## 📦 Project Structure

```
42-Piscine-BSQ/
├── src/
├── includes/
├── Makefile
├── README.md
└── maps/
```

---

## 📝 Notes

This project is part of the **42 Piscine**, focusing on algorithmic thinking and optimized data processing. The solution must be **efficient**, **clean**, and **robust**.

---

- minor update @ 2026-01-13 03:39:02.797316