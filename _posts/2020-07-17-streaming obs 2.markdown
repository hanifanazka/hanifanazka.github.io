---
layout: post
title:  "Materi Streaming OBS - Part 2"
date:   2020-07-17 10:00:00 +0700
categories: Streaming-OBS
---


## Proyek "Browser"

> Diasumsikan OBS sudah terinstall di Laptop dan IP Webcam sudah terinstall di Android, Laptop dan Android berada di jaringan Wifi yang sama, dan Memliki akses internet.

**Langkah-langkah:**

1. Lakukan Inisiasi OBS. Catat bagian "canvas size".

2. Setting Android yg akan menjadi kamera.
   1. Buka IP Webcam, lalu klik Start Stream.
   2. Catat alamat HP dibawah. (Contoh: http://192.168.0.6:8080/)
3. Buat Sources **"Browser"**
4. Tulis alamat HP di kolom URL (Contoh: http://192.168.0.6:8080/) lalu tambahkan "video"  (Contoh: http://192.168.0.6:8080/video)
5. Setting Width dan Height Supaya sama dengan hasil inisiasi bagian "canvas size". Lalu klik OK.

Penampilan sekarang seperti ini:![image-20200716085308217](/assets/images/image-20200716085308217.png)

**Selamat!** Sudah Anda telah berhasil membuat alat streaming...😁



###### Faq (Frequently Asked Question)

**Kok gambarnya hitam?**

Pencet tombol "Refresh cache of current page" lalu pencet tombol OK setelah langkah nomor 5.

**Gambarnya kok masih hitam?**

Pastikan URL pada langkah 4 diawali dengan **http://** bukan **https://**

**Sudah. Tapi kok masih hitam?**

Pastikan HP dan Laptop berada di jaringan Wifi yang sama.



## Suara

> Diasumsikan anda telah menyelesaikan **Proyek "Browser"**. Persiapkan 1 headset.

Untuk membuat suara, anda dapat menggunakan input mic yg ada di laptop. **FYI:** Anda dapat menggunakan Mic yang ada di HP anda juga.

Langkah-langkah:

1. Lihat bagian Audio Mixer. Pastikan bagian Mic/Aux tidak di-mute.
2. Untuk memonitor Suara, Klik kanan dibagian Audio Mixer.
3. Pilih "Advanced Audio Properties".
4. Pilih "Monitor and Output" pada kolom "Audio Monitoring" Untuk Mic/Aux.
   Tampilan saat ini akan seperti ini.![image-20200716093400362](/assets/images/image-20200716093400362.png)

**Keren-kannn.** Jadi suaranya bisa di monitor sambil streaming😉.



###### Faq (Frequently Asked Question)

**Kok jadi *ngiing* gituh. Sakit tau kupingnya.**

Pake headset.

**Audio Monitoring itu apa?**

"Monitor off" itu berarti suara ke output saja. "Monitor only (mute output)" itu berarti suara hanya ke monitor. "Monitor and Output" itu berarti suara ke monitor dan output.



## 2 Kamera

> Diasumsikan anda telah menyelesaikan **Proyek "Browser"**. Persiapkan 1 HP tambahan.

Langkah-langkah:

1. Klik **+** di dalam panel Scanes. Namakan "Scene 2".
2. Klik **+** di dalam panel Sources. Tambahkan Browser seperti langkah-langkah di **Proyek "Browser"**
   Tampilan sekarang akan seperti ini![image-20200716095437697](/assets/images/image-20200716095437697.png)

**Berhasil toh?** Sekarang siap buat transisi dong😋



## Transisi

> Diasumsikan anda telah menyelesaikan **2 Kamera**.

Langkah-langkah:

1. Klik tombol "Studio Mode" dalam panel Controls.
   ![image-20200716103854748](/assets/images/image-20200716103854748.png)

**Mantapp!** 1 langkah jadi.😀



###### Faq (Frequently Asked Question)

**Apa itu kolom preview dan kolom program?**

Kolom program itu adalah tampilan yang sekarang sedang disisarkan. Sedangkan, kolom preview adalah kolom untuk pratinjau.

**Kalo pingin transisi caranya gimana?**

Pilih scane yang akan dituju. Klik tombol transition di tengah.



## Panel Streaming

>Diasumsikan anda telah menyelesaikan **Transisi**.

Nih bagian kerennya... Tampilannya tuh kayak yang live-live keren gitu....



Langkah-langkah:

1. Klik menu bar "View diatas". Pilih bagian "Multiview (Windowed)".

![image-20200717175028597](/assets/images/image-20200717175028597.png)

**Yup... Kerenkan..** 1 Langkah doang. Hehehe...😄



###### Faq (Frequently Asked Question)

**Itu buat apa?**

Coba pencet2.

**Yang mana sih?**

Yang ini...

<img src="/assets/images/image-20200717175632915.png" alt="image-20200717175632915" style="zoom: 80%; float: left;" />



## Berita

> Diasumsikan anda telah menyelesaikan **Proyek "Browser"**

Dalam bagian ini, anda bisa membuat panel bawah yang isinya info-info seperti acara berita lho. Untuk penjelasannya tidak dalam bentuk langkah-langkah. Karena jika dijelaskan satu per satu akan lama. Coba2 sendiri ya..

Pilihannya:![image-20200717195423737](/assets/images/image-20200717195423737.png) 



Nah, nanti hasilnya bisa seperti ini ya... 

![http://ksp.go.id/wp-content/uploads/2019/09/Screen-Shot-2019-09-26-at-07.07.57.png](/assets/images/Screen-Shot-2019-09-26-at-07.07.57.png)



Untuk belajar, disarankan pelajari dahulu:

1. Image.
2. Text.
3. Color Source.
4. Audio input&output capture.

***Pssstt...*** Ada yang keren, cobain yang source "scane" ![image-20200717195423738](/assets/images/image-20200717195423738.png)



###### Faq (Frequently Asked Question)

**Emangnya "scene" buat apa?**

Buat memasukkan scene didalam scene.

**Kok yang "scene" enggak bisa di pencet?**

Bikin "scene" baru di panel Scenes.



## Kebalik 🙃🙃

> Diasumsikan anda telah menyelesaikan **Proyek "Browser"**

![image-20200717201722272](/assets/images/image-20200717201722272.png)



Kebalik, gimana doong...?

Langkah-langkah:

1. <img src="/assets/images/image-20200717201946451.png" alt="image-20200717201946451" />

**Selesaii...** Setelah ini coba2 pilihan transform yang lainnya. Ok...👌



###### Faq (Frequently Asked Question)

**Itu pilihanya keluar dari mana?**

Klik kanan.



## Greenscreen

> Diasumsikan anda telah menyelesaikan **Kebalik 🙃🙃**

Wiii... Kerenn nih...

Langkah-langkah:

1. Klik "Filters". Akan terbuka halaman seperti berikut
   ![image-20200717203912369](/assets/images/image-20200717203912369.png)
2. Klik **+** di bagian "Effect Filters" lalu pilih "Chroma Key"
   ![image-20200717204141063](/assets/images/image-20200717204141063.png)

**Jadi deh..** Keren toh😁... Sok, coba2 yang lainnya...