<h1>Laravel Tutorial by P'otis</h1>
  <h2>Basics Todo-List Application<h2>
  <p>what will you learn from this?
    <ol>
        <li>artisan command</li>
        <li>larvel mvc model</li>
        <li>how to store data in database by using laravel</li>
        <li>rich of php syntax</li>
        <li>Eloquent model of laravel</li>
    </ol>
  </p> 
  <p>
    How to use this repository?
    <ol>
      <li>copy .env.example แล้วเปลี่ยนชื่อเป็น .env หลังจากนั้นให้เปลี่ยน DB_DATABASE, DB_USERNAME, DB_PASSWORD  เป็น ของตัวเองตามที่ตั้งไว้ใน xampp</li>
      <li>หลังจากนั้นให้ไปที่หน้า cmd ไปที่ directory ของ project นี้ แล้วสั่ง php artisan migrate เพื่อสร้าง database</li>
      <li>โดยหากทำถูกต้อง จะมีตารางชื่อ users, password reset และ todos อยู่ใน database</li>
      <li>หากต้องการ reset ค่าใน database ใหม่ให้รันคำสั่ง php artisan migrate:rollback ใน cmd หลังจากนั้นให้สั่ง php artisan migrate อีกที</li>
    </ol>
  </p>