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

### Bài 4: SIXTY FOUR
Gà để lại một thông điệp bí mật nhưng nó không làm khó được trí thông minh của Mèo Yang Hồ.

> [cipher (10).txt](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471706/cipher.10.txt)

####***Cách giải***

Bước 1: Đọc đề bài ta có thể hiểu được là Sixty Four là 64 hay nói rõ hơn thì đoạn mã đã được mã hóa dưới dạng base64. Ta chỉ cần decode nó qua trang web 

> https://kt.gy/tools.html#conv/

> Ta thu được *466C61677B5F5F5F426173653634784865785F5F5F7D*

Bước 2: Tuy nhiên đây chưa phải là Flag dựa vào quan sát ta thử decode sang dạng Hex thì ta đã tìm được thứ ta muốn 

> ![image](https://user-images.githubusercontent.com/90112096/140244509-1ea7151c-9ada-49c9-a6d1-b0664f38ce54.png)

**Flag{___Base64xHex___}**

## Misc
### Bài 1 : DISCORD
Đã từng là những Rookie còn bỡ ngơ trong ngành bảo mật, chúng mình hiểu cảm giác ấy! Nên Cookie Hân Hoan muốn sử dụng những năng lượng vui tươi và truyền cảm hứng học và tìm hiểu bảo mật cho các bạn. Không dùng những tiêu đề cảnh báo an ninh nhạy cảm, gây sợ hãi. Cookie Hân Hoan giúp mọi người tiếp cận các vấn đề về An Ninh Mạng bằng sự đồng cảm và hài hước. Hãy tham gia kênh Discord chính thức của Cookie Hân Hoan để nhận #roles tham gia trao đổi các thử thách với các chiến binh khác. Flag sẽ ở chỗ mà ai cũng thấy!

> https://discord.gg/cookiehanhoan

####***Cách giải***

Bước 1: Thường thì đây là câu cho điểm các thí sinh nên việc ta cần làm chỉ là vào discord Cookie Hân Hoan. Vào phần ghim tin nhắn để kiểm tra xem có gì đáng lưu ý không.

Bước 2: Như dự đoán, ta tìm được flag :3 

> ![image](https://user-images.githubusercontent.com/90112096/140245063-6c5877e8-c84c-42ad-913f-c8fb666f628d.png)

***Flag{Cookie_Han_Hoan}***

## PROGRAMMING
### Bài 1 : SUM()
Bỏ qua tất cả các tích phân, đạo hàm, ma trận, sác xuất. Gà hãy kết nối tới máy chủ của Cookie Arena và thực hiện tính tổng của dãy số đã cho một cách nhanh nhất. Hãy học cách sử dụng Python và player.py để giải toán nha

> programming.letspentest.org 8111

> [player (2).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471782/player.2.zip)
 
####***Cách giải***

Bước 1: Ta thử kết nối với programming.letspentest.org 8111 bằng netcat. Ta thấy được việc ta cần làm là tính tổng 10 số tự nhiên.

> ![image](https://user-images.githubusercontent.com/90112096/140245690-baa42b47-5ab5-4442-ae19-4c1bfa957465.png)

Bước 2: Ta bắt tay vào code socket. Các bạn nên đọc code để dễ hiểu hơn : https://pastebin.com/Xufdw1Wx

> ![image](https://user-images.githubusercontent.com/90112096/140245862-e2482351-7bd7-463b-8064-39c45851d8f3.png)

**Flag{1plust1_1s_2_qu1ck_mafth}**

### Bài 2 : PRO102
Rồi một ngày kia mắt anh tròn xoe như đường tròn lượng giác Khi bất ngờ một bài toán bậc 2 Cứ lầm tưởng rằng nghiệm duy nhất với ai Thật kinh hoàng phương trình vô nghiệm(st)

> programming.letspentest.org 8222

> [player (3).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471805/player.3.zip)

####***Cách giải***

Bước 1: Ta thử kết nối với programming.letspentest.org 8222 bằng netcat. Ta thấy được việc ta cần làm là tìm nghiệm của phương trình bậc 2. Tuy nhiên một số điều cần lưu ý khi submit đã được đề cập trong file của bài như 

- NẾU KẾT QUẢ LÀ VÔ NGHIỆM -> RETURN "NOPE"
- NẾU KẾT QUẢ CÓ 1 NGHIỆM DUY NHẤT -> RETURN 1 STRING CÓ 2 KẾT QUẢ NGĂN CÁCH BẰNG DẤU "," (VD: "1, 1"    "123, 123")
- NẾU KẾT QUẢ CÓ 2 NGHIỆM KHÁC NHAU -> RETURN 1 STRING KẾT QUẢ THEO THỨ TỰ TỪ BÉ ĐẾN LỚN, NGĂN CÁCH NHAU BẰNG DẤU "," (VD: "-1, 1"   "-123, 123")

Bước 2: Ta bắt tay vào code socket. Các bạn nên đọc code để dễ hiểu hơn : https://pastebin.com/HCsUTkFC

> ![image](https://user-images.githubusercontent.com/90112096/140246372-6e7daa07-e0ae-498a-9806-4f64f9f5df82.png)

**Flag{2fast2fur10us}**

### Bài 3 : ROBERVAL
Hazy ngồi cân những viên bi mình đang có, loay hoay vẫn không biết phải cân bao nhiêu lần để tìm được viên bi nhẹ nhất. Bạn giúp Hazy một tay với nhé

> programming.letspentest.org 8333

> [player (4).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471821/player.4.zip)

####***Cách giải***

Bước 1: Ta thử kết nối với programming.letspentest.org 8333 bằng netcat. Ta thấy được bài toán như sau

> ![image](https://user-images.githubusercontent.com/90112096/140246630-c174829d-5a66-4251-acbf-bd478aa53d70.png)

Bước 2: Sau một hồi tìm kiếm công thức và suy nghĩ thì mình nghiệm ra cách giải bài này là: Cứ chia n cho 3 đến khi bằng 1. Để giải thích cho cách giải này mình có ví dụ như sau:

Lần 1 chia nó thành 3 nhóm mỗi nhóm 3 bi , cân 2
- 2 nhóm bằng nhau > bi nhẹ ở nhóm còn lại
- 2 nhóm có nhóm nhẹ hơn > bi nhẹ ở nhóm đó 
Lần 2 cân 3 bi trong nhóm nhẹ , cân 2 
- 2 bi bằng nhau > bi nhẹ là viên còn lại
- 2 bi không bằng nhau > xác định được viên bi nhẹ

> Thế là n=9 thì ta chỉ cần cân 2 lần

Bước 3: Tuy nhiên bài này mình sẽ không code socket vì mình tìm thấy rằng các câu hỏi xuất hiện ngẫu nhiên nhưng vẫn sẽ lặp lại giá trị n. Ví dụ mình biết là n=9 thì đáp án là 2, n=81 sẽ là 4, n=3 thì sẽ là 1. Việc mình cần chỉ là gặp câu số quá to thì ta nhập đại để nó quay lại câu hỏi cũ thôi :>>>>. Sau khi đúng được 5 câu ta nhận được flag.

> ![image](https://user-images.githubusercontent.com/90112096/140247501-390f04fc-2551-408b-a599-8932ea11c64f.png)

**Flag{n0_pr0b_w1th_cub3_r00t_RIGHT?}**

## Web Basic
### Bài 1 : HÂN HOAN
Thấy hộp bánh quy của chú Hazy để hớ hênh trên bàn. Với bản tính nghịch ngợm, Mèo Yang Hồ nhanh tay thêm chút gia vị để biến cuộc đời trở nên hài hước và hân hoan hơn.

> http://chal5.web.letspentest.org/

###***Cách giải***

Bước 1: Ta thử truy cập vào trang web và nhập bừa tài khoản mật khẩu thì ta nhận được thông báo.

> ![image](https://user-images.githubusercontent.com/90112096/140248244-17f69b97-f877-4f94-a5a4-12f7182e479d.png)

Bước 2: Ta đọc lại đề bài, ta thấy nó có đề cập tới bánh quy hay ta hiểu là cookie. Ta thử xem cookie hiện tại là gì

> ![image](https://user-images.githubusercontent.com/90112096/140248345-7733396b-2381-44be-9cca-cedcb1342fc3.png)

Bước 3: Ta thấy được giá trị đang là Guest mà trang web đang cần bạn là CookieHanHoan. Vậy ta chỉ cần thay đổi value sang CookieHanHoan rồi ta nhận được flag

> ![image](https://user-images.githubusercontent.com/90112096/140248449-e341cd92-96f8-42bc-be0b-b2b56966095d.png)

**Flag{Cookies_Yummy_Cookies_Yammy!}**

 ### Bài 2 : HEADER 401
Để nhiều loại Trình duyệt và Web Server có thể nói chuyện và hiểu được nhau thì họ phải sử dụng chung một giao thức có tên gọi là HTTP Protocol. Khi người dùng bắt đầu truy cập Web, trình duyệt sẽ chuyển những hành động của họ thành yêu cầu (Request) tới Web Server. Còn Web Server sẽ trả lời (Response) xem có thể đáp ứng hay từ chối cung cấp thông tin cho trình duyệt. Ví dụ, bạn Gà muốn LẤY danh sách các thử thách trong cookiearena<chấm>org, ở đường dẫn /challenges bằng TRÌNH DUYỆT Chrome. Trình duyệt của Gà sẽ phải điền vào một cái form mẫu có tên gọi là HTTP Header và gửi đi. Mỗi yêu cầu sẽ được viết trên một dòng, và nội dung của mỗi yêu cầu sẽ phải viết đằng sau dấu hai chấm. Hãy đoán xem trong thử thách này có những Header thú vị nào nha

> http://chal3.web.letspentest.org/

####***Cách giải***

Bước 1: Ta vào trang web thử ta nhận được một thông tin "Hello GET Request. Nice to meet you <3". Khi bật source lên thì ta tìm được

> Basic Authentication Credential: gaconlonton/cookiehanhoan

Bước 2: Ta sử dụng công cụ BurpSuite để kiểm tra. 

> ![image](https://user-images.githubusercontent.com/90112096/140248884-da11e921-6141-4c7e-8cb3-7b71744f213c.png)

Bước 3: Ta biết rằng ngoài phương thức GET thì ta còn POST để gửi đến server. Giải thích lý do ta muốn dùng phương thức POST là bởi ta tìm được Basic Authentication. Các bạn có thể đọc thêm về đó qua:

> https://swagger.io/docs/specification/authentication/basic-authentication/#:~:text=Basic%20authentication%20is%20a%20simple,%2Dencoded%20string%20username%3Apassword%20.

Bước 4: Ta chỉ cần thay đổi phương thức qua POST và chèn thêm *Authorization: Basic Z2Fjb25sb250b246Y29va2llaGFuaG9hbg==* để xem ta có thể nhận được gì

> ![image](https://user-images.githubusercontent.com/90112096/140249272-dbfb3ac2-ad62-48d5-9f17-3f48f69d2f5f.png)

**Flag{m4g1c@l_h34d3r_xD}**

### Bài 3 : JS BEEP BEEP 
Sau nhiều đêm suy nghĩ về việc làm thế nào để bảo vệ mã nguồn. Cố gắng thoát khỏi ánh mắt soi mói của Mèo Yang Hồ. Gà chẹp miệng rồi nói: "Đã tới lúc phải cho nó phải thốt lên rằng! WTF!!!"

> http://chal4.web.letspentest.org/

####***Cách giải***

Bước 1: Ta truy cập vào trang web mở source code ra ta tìm được hàm kiểm tra user/pass/role để có được flag

> ![image](https://user-images.githubusercontent.com/90112096/140249414-bed9b671-5d37-4a63-bda3-6b55d6907663.png)

Bước 2: Tuy nhiên nó không được thấy một cách dễ dàng nên ta vào console nhập hàm đó xem nó là gì:

> ![image](https://user-images.githubusercontent.com/90112096/140249484-02ef49e9-2db2-48e6-a145-e0fbb1c723a6.png)

Bước 3: Ta phân tích các hàm ta có được 
- Đầu tiên là Username : cookiehanhoan 
- Thứ 2 là password : sup3rSercur3p@ssW0rd ( hàm đó chỉ cần đảo chuỗi là ra password )
- Thứ 3 là role : https://pastebin.com/puCDwWUJ
  + Hàm charCodeAt() trả về giá trị Unicode của một ký tự tại một vị trí được xác định trong chuỗi.
  + Đọc code sau đó ta tìm được Role=@dmiN. 

Bước 4: Nhập vào trang web, ta nhận được flag 

> ![image](https://user-images.githubusercontent.com/90112096/140250185-ef75d970-8d7e-48fb-9497-cb9eba70029c.png)

**Flag{JAV-ascript_F*ck}**
