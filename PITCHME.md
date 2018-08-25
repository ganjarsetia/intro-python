# Introduction to python

By: Ganjar Setia

---

### Apa itu python?

Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together.

[From https://www.python.org/doc/essays/blurb/](https://www.python.org/doc/essays/blurb/)

---

## Sejarah Python

- Dibuat oleh Guido van Rossum.
- Dirumuskan dan direncanakan pada tahun 1980, dan mulai di implementasi pada tahun 1989
- Nama nya diambil dari acara TV Monty @color[darkorange](Python)'s Flying Circus.
- Sejak awal sudah berlisensi @color[#de935f](open source).

---?color=#E49436

@snap[north-west]
@fa[google fa-4x]
@snapend

@snap[north]
@fa[facebook fa-4x]
@snapend

@snap[north-east]
@fa[reddit fa-4x]
@snapend

@snap[south-west]
@fa[instagram fa-4x]
@snapend

@snap[south]
@fa[spotify fa-4x]
@snapend

@snap[south-east]
@fa[dropbox fa-4x]
@snapend

@snap[midpoint]
Perusahan ternama yang menggunakan python ?
@snapend

---

### Mengapa menggunakan python

Hampir sudah terinstall di tiap OS
<br>
Mudah digunakan
<br>
Mudah dipelajari, karena syntax nya yang simple
<br>

Hampir bisa digunakan di berbagai bidang:
<br>
- Backend
- Data Science, Statistik, mathematics
- Sys Admin, like Linux installer (system scripting)
- etc

---

## Yang harus diketahui

@ul
- Python memiliki 2 versi. Keduanya masih sering digunakan dan di maintain dari dulu.
- Why ?
- Perbedaan ?? see next slide
@ulend

---?image=https://mk0learntocodew6bl5f.kinstacdn.com/wp-content/uploads/2014/06/python-2-vs-3-2018.png&size=auto 90%
@transition[concave]

---

## Lalu gunakan yang mana?

@ul
- The future. Python 3.
- Now much faster
- Much more library
- Much more community support
@ulend

---

### how to start
@ol
- Install first. Kebanyakan sudah di install di Linux & Mac. Not recommended running on windows. For windows download it first
- Create file `hello.py`
- Write: `print("Hello World")`
- Then run it: `python hello.py`
- Or run python, then do the syntax
@olend

---?gist=ganjarsetia/de3c0ba3f66c22aaa4e00fd0294c7711&lang=python&title=Sample Code
@[1](Initialization code)
@[11-12](Standard boilerplate untuk memanggil fungsi main)

---
### Choose right IDE!

@ul
- Sesuaikan dengan kebutuhan Anda.
- Anda seorang Data Scientist ? gunakan Spyder or Jupyter Notebook
- Jika bukan? gunakan VS Code dengan support debugging tools
@ulend

---

### Identation!

Identasi di python sangatlah penting. Bertujuan agar bisa mengidentifikasi blok kode.

biasanya menggunakan spasi 2 kali atau 4 kali.

![Identation](https://d33wubrfki0l68.cloudfront.net/6d38cb172315d30651c04f053ba5f834aa2f513a/3f439/img/python/sintaks/blok-program-python.png)

---?gist=ganjarsetia/96f1c4778611ef3d7564e009577a122f&lang=python&title=Comment Syntax

@[1](Single comment)
@[3-6](Multi Line comment)
@[8-9](Contoh lain single comment)

---?gist=ganjarsetia/3f54d808b17fb95d8a925424d9c32aa4&lang=python&title=Strings Syntax

@[1](Single line)
@[4-5](Multi Line strings)

---?gist=ganjarsetia/7b5fdba0fa86af69ee3822c107adff4d&lang=python&title=Number Syntax

---

## Null Syntax

untuk menyatakan isi variabel tidak ada

```python
alamat = None
```

---?gist=ganjarsetia/68b5ab2a401a6f4846fab227354dde91&lang=python&title=Conditional Syntax

---?gist=ganjarsetia/b8f8689edc1e28cc6ca56d9d7b383329&lang=python&title=For loop syntax

---?gist=ganjarsetia/54338f82bde23b23f0522068d7886daf&lang=python&title=While syntax

---

```python
def tambah(x, y):
    return x + y
```
@[1](Single line)
