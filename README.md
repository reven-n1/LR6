# LR6
Лабораторная работа №6

## Progress of work

### 1. астройка клиента
fff

### 2. Клонирование удаленного репозитория
fff

### 3.

### 4.

### 5.

### 6.

### 7.

### 8.

### 9.

## Command logs

git config -l

  687  git clone git@github.com:reven-n1/LR6.git
  688  cd LR6/
  689  git pull

  692  git log
  693  git log --pretty=format:"%h - %an, %ar : %s"

  695  git checkout master
  696  git merge origin/branch1

  699  nano mergefile.txt 
  700  git add mergefile.txt 

  702  git commit -am "soleved merge conflict"
  703  git branch -d branch1

  706  nano wtf.py 
  707  git add .

  709  git commit -am "1st change"
  710  nano wtf.py 
  711  git commit -am "2nd change"
  712  git reset --hard HEAD~2
  713  git checkout -b "report"

  716  mkdir data

