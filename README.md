# COOKIEHANHOAN2021
## Cryptography
### Bài 1 : XOR 
[encrypt.zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471519/encrypt.zip)

####***Cách giải***
Bước 1: Theo đề bài thì ta thấy đây là một bài dạng XOR, việc ta cần làm là dịch ngược đoạn mã 

> 6c464b4d514b744817491714487449174b57

Bước 2: Ở đây mình sẽ sử dụng tool XOR decode để có thể tìm ra flag qua trang 

> https://www.dcode.fr/xor-cipher 

**Flag{a^b=c=>b^c=a}**

### Bài 2 : MORSE
Suỵt! Tập trung và đeo tai nghe lên nào. Gà có nghe thấy nhịp beat không? Họ nói gì từ bên kia chiến tuyến Format: Flag{what_you_find}

>  [cipher .zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471540/cipher.zip)

####***Cách giải***
Bước 1: Theo đề bài thì ta biết đây là một file âm thanh liên quân đến mã Morse. Cho nên ta dùng trang web ở dưới để hiểu được thông điệp nó muốn nói là gì

> https://morsecode.world/international/decoder/audio-decoder-adaptive.html

Bước 2: Ta tìm được thông điệp của bài cần 

> ![image](https://user-images.githubusercontent.com/90112096/140239644-2acc9f0b-cd35-463f-bb65-c54941590024.png)

**Flag{M.O.R.S.E.C.O.D.E}**

### Bài 3 : JULIUS CAESER
Vô tình khi khai quật khảo cổ, Gà tìm được một thông điệp bí ẩn khoảng hơn 100 năm trước công nguyên. Nghe đồn đây là một bí thuật đã bị thay đổi công thức của một vị tướng Julius Caesar, sau này trở thành vị vua đầu tiên của đế chế La Mã hùng mạnh. Hãy giúp Gà giải mật thư này!

> [cipher (9).txt](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471565/cipher.9.txt)

####***Cách giải***
Bước 1: Như đề bài thì ta biết được đây là mã Caeser việc ta cần làm chỉ là decode nó qua trang 

> https://www.dcode.fr/caesar-cipher

Bước 2: Sau khi decode ta tìm được flag :3

> ![image](https://user-images.githubusercontent.com/90112096/140243394-c85ad1d8-1054-444c-9535-72a3197f6200.png)

**Flag{El_Clasico_Cipher}**

### Bài 4: Sixty Four
Gà để lại một thông điệp bí mật nhưng nó không làm khó được trí thông minh của Mèo Yang Hồ.

> [cipher (10).txt](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471706/cipher.10.txt)

####***Cách giải***
Bước 1: Đọc đề bài ta có thể hiểu được là Sixty Four là 64 hay nói rõ hơn thì đoạn mã đã được mã hóa dưới dạng base64. Ta chỉ cần decode nó qua trang web 

> https://kt.gy/tools.html#conv/

> Ta thu được *466C61677B5F5F5F426173653634784865785F5F5F7D*

Bước 2: Tuy nhiên đây chưa phải là Flag dựa vào quan sát ta thử decode sang dạng Hex thì ta đã tìm được thứ ta muốn 

> ![image](https://user-images.githubusercontent.com/90112096/140244509-1ea7151c-9ada-49c9-a6d1-b0664f38ce54.png)

**Flag{___Base64xHex___}**



