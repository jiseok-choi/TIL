## ๐ 2022/05/14

<br/>

### ๐น ์ฃผ๊ฐ ๋ชฉํ

- [ ] ์ด๋ ฅ์ ์ง์
- [ ] stock ํ ์ด ํ๋ก์ ํธ ๋ฐ์ดํฐ ํ์ฑํ๊ธฐ
- [x] MySQL ์คํฐ๋ ์ด๋ฒ์ฃผ ๋ถ๋ ํ์ต
- [x] ์คํ๋ง ์๋ฆฌ ํ์ต ๋ฐ ์ ๋ฆฌ
- [x] queryDSL ํ์ต


<br/>

### ์ผ์ผ ์ฒดํฌ๋ฆฌ์คํธ(์ด์  ์ ํ ๋ชฉํ)

- [ ] ์คํ๋ง ํ์ต
- [x] MySQL ๊ฒฉ๋ฆฌ๋ ๋ฒจ ํ์คํธ

<br/>

### ๐ฏ ์ค๋ ํ ์ผ

- MySQL ๊ฒฉ๋ฆฌ๋ ๋ฒจ ํ์คํธ

<br/>

### ๐ ๋ด์ผ ํ  ์ผ

- ์คํ๋ง ํ์ต
- stock ํ ์ดํ๋ก์ ํธ
- MySQL ํ์คํธ

<br/>

### ๐ง ๊ฐ๋จ ํ๊ณ 

- Mysql ๊ฒฉ๋ฆฌ ๋ ๋ฒจ ํ์คํธ๋ฅผ ์งํํ๋ค.
  - ๊ฐ ๊ฒฉ๋ฆฌ๋ ๋ฒจ ๋ณ๋ก update ํ ๋ฐ์ดํฐ๋ฅผ ์ฝ์์๋ ๊ฒฐ๊ณผ๋ฅผ ํ์ธํ๋ ํ์คํธ๋ฅผ ์ํํ์ผ๋ฉฐ
  - Read Uncommitted ์ธ ์ ์ ๊ฐ ๋ ๋ฒจ๋ก ์กฐํ์ row lock ์ด ๊ฑธ๋ ค์๋ ๋ฐ์ดํฐ๋ฅผ ์ฝ์์๋ ๊ณผ๊ฑฐ ๋ฐ์ดํฐ๊ฐ ๋์ฌ๊ฒ์ธ๊ฐ๋ฅผ ์ถ๊ฐ์ ์ผ๋ก ํ์คํธํ๋ค.
  - ์ง๋ฌธ์ ๋ต์ ํ๊ธฐ ์ํด ๋ด์ผ row lock ์ ์ข๋ ์ฅ๊ธฐ์ ์ผ๋ก ํ  ์ ์๋ ๋ฐฉ๋ฒ์ด ์๋์ง, ์๋ค๋ฉด uncommitted ๋ ๋ฒจ์์ ์ฝ์์๋ undo log ์์ ๊ณผ์ฐ ์ ๋ ์์ฝ๋์ง๋ฅผ ์ข๋ ํ์ธํด๋ด์ผ ํ  ๊ฒ ๊ฐ๋ค.
  

