----------------------------------------Inside the parent repository, there are two folders ---------------> User-1 and User-2---------------------------------------------------------- 
clone those inside repositories as
" git clone https://github.com/Harpreet6263/user-1.git "  and 
" git clone https://github.com/Harpreet6263/user-2.git "

First start Xampp and create database by running following commands:
create database whatsapp;
CREATE TABLE chat (
    id INT AUTO_INCREMENT PRIMARY KEY,
    msg VARCHAR(500),
    time TEXT DEFAULT (CURRENT_TIME),
    sender VARCHAR(20)
);
 INSERT INTO chat (msg, sender) VALUES
('Hello', 'you');

Now we have two folders as User-1 and User-2.
We have to install node modules by using the command npm install. NOTE we need to run this command twice in each user once in frontend and backend as well, It is demonstrated below----

For user-1 :
cd user-1
cd backend 
npm install
cd ..
npm install
cd ..

For user-2:
cd user-2
cd backend
npm install
cd ..
npm install

