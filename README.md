# ๐ํ์ฅTest(ํ๊ฒฝ์ฅ์ธ Test)

## Our Service
the test for environmental proffessional for Likelion hackerton 9th A-heung Olympic

## ๐จโ๐จโ๐ฆโ๐ฆContributor

- Likelion 9th
- ๊นํ์(PM)
- ๋ฐ์์ง(Back-end)
- ์ ์ฐ์ง(Front-end)
- ์ต์คํ(Front-end)

## Branch structure

### Main branch

- Main branch : It is Manage only the state that can be distributed
- Develop branch : It is Used to merge branches for feature development

### Secondary branch
- Fix branch : Branch to fix the function ex)fix/profile

## Guide

```
$ git clone
$ git pull origin develop
$ python -m venv myvenv
$ source myvenv/scripts/activate  mac) source myvenv/bin/activate
$ cd 
$ pip install -r requirements.txt
ํ์ํ ๋ชจ๋๋ค์ ์ ์ด๋์ผ๋ฉด, ์์์ ์ค์นํด์ค.
manage.py makemigrations
$ ./manage.py migrate
$ ./manage.py runserver

```

## Commit rule

```
git commit -m "text"
```

## Merge Rule

- merge๋ ํ์คํ๊ฒ ๋ pull request๋ง ํ  ๊ฒ
- ์๋ฌ๋ convention์ด ์ ์ง์ผ์ง์ง ์์์ ๊ฒฝ์ฐ ์ฝ๋๋ฆฌ๋ทฐ๋ฅผ ํ๊ฑฐ๋ ๋ณด๊ณ  ์์ ์ ํ  ๊ฒ
