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
- minor update @ 2026-01-17 14:20:15.964431
- minor update @ 2026-01-17 14:20:20.273824
- minor update @ 2026-01-17 14:20:25.596533
- minor update @ 2026-01-17 14:20:35.897278
- minor update @ 2026-01-17 14:20:45.193221
- minor update @ 2026-01-17 14:20:52.514442
- minor update @ 2026-01-18 01:57:37.029346
- minor update @ 2026-01-18 01:57:52.919108
- minor update @ 2026-01-18 04:42:43.562428
- minor update @ 2026-01-18 04:42:49.823042
- minor update @ 2026-01-18 04:43:13.614061
- minor update @ 2026-01-18 04:43:20.880863
- minor update @ 2026-01-18 04:43:23.144251
- minor update @ 2026-01-18 05:24:49.993177
- minor update @ 2026-01-18 05:24:55.302291
- minor update @ 2026-01-18 05:25:04.588356
- minor update @ 2026-01-18 05:25:13.885910
- minor update @ 2026-01-18 05:25:29.776932
- minor update @ 2026-01-18 05:25:36.072927
- minor update @ 2026-01-18 05:25:38.372770
- minor update @ 2026-01-18 10:22:53.410324
- minor update @ 2026-01-18 10:23:03.095685
- minor update @ 2026-01-18 10:23:06.743827
- minor update @ 2026-01-18 10:23:10.451252
- minor update @ 2026-01-18 10:23:18.005343
- minor update @ 2026-01-18 10:23:29.690331
- minor update @ 2026-01-18 10:23:46.897948
- minor update @ 2026-01-18 12:41:58.081031
- minor update @ 2026-01-18 12:42:01.594094
- minor update @ 2026-01-18 17:18:36.582966
- minor update @ 2026-01-18 17:18:47.116215
- minor update @ 2026-01-18 17:18:56.380572
- minor update @ 2026-01-18 19:16:40.720401
- minor update @ 2026-01-18 23:20:47.538282
- minor update @ 2026-01-18 23:20:57.098322
- minor update @ 2026-01-18 23:21:05.375828
- minor update @ 2026-01-18 23:21:15.662406
- minor update @ 2026-01-19 09:36:03.540505
- minor update @ 2026-01-19 09:36:18.905562
- minor update @ 2026-01-19 09:36:21.639453
- minor update @ 2026-01-19 09:36:24.216301
- minor update @ 2026-01-19 09:36:36.324752
- minor update @ 2026-01-19 09:36:43.841886