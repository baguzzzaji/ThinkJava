# ThinkJava Edisi Bahasa Indonesia
LaTeX source and code for Think Java, 6th edition.
Copyright (C) 2016 Allen Downey and Chris Mayfield.

Permission is granted to copy, distribute, and/or modify this work under the
terms of the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported
License, which is available at http://creativecommons.org/licenses/by-nc-sa/3.0/.

---

Edisi asli buku ini dalam bentuk kode sumber LaTeX tersedia di http://thinkjava.org dan https://github.com/AllenDowney/ThinkJava.

Semua ilustrasi digambar menggunakan aplikasi xfig (http://www.xfig.org/) dan dia
(https://wiki.gnome.org/Apps/Dia/). Aplikasi-aplikasi ini merupakan aplikasi yang *free and open-source*.

Mengkompilasi kode sumber LaTeX dapat menciptakan dokumen baru yang *device-independent* atas buku ini yang dapat diubah ke format lain maupun dicetak.

Untuk melakukan kompilasi berkas PDF dari sumber LaTeX jalankan perintah:

    pdflatex thinkjava
    makeindex thinkjava
    pdflatex thinkjava
    pdflatex thinkjava

Kode sumber ini termasuk sebuah Makefile yang akan mengotomasi proses kompilasi. 
Di Linux, anda perlu memasang paket texlive-latex-extra dan hevea.
