<div align="center">

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10172A,35:164E83,70:087EAD,100:38BDF8&height=200&section=header&text=SMART%20CLASSROOM%20DIGITAL%20TWIN%20SYSTEM&fontSize=31&fontColor=FFFFFF&fontAlignY=40&animation=fadeIn&desc=SMART%20CAMPUS%20%7C%20DIGITAL%20TWIN%20PROJECT&descAlignY=62&descSize=14"/>

</div>

<img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=700&size=20&duration=3000&pause=1000&color=5BC0BE&center=true&vCenter=true&width=640&height=45&lines=Mission+Control+%E2%80%A2+Online;Five+Minds%2C+One+Mission;Learn+%C2%B7+Create+%C2%B7+Collaborate" alt="Mission Control">

</div>


<div align="center">

### 🌌 *“FIVE MINDS, ONE MISSION.”*

</div>

---


# 📜 PROJECT CHARTER

*Dokumen kesepakatan awal project.*

</div>



## <img src="https://img.icons8.com/fluency/32/info.png" width="28"/> 1️⃣ GAMBARAN UMUM

</div>

| ITEM | DETAIL |
|---|---|
| Judul Project | Smart Classroom Digital Twin System |
| Sponsor | Cut Alna Fadhilla, S.Kom., M.Sc. (Dosen Rekayasa Perangkat Lunak) |
| Tim | Kelompok 3 (5 anggota) |
| Project Manager | Ditentukan oleh tim |
| Pendekatan | Agile Scrum, 4 sprint |



## <img src="https://img.icons8.com/fluency/32/idea.png" width="28"/> 2️⃣ JUSTIFIKASI

</div>

Data ruang kelas, kapasitas, dan jadwal di banyak kampus tersimpan terpisah, misalnya di spreadsheet. Akibatnya jadwal bisa bentrok, kapasitas ruang tidak sesuai jumlah mahasiswa, dan pemakaian ruang sulit dipantau. Digital Twin berbasis perangkat lunak memberi gambaran terpadu, visual, dan dapat dianalisis tanpa biaya infrastruktur IoT.



## <img src="https://img.icons8.com/fluency/32/goal.png" width="28"/> 3️⃣ TUJUAN PROJECT

</div>

| NO | TUJUAN | UKURAN KEBERHASILAN |
|:-:|---|---|
| 1 | Memusatkan data ruang kelas | Profil ruang, kapasitas, dan fasilitas dapat dikelola dalam satu sistem |
| 2 | Mencegah jadwal bentrok | Jadwal yang tumpang tindih pada ruang yang sama ditolak oleh validasi |
| 3 | Menyediakan pemantauan simulasi | Okupansi dan status fasilitas tampil di Digital Twin Overview |
| 4 | Mendukung keputusan lewat analitik | Dashboard pemakaian dan jam sibuk tersedia |
| 5 | Menerapkan praktik rekayasa perangkat lunak | Dokumen analisis dan desain Sprint 1 selesai |


## <img src="https://img.icons8.com/fluency/32/compass.png" width="28"/> 4️⃣ RUANG LINGKUP

</div>

| ✅ DALAM LINGKUP | ❌ DI LUAR LINGKUP |
|---|---|
| Aplikasi web untuk ruang kelas, jadwal, dan Digital Twin | Integrasi sensor IoT fisik |
| Akses berbasis peran: Admin, Dosen, Pengelola Fasilitas | CCTV, kamera, mikrokontroler, perangkat tertanam |
| Simulasi okupansi dan status fasilitas virtual | Pengukuran kondisi ruang secara fisik |
| Overview interaktif dan analitik pemakaian | Aplikasi mobile native |



## <img src="https://img.icons8.com/fluency/32/timeline.png" width="28"/> 5️⃣ DELIVERABLE PER SPRINT

</div>

| SPRINT | FOKUS | HASIL | STATUS |
|---|---|---|---|
| **Sprint 1** | Analisis & Desain | User Story, Activity Diagram, Flowchart, API Spec, Function Point, Wireframe, Deployment | 🔄 Berjalan |
| **Sprint 2** | Backend & Autentikasi | Skema database, JWT, RBAC, REST API ruang & jadwal | 🔒 Direncanakan |
| **Sprint 3** | Digital Twin & Simulasi | Overview interaktif, API & UI simulasi, integrasi frontend | 🔒 Direncanakan |
| **Sprint 4** | Analitik & Deployment | Dashboard analitik, pengujian end-to-end, Docker, CI/CD | 🔒 Direncanakan |



## <img src="https://img.icons8.com/fluency/32/conference.png" width="28"/> 6️⃣ STAKEHOLDER

</div>

