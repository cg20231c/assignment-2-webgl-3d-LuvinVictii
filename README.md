[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/nyKu4E7_)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12839616&assignment_repo_type=AssignmentRepo)
# Assignment 2: 3D Graphics and Interaction with WebGL
> Muhammad Daffa Harits<br> 5025211005

  - [Objective](#objective)
  - [Approach & Steps](#approach--steps)
    - [Initialization & Basics](#1-initialization--basics)
    - [Plane Construction](#2-plane-construction)
    - [3D Letter Construction](#3-3d-letter-construction)
    - [... (other sections as necessary)](#other-sections-as-necessary)
  - [Challenges & Learnings](#challenges--learnings)
  - [References & Resources](#references--resources)
  - [Feedback & Future Work](#feedback--future-work)
  - [Screenshots, Screencast & GIFs](#screenshots-screencast--gifs)
  - [Contribution & Collaboration](#contribution--collaboration)

## Objective
Create an interactive 3D scene with WebGL that showcases a personalized letter standing on an XZ plane, combined with lighting techniques from a designated light source.

---

## Approach & Steps
Document the strategy and step-by-step approach you took to achieve the objectives of the assignment:

### 1. Initialization & Basics
- Saya membuat basic kodenya dari chatGPT. Saya mendapatkan full kode tetapi sangat banyak yang perlu diubah
- Untuk dasar-dasar di luar teknis penggambaran dan listener sudah hampir benar, tetapi tetap butuh koreksi
- Saya meminta bantuan teman saya yang sudah mengambil matkul grafkom semester lalu

### 2. Plane Construction
- Untuk plane saya tidak mengalami masalah yang berarti
- Hanya saja karena warna pilihan saya sangat gelap (obsidian black), saya berimprovisasi untuk menukar warna plane dengan huruf agar plane lebih kontras dengan background hitam

### 3. 3D Letter Construction
- Awalnya bentuk inilah yang diberikan chatGPT:<br>
![image](https://github.com/cg20231c/assignment-2-webgl-3d-LuvinVictii/assets/78089862/e5d2b98d-b68d-4ceb-bb8e-68b096743d88)<br>
- Lalu saya berniat membuat sendiri dengan memulai membuat gambar ukuran huruf agar mudah ketika membuat titik-titiknya:<br>
![image](https://github.com/cg20231c/assignment-2-webgl-3d-LuvinVictii/assets/78089862/e29ae048-82f5-456d-985f-4ef2f2cbc547)<br>
- Setelah itu saya tidak mengalami banyak masalah
- Kecuali soal warna, karena tadi sudah ditukar dengan plane, jadi warna huruf saya yang gelap. Kemudian saya coba membuatnya lebih terang agar kontras dengan background

### 4. Lightsource
- Saya ada sedikit kesulitan dalam mengadaptasi cahaya ke huruf karena cahaya tidak mau bergerak ketika huruf bergerak
- Contoh: Ketika huruf ke kanan, seharusnya ada efek cahaya bergerak ke kiri pada huruf. Tetapi itu tidak terjadi
- Sudah saya coba otak atik, hanya saja cubenya juga bergerak
- Saya tidak sempat mengoreksinya sebelum deadline

### 5. Camera movement dan listener
- Saya tidak mengalami banyak kesulitan
- Saya hanya mengoreksi beberapa kesalahan chatGPT

### 6. Bonus: Physics
- Saya menambahkan sedikit keunikan dimana ada efek gravitasi ketika huruf melompat, sehingga kecepatan lompatnya tidak konstan

---

## Challenges & Learnings
Dalam pengerjaan, saya banyak belajar, terutama dalam listener, pengorganisasian bagian dari huruf, dan mekanisme-mekanisme pergerakan (huruf, kamera, dan cube). Kesulitan saya adalah saat memulai dan saat pewarnaan. Kedua kesulitan itu sudah bisa saya atasi

---

## References & Resources
List all the external resources, references, tutorials, or documentation you've consulted during the assignment:
- [WebGL Fundamentals](https://webglfundamentals.org/)
- [StackOverflow Post on Matrix Transformations](https://stackoverflow.com/questions/example)
- [ChatGPT: Coloring and gravity](https://chat.openai.com/share/04f3d96d-c96c-413a-a9bf-a1b169863811)
- (Other chatGPT chats (including the main chatroom) are accidentally erased by me when I want to delete other chats)

---

## Feedback & Future Work
I think this assignment is a little bit hard, especially in initialization. For future assignments I hope the template is more complete. For example, there's already object declaration, empty listener, empty functions, etc. so we can focus on the mechanism
---

## Screenshots, Screencast & GIFs
Include some visual representation of your work. These can be static images, YouTube videos, or GIFs that demonstrate the functionality and features you implemented. 

### [Demo](https://drive.google.com/file/d/1DnoTDKVGXGKBIcCo2tRRdUWnRGUqQB41/view?usp=drivesdk)

---

## Contribution & Collaboration
Thank you Ogik for the initialization when I really got stuck from GPT. Also thank you Syukra for the discussion on this assignment. And lastly thank you Andika (not in our class. He's already took CG class last semester) for some advice and teachings
