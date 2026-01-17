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
- minor update @ 2026-01-13 03:39:12.053075
- minor update @ 2026-01-13 05:26:47.455404
- minor update @ 2026-01-13 05:27:11.664789
- minor update @ 2026-01-13 05:27:15.943537
- minor update @ 2026-01-13 12:51:03.908114
- minor update @ 2026-01-13 12:51:08.202581
- minor update @ 2026-01-13 12:51:43.402194
- minor update @ 2026-01-13 22:23:23.107198
- minor update @ 2026-01-13 22:23:44.968161
- minor update @ 2026-01-13 22:23:59.492284
- minor update @ 2026-01-13 22:24:06.768313
- minor update @ 2026-01-14 12:50:36.568961
- minor update @ 2026-01-14 14:27:25.793527
- minor update @ 2026-01-14 14:27:59.032710
- minor update @ 2026-01-14 19:20:31.417926
- minor update @ 2026-01-14 19:20:37.006880
- minor update @ 2026-01-14 19:21:00.133053
- minor update @ 2026-01-14 19:21:09.419158
- minor update @ 2026-01-15 03:42:03.982356
- minor update @ 2026-01-15 03:42:11.700147
- minor update @ 2026-01-15 14:29:21.823496
- minor update @ 2026-01-15 14:29:27.145430
- minor update @ 2026-01-15 14:29:34.437010
- minor update @ 2026-01-15 14:30:07.154584
- minor update @ 2026-01-16 16:30:48.276996
- minor update @ 2026-01-16 16:30:52.939313
- minor update @ 2026-01-16 16:31:06.271196
- minor update @ 2026-01-16 16:31:13.565264
- minor update @ 2026-01-16 16:31:34.496625
- minor update @ 2026-01-16 16:31:37.809742
- minor update @ 2026-01-17 14:19:48.524238
- minor update @ 2026-01-17 14:19:57.864218