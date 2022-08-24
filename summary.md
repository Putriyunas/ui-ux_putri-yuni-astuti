RINGKASAN SECTION 3

INTRODUCTION & INSTALLATION 

- Versioning /version control (fx) → berfungsi untuk mengatur versi dari source code program 
  Contoh masalah: seperti pengerjaan dokumen skripsi yang birevisi berulang kali, penamaan dokumen akan selalu berbeda yg artinya akan ada banyak nama pada dokumen yg sudah dibuat. Nah kalau gaada version control itu kita bingung mana sih yang paling bener/baru? 
  Dengan versioning kita gaperlu namain dokumen dgn revisi, revisi fix, revisi fix last, dst
- TOOLS 
   -RCS dan SCM adalah cikalbakal dari VCS 
   -Version Control System 
	Single User (1972-1982)
	Centralized (1986-2005)
	Distributed ( Git, Mercurial, Bazaar (2005))
- GIT
  - Salah satu VCS yang digunakan utk mengembangkan software scr bersama-sama
  - REAL WORLD COLLABORATION
  - Terdistribusi bukan tersentralisasi, artinya setiap org punya  kodenya masing masing yg akan dimasukan ke remote server. Setiap org bisa ngedit dan kalau sentralnya ada problem setiap org punya backup utk perbaikan ke remote server tsb 
  - GIT dibuat oleh Linus Torvalds (2005) 
  - GIT REPOSITORY (Folder Project)
  - Akan berisikan 2 hal 
    1. Folders dan Files(project kita)  
    2. History  ( biasanya folder .id nya biasanya ke hidden)
  - Agar bisa terhubung ke server, kita harus COMMIT dulu. 
- Commit → the record of changes 
  - Setiap code yg diubah akan di wrap dan ada tracknya juga yg berisikan perubahan yg terjadi (oleh siapa diubah, apa perubahannnya) kemudian kita pgn commmit atau naruh dia ke server (Upload) ya itulah COMMIT. Github akan catat perubahannya 
- Github → git hosting service
  Kayak sosial medianya programmer
  Bisa berkontribusi terhadap suatu program.
- Gitignore → berfungsi untuk memfilter mana aja yg boleh dan tidak boleh masuk ke repo 
- Pull Request → digunakan utk berkontribusi ke repo perusahaan temen, atau yg kita tapi pake akun lain (misal pengen tau salahnya dimana)
- Workflow Collaboration → cara mengolah brench scr bagus (optimalisasi workflow di github dan gitlab)
  Tips: 
  - Biarkan grandmaster tidak terdistribusi
  - Hindari edit langsung di developer 
  - Jika masukan fitur yang udah ada, masukin ke arah development bukan main
  - Jika benar benar udah selesai dan testing, baru merged ke master
