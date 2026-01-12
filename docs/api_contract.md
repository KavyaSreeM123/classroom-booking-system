| Feature     | API                      | Method | Input                       | Output       |
| ----------- | ------------------------ | ------ | --------------------------- | ------------ |
| Register    | /auth/register.php       | POST   | name, email, password, role | status       |
| Login       | /auth/login.php          | POST   | email, password             | status, user |
| Get Rooms   | /rooms/get_rooms.php     | GET    | -                           | room list    |
| Book Room   | /booking/book_room.php   | POST   | room_id, date, time         | success      |
| My Bookings | /booking/my_bookings.php | POST   | user_id                     | bookings     |
