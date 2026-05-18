# Git

- Langkah 1: Ambil semua update terbaru dari repo ASLI

```
git fetch upstream
```

- Langkah 2: Merge update itu ke branch local kamu

```git merge upstream/master

```

- Langkah 3: Push ke repo GitHub KAMU supaya ikut terupdate

```git push origin main

```

# workflow buat UV

-

```
uv init --python 3.11
uv add jupyter numpy pandas matplotlib scikit-learn seaborn
git add .
git commit -m "Add UV environment and dependencies"
git push origin master
```

# workflow harian

## Setiap mulai belajar:

git fetch upstream # cek ada update dari DataTalksClub?
git merge upstream/master # ambil update kalau ada
git push origin master # sync ke GitHub kamu

## Kerja di my_work seperti biasa

## Selesai belajar:

git add my_work/
git commit -m "week 1: selesai homework linear regression"
git push origin master

## finish modul 1

git add my_work/01_intro/
git commit -m "finish modul 1"
git push origin master
