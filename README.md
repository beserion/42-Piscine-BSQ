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
- minor update @ 2026-01-19 11:22:22.137407
- minor update @ 2026-01-19 11:22:44.638939
- minor update @ 2026-01-20 01:50:49.490017
- minor update @ 2026-01-20 01:50:56.053665
- minor update @ 2026-01-20 10:29:45.124272
- minor update @ 2026-01-21 01:53:53.222136
- minor update @ 2026-01-21 01:54:19.466501
- minor update @ 2026-01-21 01:54:32.674947
- minor update @ 2026-01-21 01:54:46.188689
- minor update @ 2026-01-21 01:54:53.453966
- minor update @ 2026-01-21 05:30:01.239446
- minor update @ 2026-01-21 05:30:24.360220
- minor update @ 2026-01-21 05:30:55.759883
- minor update @ 2026-01-21 13:47:46.520382
- minor update @ 2026-01-21 13:48:00.624491
- minor update @ 2026-01-22 07:28:49.664024
- minor update @ 2026-01-22 07:28:59.978058
- minor update @ 2026-01-22 07:29:03.260599
- minor update @ 2026-01-22 07:29:06.561054
- minor update @ 2026-01-22 23:22:39.193635
- minor update @ 2026-01-22 23:22:55.233043
- minor update @ 2026-01-22 23:23:01.560326
- minor update @ 2026-01-23 15:27:19.558590
- minor update @ 2026-01-23 15:27:37.084601
- minor update @ 2026-01-23 15:27:43.380635
- minor update @ 2026-01-24 01:47:29.837323
- minor update @ 2026-01-24 01:47:39.764984
- minor update @ 2026-01-24 01:47:42.041524
- minor update @ 2026-01-24 18:31:43.188510
- minor update @ 2026-01-24 18:31:47.427137
- minor update @ 2026-01-24 18:32:10.481346
- minor update @ 2026-01-24 18:32:55.018196
- minor update @ 2026-01-24 20:23:25.078320
- minor update @ 2026-01-24 20:23:27.740679
- minor update @ 2026-01-24 20:23:34.288873
- minor update @ 2026-01-26 07:29:06.087302
- minor update @ 2026-01-26 07:29:14.341248
- minor update @ 2026-01-26 07:29:31.863421
- minor update @ 2026-01-26 17:30:59.611600
- minor update @ 2026-01-26 17:31:17.146690
- minor update @ 2026-01-26 22:24:06.709089
- minor update @ 2026-01-26 22:24:12.976836
- minor update @ 2026-01-26 22:24:30.034357
- minor update @ 2026-01-27 19:27:29.892391
- minor update @ 2026-01-27 19:27:40.491187
- minor update @ 2026-01-27 19:27:47.774192
- minor update @ 2026-01-27 19:27:57.056881
- minor update @ 2026-01-27 20:24:57.517958
- minor update @ 2026-01-27 20:25:28.828203
- minor update @ 2026-01-27 22:24:43.141384
- minor update @ 2026-01-27 22:25:00.003273
- minor update @ 2026-01-28 07:27:37.939428
- minor update @ 2026-01-28 07:27:57.050013
- minor update @ 2026-01-28 07:28:23.389440
- minor update @ 2026-01-28 12:53:49.593265
- minor update @ 2026-01-28 12:53:55.849610
- minor update @ 2026-01-28 12:54:04.113708
- minor update @ 2026-01-28 12:54:08.371642
- minor update @ 2026-01-29 02:07:07.134477
- minor update @ 2026-01-29 02:07:17.629745
- minor update @ 2026-01-29 02:07:25.894102
- minor update @ 2026-01-29 02:07:43.400887
- minor update @ 2026-01-29 02:07:57.112303
- minor update @ 2026-01-29 02:08:02.351708
- minor update @ 2026-01-29 02:08:06.603826
- minor update @ 2026-01-29 06:50:59.449800
- minor update @ 2026-01-29 06:51:06.096277
- minor update @ 2026-01-29 06:51:13.354602
- minor update @ 2026-01-29 08:41:24.087449
- minor update @ 2026-01-29 08:41:35.439044
- minor update @ 2026-01-29 08:41:55.796700
- minor update @ 2026-01-29 11:32:23.214160
- minor update @ 2026-01-29 11:32:26.849400
- minor update @ 2026-01-30 19:33:11.948711
- minor update @ 2026-01-30 19:33:20.246141
- minor update @ 2026-01-31 19:21:20.297966
- minor update @ 2026-01-31 19:21:28.602561
- minor update @ 2026-01-31 22:24:39.286195
- minor update @ 2026-01-31 22:24:53.904463
- minor update @ 2026-02-02 14:41:27.452431
- minor update @ 2026-02-02 14:41:33.932593
- minor update @ 2026-02-02 14:41:36.402802
- minor update @ 2026-02-03 09:42:52.301733
- minor update @ 2026-02-03 09:43:03.052266
- minor update @ 2026-02-03 14:44:06.421957
- minor update @ 2026-02-04 05:54:01.935872
- minor update @ 2026-02-05 02:09:52.920291
- minor update @ 2026-02-05 09:47:31.230154
- minor update @ 2026-02-05 09:47:39.773771
- minor update @ 2026-02-06 05:54:10.676097
- minor update @ 2026-02-06 05:54:14.197514
- minor update @ 2026-02-06 22:26:08.815030
- minor update @ 2026-02-07 11:23:28.864097
- minor update @ 2026-02-07 11:23:34.357071
- minor update @ 2026-02-07 11:23:41.903782
- minor update @ 2026-02-07 15:26:35.603684
- minor update @ 2026-02-07 15:26:54.134525
- minor update @ 2026-02-07 17:27:06.865233
- minor update @ 2026-02-07 17:27:17.151026
- minor update @ 2026-02-07 19:25:25.738552
- minor update @ 2026-02-07 19:25:34.306604
- minor update @ 2026-02-08 08:35:32.289341
- minor update @ 2026-02-08 08:35:40.824280
- minor update @ 2026-02-08 08:35:43.465240
- minor update @ 2026-02-08 17:27:44.057917
- minor update @ 2026-02-09 20:40:15.740987
- minor update @ 2026-02-09 20:40:23.335438
- minor update @ 2026-02-11 09:55:02.507550
- minor update @ 2026-02-11 09:55:09.097934
- minor update @ 2026-02-11 09:55:28.273729
- minor update @ 2026-02-11 21:35:02.208389
- minor update @ 2026-02-11 21:35:12.487808
- minor update @ 2026-02-11 21:35:20.186815
- minor update @ 2026-02-12 11:40:49.045149
- minor update @ 2026-02-12 17:00:36.050702
- minor update @ 2026-02-13 07:49:55.100644
- minor update @ 2026-02-13 07:50:08.579123
- minor update @ 2026-02-13 13:02:51.838498
- minor update @ 2026-02-13 13:03:04.039902
- minor update @ 2026-02-13 16:50:19.333756
- minor update @ 2026-02-13 16:50:39.540994
- minor update @ 2026-02-13 19:42:15.632530
- minor update @ 2026-02-14 02:07:43.579401
- minor update @ 2026-02-14 02:07:53.114278
- minor update @ 2026-02-14 06:48:05.911153
- minor update @ 2026-02-14 06:48:12.197035
- minor update @ 2026-02-16 14:42:16.371749
- minor update @ 2026-02-16 14:42:29.220861
- minor update @ 2026-02-16 14:42:37.082497
- minor update @ 2026-02-16 17:38:31.375659
- minor update @ 2026-02-17 14:47:55.940241
- minor update @ 2026-02-17 20:40:07.185061
- minor update @ 2026-02-18 06:02:15.430237
- minor update @ 2026-02-19 17:51:07.717336
- minor update @ 2026-02-20 15:38:02.603365
- minor update @ 2026-02-20 15:38:16.827246
- minor update @ 2026-02-21 22:25:32.426844
- minor update @ 2026-02-22 06:50:45.245618
- minor update @ 2026-02-23 09:56:36.944552
- minor update @ 2026-02-23 09:57:13.307260
- minor update @ 2026-02-23 10:54:58.192192
- minor update @ 2026-02-23 11:40:59.599746
- minor update @ 2026-02-23 11:41:18.813979
- minor update @ 2026-02-23 16:58:27.699452
- minor update @ 2026-02-23 16:58:32.912676
- minor update @ 2026-02-25 20:37:22.906973
- minor update @ 2026-02-25 21:35:57.974299
- minor update @ 2026-02-26 21:33:25.199864
- minor update @ 2026-02-27 05:53:04.987872
- minor update @ 2026-02-27 10:39:25.798905
- minor update @ 2026-02-28 12:48:50.005324
- minor update @ 2026-02-28 23:23:15.034518
- minor update @ 2026-02-28 23:23:32.618577
- minor update @ 2026-03-01 14:25:24.457313
- minor update @ 2026-03-01 14:25:37.644727