## Laporan Praktikum

|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2141720166|
| Nama |  Raihan Dany Radhinnur |
| Kelas | TI - 3I |

### Practicum 1 <br />

## Soal 1
"Capture hasil deploy project Anda dan buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari Jangan lupa push dengan pesan commit: "W09: Jawaban soal 1". "

![Screenshot](assets-report/09-jawaban-soal-1.png)

    We can use or implement Vercel to create web-based applications. It can be easily connected with NextJS framework in React programming language and other frameworks, producing with fast speed and high reliability in its infrastructure. By being able to connect with Repositories on GitHub that are owned, with only 1 time configuration easily and instantly without the need to configure each push repository.

<br />

## Soal 2
"Capture hasil basis data Anda dan buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari Jangan lupa push dengan pesan commit: "W09: Jawaban soal 2". "

![Screenshot](assets-report/09-jawaban-soal-2.png)

    We can create a database online in Vercel, in this practicum experiment we use Postgress which is a serverless SQL. In this practicum we need to connect/create .env in our root framework project, which has a private configuration code that can be seen in Vercel after completing Create Postgress Database in the store tabs section. We also need to verify that the .gitignore list includes .env so that it is not exposed when pushing the repository to our Github.

<br />

## Soal 3
"Capture hasil npm run seed Anda dan buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari ?
Jangan lupa push dengan pesan commit: "W09: Jawaban soal 3". "

![Screenshot](assets-report/09-jawaban-soal-3-1.png)<br />
![Screenshot](assets-report/09-jawaban-soal-3-2.png)

    We can do the npm run seed command to seed our data to the database, we need to configure in package.json by adding the code "seed": "node -r dotenv/config ./src/seeder/seed.js" in the bait scripts.
    Need to do the command npm i --save dotenv and npm i --save bcrypt first to overcome / prevent dotenv module errors and bcrypt module errors.
    After that, change the code in seed.js by changing the code to require( ./data.js ) if there is a Cannot find module 'data.js' error.

<br />

## Soal 4
"Capture hasil query Anda dan buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari ? Cobalah eksekusi query SQL yang lain sesuai kreasi Anda, capture hasilnya dan jelaskan!
Jangan lupa push dengan pesan commit: "W09: Jawaban soal 4"."

![Screenshot](assets-report/09-jawaban-soal-4-1.png)
    In this practicum, I coded a SQL query according to the practicum directions that search for 'invoices.amount = 666'. In this code query, we are trying to find in the invoice table based on custermer.id which is the customer that has amaount = 666.
    <br />
![Screenshot](assets-report/09-jawaban-soal-4-2.png)
    In executing my own customized SQL query, I tried to find invoice.status = 'paid', which will bring up the data of the customer name and amount that have paid status based on the costumer.id field.

<br />

### Practicum 2 <br />

## Soal 5
"Lakukan push, kemudian perhatikan di akun dashboard Vercel project Anda. Capture dan lampirkan link aplikasi Anda yang telah berhasil di deploy, kemudian buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari ?
Jangan lupa push dengan pesan commit: "W09: Jawaban soal 5"."

![Screenshot](assets-report/09-jawaban-soal-5.png)<br />
    link : https://09-react-nextjs-database.vercel.app/
    In this practicum, Vercel automatically runs the latest version of the Web-Application that is linked to the GitHub repository that was done at the beginning of Vercel creation. Vercel checks the code and then applies it automatically. 
    The results of the Vercel dashboard that I got can be seen from this screen shot.

<br />

## Soal 6
"Lakukan capture dan push hasilnya, kemudian buatlah laporan di file README.md. Jelaskan apa yang telah Anda pelajari ?
Jangan lupa push dengan pesan commit: "W09: Jawaban soal 6"."

![Screenshot](assets-report/09-jawaban-soal-6.png)<br />
    

<br />
