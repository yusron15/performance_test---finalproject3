
# Final Project 3

Performance Testing yang menjalankan pengujian API contact list dengan API Login dan Logout




## Authors

- [@yusronf](https://yusronfadillah.net/)


## Features
Login - `https://thinking-tester-contact-list.herokuapp.com/users/login`

Log Out - `https://thinking-tester-contact-list.herokuapp.com/users/logout`


## HTTP Header Manager

Dalam pengujiannya, testing dilakukan dengan memiliki HTTP Header Manager yaitu:

⚒️ `Authorization: Bearer {{token}}`

Digunakan dalam request API ini `Login` & `Logout` untuk mengotentikasi atau mengotorisasi request dengan menggunakan metode otentikasi Bearer Token. Di sini, "{{token}}" adalah tempat di mana kita menyertakan token akses yang valid.

