# katalon-finalapi-clarissafatimah

API merupakan perantara bagi beberapa aplikasi atau client dan server, baik pada satu platform yang sama maupun lintas platform yang berguna agar bisa saling berkomunikasi.

Link drive DEMO Task API (Report dan Video) : https://drive.google.com/drive/folders/13bhFVBwsGurcvM4fVB47oO6WBV8jAuvv?usp=sharing

Repository ini berdasarkan pada baseURL API Test Automation : https://restful-booker.herokuapp.com/

Pada Repository ini dijelaskan beberapa method, yakni :
GET digunakan untuk meminta data dari sumber daya tertentu.
POST digunakan untuk mengirim data ke server , dan server membuat / memperbarui sumber daya.
PUT digunakan untuk mengirim data ke server untuk membuat / memperbarui sumber daya.
DELETE digunakan untuk menghapus sumber daya yang ditentukan.
PATCH digunakan untuk memperbarui nilai properti sumber daya.

Pada repository ini saya membuat endpoint GET, POST, PUT yang dibuat ke dalam 5 test case, yaitu :
1. GET Booking
2. GET Booking ID
3. POST auth
4. PUT Booking

Repository ini juga terdapat 2 test suite, yaitu :
1. Test Suite GET : GET Booking & GET Booking ID
2. Test Suite PUT : PUT Booking yang chain dengan POST Auth dan CREATE Booking