| STAKEHOLDER | KEPENTINGAN |
|---|---|
| Dosen pengampu | Menilai proses, dokumentasi, dan hasil akhir |
| Tim pengembang (Kelompok 3) | Merancang, membangun, menguji, dan mendokumentasikan sistem |
| Administrator | Mengoperasikan dan mengonfigurasi sistem |
| Dosen (pengguna) | Memakai informasi jadwal dan ruang |
| Pengelola Fasilitas Kampus | Memakai pemantauan dan analitik untuk perencanaan |


## <img src="https://img.icons8.com/fluency/32/toolbox.png" width="28"/> 7️⃣ SUMBER DAYA

</div>

| SUMBER DAYA | DETAIL |
|---|---|
| Sumber daya manusia | 5 anggota tim |
| Alat | GitHub, Docker, GitHub Actions |
| Anggaran | Tidak ada anggaran dana, memakai perangkat gratis dan open source |



## <img src="https://img.icons8.com/fluency/32/error.png" width="28"/> 8️⃣ RISIKO DAN MITIGASI

</div>

| RISIKO | DAMPAK | MITIGASI |
|---|---|---|
| Lingkup membesar melebihi waktu | Fitur tidak selesai | Prioritaskan fitur inti per sprint, hardware tetap di luar lingkup |
| Kontribusi anggota tidak merata | Keterlambatan dan kualitas turun | Bagi tugas tiap sprint, wajibkan commit semua anggota |
| Belum menguasai teknologi | Pengembangan lambat | Belajar bersama, kerja berpasangan pada bagian sulit |
| Integrasi frontend dan backend bermasalah | Pengerjaan ulang | Sepakati spesifikasi API sejak Sprint 1 |
| Data simulasi terasa tidak realistis | Nilai Digital Twin lemah | Buat pola okupansi berdasarkan jadwal dan kapasitas |



## <img src="https://img.icons8.com/fluency/32/checklist.png" width="28"/> 9️⃣ ASUMSI DAN BATASAN

</div>

**<img src="https://img.icons8.com/fluency/20/checked-checkbox.png" width="18"/> Asumsi**

- Semua anggota memiliki akses GitHub dan alat pengembangan.
- Data ruang dan jadwal adalah data contoh atau simulasi.
- Dosen pengampu tersedia untuk reviu di akhir tiap sprint.

**<img src="https://img.icons8.com/fluency/20/lock.png" width="18"/> Batasan**

- Sistem tidak boleh bergantung pada perangkat keras atau IoT.
- Pengerjaan mengikuti jadwal sprint mata kuliah.
- Hanya memakai perangkat gratis dan open source.



## <img src="https://img.icons8.com/fluency/32/trophy.png" width="28"/> 🔟 KRITERIA KEBERHASILAN

</div>

- Dokumen Sprint 1 lengkap dan konsisten satu sama lain.
- Setiap anggota memiliki commit yang dapat diverifikasi di repository.
- Sistem akhir mendukung pengelolaan ruang, jadwal tanpa bentrok, simulasi okupansi, dan analitik pemakaian.
- Sistem dapat dijalankan lewat alur deployment berbasis container yang terdokumentasi.

---

<div align="center">

# ⚡ TEAM POWER-UPS

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=14&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=400&lines=Creativity+%E2%80%A2+Teamwork;Innovation+%E2%80%A2+Problem+Solving;Knowledge+%E2%80%A2+Growth"/>

</div>

| POWER-UP | DESCRIPTION |
|---|---|
| 💡 Creativity | Mengembangkan ide kreatif |
| 🤝 Teamwork | Kerja sama kelompok |
| 🚀 Innovation | Menciptakan inovasi |
| 🧠 Problem Solving | Menyelesaikan masalah |
| 📖 Knowledge | Belajar bersama |

---

<div align="center">

# 💻 LANGUAGES & TECHNOLOGIES

<img src="https://skillicons.dev/icons?i=html,css,js,python,github,vscode&theme=dark" />

<br/><br/>

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

<div align="center">

# 🏆 OUR MISSION

### DESIGN • DEVELOP • INNOVATE

Belajar bersama, bekerja sama, dan mengembangkan
kemampuan dalam bidang Rekayasa Perangkat Lunak.

<br/>

| MISSION | STATUS |
|---|---|
| Team Formation | ✅ COMPLETED |
| Project Planning | 🔄 IN PROGRESS |
| System Analysis | 🔄 IN PROGRESS |
| Development | 🔒 UPCOMING |

<br/>

### "FIVE MINDS, ONE MISSION."

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:10172A,35:164E83,70:087EAD,100:38BDF8&height=160&section=footer&text=LEVEL%20UP%20TOGETHER&fontSize=26&fontColor=FFFFFF&animation=fadeIn"/>

**INFORMATIKA TEAM © 2026**

</div>
