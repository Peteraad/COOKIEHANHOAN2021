# COOKIEHANHOAN2021
## CRYPTOGRAPHY
### Bài 1 : XOR 
[encrypt.zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471519/encrypt.zip)

#### ***Cách giải:***

Bước 1: Theo đề bài thì ta thấy đây là một bài dạng XOR, việc ta cần làm là dịch ngược đoạn mã 

> 6c464b4d514b744817491714487449174b57

Bước 2: Ở đây mình sẽ sử dụng tool XOR decode để có thể tìm ra flag qua trang 

> https://www.dcode.fr/xor-cipher 

**Flag{a^b=c=>b^c=a}**

### Bài 2 : MORSE
Suỵt! Tập trung và đeo tai nghe lên nào. Gà có nghe thấy nhịp beat không? Họ nói gì từ bên kia chiến tuyến Format: Flag{what_you_find}

>  [cipher .zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471540/cipher.zip)

#### ***Cách giải:***

Bước 1: Theo đề bài thì ta biết đây là một file âm thanh liên quân đến mã Morse. Cho nên ta dùng trang web ở dưới để hiểu được thông điệp nó muốn nói là gì

> https://morsecode.world/international/decoder/audio-decoder-adaptive.html

Bước 2: Ta tìm được thông điệp của bài cần 

> ![image](https://user-images.githubusercontent.com/90112096/140239644-2acc9f0b-cd35-463f-bb65-c54941590024.png)

**Flag{M.O.R.S.E.C.O.D.E}**

### Bài 3 : JULIUS CAESER
Vô tình khi khai quật khảo cổ, Gà tìm được một thông điệp bí ẩn khoảng hơn 100 năm trước công nguyên. Nghe đồn đây là một bí thuật đã bị thay đổi công thức của một vị tướng Julius Caesar, sau này trở thành vị vua đầu tiên của đế chế La Mã hùng mạnh. Hãy giúp Gà giải mật thư này!

> [cipher (9).txt](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471565/cipher.9.txt)

#### ***Cách giải:***

Bước 1: Như đề bài thì ta biết được đây là mã Caeser việc ta cần làm chỉ là decode nó qua trang 

> https://www.dcode.fr/caesar-cipher

Bước 2: Sau khi decode ta tìm được flag :3

> ![image](https://user-images.githubusercontent.com/90112096/140243394-c85ad1d8-1054-444c-9535-72a3197f6200.png)

**Flag{El_Clasico_Cipher}**

### Bài 4: SIXTY FOUR
Gà để lại một thông điệp bí mật nhưng nó không làm khó được trí thông minh của Mèo Yang Hồ.

> [cipher (10).txt](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471706/cipher.10.txt)

#### ***Cách giải:***

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

#### ***Cách giải:***

Bước 1: Thường thì đây là câu cho điểm các thí sinh nên việc ta cần làm chỉ là vào discord Cookie Hân Hoan. Vào phần ghim tin nhắn để kiểm tra xem có gì đáng lưu ý không.

Bước 2: Như dự đoán, ta tìm được flag :3 

> ![image](https://user-images.githubusercontent.com/90112096/140245063-6c5877e8-c84c-42ad-913f-c8fb666f628d.png)

***Flag{Cookie_Han_Hoan}***

## PROGRAMMING
### Bài 1 : SUM()
Bỏ qua tất cả các tích phân, đạo hàm, ma trận, sác xuất. Gà hãy kết nối tới máy chủ của Cookie Arena và thực hiện tính tổng của dãy số đã cho một cách nhanh nhất. Hãy học cách sử dụng Python và player.py để giải toán nha

> programming.letspentest.org 8111

> [player (2).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471782/player.2.zip)
 
#### ***Cách giải:***

Bước 1: Ta thử kết nối với programming.letspentest.org 8111 bằng netcat. Ta thấy được việc ta cần làm là tính tổng 10 số tự nhiên.

> ![image](https://user-images.githubusercontent.com/90112096/140245690-baa42b47-5ab5-4442-ae19-4c1bfa957465.png)

Bước 2: Ta bắt tay vào code socket. Các bạn nên đọc code để dễ hiểu hơn : https://pastebin.com/Xufdw1Wx

> ![image](https://user-images.githubusercontent.com/90112096/140245862-e2482351-7bd7-463b-8064-39c45851d8f3.png)

**Flag{1plust1_1s_2_qu1ck_mafth}**

### Bài 2 : PRO102
Rồi một ngày kia mắt anh tròn xoe như đường tròn lượng giác Khi bất ngờ một bài toán bậc 2 Cứ lầm tưởng rằng nghiệm duy nhất với ai Thật kinh hoàng phương trình vô nghiệm(st)

> programming.letspentest.org 8222

> [player (3).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7471805/player.3.zip)

#### ***Cách giải:***

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

#### ***Cách giải:***

Bước 1: Ta thử kết nối với programming.letspentest.org 8333 bằng netcat. Ta thấy được bài toán như sau

> ![image](https://user-images.githubusercontent.com/90112096/140246630-c174829d-5a66-4251-acbf-bd478aa53d70.png)

Bước 2: Sau một hồi tìm kiếm công thức và suy nghĩ thì mình nghiệm ra cách giải bài này là: Cứ chia n cho 3 đến khi bằng 1. Để giải thích cho cách giải này mình có ví dụ với n=9 như sau:

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

#### ***Cách giải:***

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

#### ***Cách giải:***

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

#### ***Cách giải:***

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

### Bài 4: IMPOSSIBLE
Học lỏm được công thức chế tạo lá chắn tàng hình của Hazy. Gà nhanh chóng đem về xây dựng hệ thống phòng thủ của riêng mình. Liệu nó có làm khó được Mèo Yang Hồ không?

> http://chal7.web.letspentest.org/

#### ***Cách giải:***

Bước 1: Vào trang web mở phần source code ta tìm được hàm checkPass()

> ![image](https://user-images.githubusercontent.com/90112096/140250747-b22f222f-326f-4876-9e35-fef8479e88f4.png)

Bước 2: Sau khi đọc sơ thì ta có thể hiểu được hàm sẽ nhận password. Sau đó sẽ xóa đi dãy "cookiehanhoan" sau đó chuyển qua dạng base 64 sau cùng so sánh với "Y29va2llaGFuaG9hbg==" ( hay ta có thể biết đây là cookiehanhoan ). Nhìn sơ quá thì có thể nghĩ rằng password sẽ là cookiehanhoancookiehanhoan. Tuy nhiên chúng ta phải thử mới biết được đáp án thật sự là cookiecookiehanhoanhanhoan ( Các bạn nên code ra thử để hiểu thêm ). Sau khi nhập password ta tìm được đáp án.

**Flag{Javascript_is_not_safe???}**

### Bài 5 : INFINITE LOOP 
Cuộc đời luôn là vậy. Một giây trước tưởng đã cùng đường, một giây sau có lại đầy hy vọng. Các chiến binh đã có công cụ mạnh mẽ trong tay, hãy dùng nó để can thiệp dòng chảy.

> http://chal6.web.letspentest.org/

#### ***Cách giải:***

Bước 1: Truy cập vào trang web, ta nhập bừa một đáp án nào đấy. Thì ta thấy nó ra một trang web lỗi :>

> ![image](https://user-images.githubusercontent.com/90112096/140251533-0aa5f712-a345-4536-aeef-fb9bf2a1b6fc.png)

Bước 2: Tuy nhiên nếu bạn để ý thì sau đó 1s thì nó có load lại web một lần nữa mà lần nãy chỉ số id=3 đã nhảy qua id=2. Vậy ta đoán được flag sẽ là một số nào đó

Bước 3: Sau đó ta dùng công cụ BurpSuite để can thiệp. 

> ![image](https://user-images.githubusercontent.com/90112096/140251844-2450f578-89c9-4fa1-a996-87f343d981d6.png)

Bước 4: Ta chỉ cần thay đổi biến id= ( trong khoảng từ 1-10 ) . Đến lượt id=6 ta đã tìm được đáp án.

> ![image](https://user-images.githubusercontent.com/90112096/140251966-ca2b616f-ee77-4a5a-bc70-c05f9044bcbf.png)

**Flag{Y0u_c4ptur3_m3_xD!!!}**

### Bài 6 : I AM NOT A ROBOT
Nếu là người thì cho xem tai, còn nếu là robot thì đứng ở ngoài. Bạn đã bị chặn

> http://chal2.web.letspentest.org/

#### ***Cách giải:***

Bước 1: Như tên đề thì việc ta làm là truy cập vào file robots.txt của trang web. Để tìm hiểu thêm về file này các bạn có thể đọc :

> https://gtvseo.com/robots-txt-la-gi/

Bước 2: Sau đó ta nhận được như hình:

> ![image](https://user-images.githubusercontent.com/90112096/140252799-afd462a0-c5df-4560-b4d0-b96030401c16.png)

Bước 3: Truy cập vào đường dẫn http://chal2.web.letspentest.org/fl@g1337_d240c789f29416e11a3084a7b50fade5.txt để lấy flag thôi

> ![image](https://user-images.githubusercontent.com/90112096/140252896-1efe9820-6456-42dc-8618-7ae0bc0618da.png)

**Flag{N0_B0T_@ll0w}**

### Bài 7 : SAUSE
Trình duyệt đang rất vất vả để chuyển đổi các đoạn mã thành hình ảnh và màu sắc. Hãy trải nghiệm góc nhìn của trình duyệt nhé!

> http://chal1.web.letspentest.org/

### ***Cách giải:***
 
Bước 1: Truy cập vào trang mở source code lên ta tìm được flag

> ![image](https://user-images.githubusercontent.com/90112096/140253054-49962d54-e847-4e45-bfae-90d094e4da71.png)

**Flag{Web_Sause_Delicious}**

## NETWORK
### Bài 1 : POST OFFICE MAN
Anh bưu tá này là một người mà Gà rất tin tưởng. Gà ủy quyền cho anh ấy lên bưu điện, nói chuyện với anh kiểm thư để lấy thư về.

Nếu giấy ủy quyền hợp lệ, anh kiểm thư sẽ giữ lại bản gốc rồi photocopy ra một bản khác để anh bưu tá đem về cho Gà. Để nhỡ trong trường hợp Gà có tức quá xé thư đi thì vẫn có thể lên đây lấy lại.

Đố bạn anh bưu tá sử dụng giao thức email nào để nói chuyện với anh kiểm thư?

> network.letspentest.org 9002

### ***Cách giải:***

Bước 1: Kết nối với network.letspentest.org 9002 bằng netcat, sau khi làm theo hướng dẫn ta nhập bừa một chuỗi gì đó để xem nó trả về cái gì 

> ![image](https://user-images.githubusercontent.com/90112096/140307972-d154d7af-599c-4ee2-8825-4bf6a086baac.png)

Bước 2: Sau khi biết rằng ta phải dùng POP3 để giao tiếp thì ta có thể đọc thêm về chúng qua trang web

> https://www.suburbancomputer.com/tips_email.htm

Bước 3: Sử dụng câu lệnh LIST nhận ra có 10 tin nhắn, kiểm tra từng tin bằng RETR, đến RETR 8 thì ta nhận được flag

> ![image](https://user-images.githubusercontent.com/90112096/140308307-7b4a581c-8d90-4635-953b-83b0c71487bd.png)

**Flag{1-Ha\/3-1o0o-UnS33n-3Ma1L}**

### Bài 2 : VERY GOOD SHIPPER
Hãy tham gia đấu trường Cookie phiên bản nhanh như chớp. Gà phải chọn ra đáp án đúng trong thời gian nhanh nhất.

Giao thức TCP sẽ giúp các câu trả lời của Gà luôn được đảm bảo gửi đến máy chủ của Cookie Arena mà không bị rơi rớt một từ nào.

Tuy nhiên, Gà đã quên cổng kết nối vào máy chủ. Chỉ nhớ mang máng là nó giống với thử thách "Scan me if you can"

network.letspentest.org

### ***Cách giải:***

Bước 1: Sử dụng công cụ nmap để scan các cổng đang có

> ![image](https://user-images.githubusercontent.com/90112096/140308727-44716514-c52d-4b59-b4e0-3cec7bad62ae.png)

Bước 2: Sau đó ta kết nối  network.letspentest.org qua cổng 9003 bằng netcat. Sau khi trả lời các câu hỏi đơn giản từ Cookie ta nhận được flag :3 

> ![image](https://user-images.githubusercontent.com/90112096/140308995-e1790202-86ff-4b93-8361-1fd3e35ec421.png)

**Flag{t00-ez-4-y0u}**

### Bài 3 : WHERE IS MY HOUSE ?
DNS CHÍNH LÀ XƯƠNG SỐNG CỦA INTERNET.

Tên miền hay Domain chính là địa chỉ trang web, thứ mà các bạn vẫn hay gõ vào trên thanh địa chỉ trên trình duyệt để đọc báo hay lướt web, xem phim.

Trên Internet mọi máy tính, máy chủ, các thiết bị mạng được kết nối và giao tiếp với nhau thông qua hệ thống cáp mạng chằng chịt và khổng lồ. Các máy tính sẽ được gán cho nhau những dãy số để định danh với nhau gọi là địa chỉ IP. Nói một cách dễ hiểu thì một ai đó muốn ghé thăm nhà bạn thì họ cần phải có địa chỉ nhà. Những dãy số địa chỉ này có độ dài có thể lên đến 12 hoặc 45 kí tự.

Đến mật khẩu 6 kí tự bạn còn không nhớ nổi, vì thế năm 1984 DNS (Domain Name System) được phát minh để giúp bạn kết nối với nhau bằng tên gọi.

Bạn chỉ cần nhớ letspentest.org thay vì những dãy số khô khan và kì quặc. Khi vừa Enter, hệ thống DNS bắt đầu hoạt động, nó như tấm bản đồ để chỉ cho bạn biết "Hey, cái tên miền của Cookie có địa chỉ IP là X.X.X.X, hãy tới đó mà lấy thông tin đê". DNS cũng trả lời cho bạn biết "X.X.X.X có phải địa chỉ nhà Cookie Hân Hoan hay không"

DNS cũng chứa các thông tin khác, nó gọi là các bản ghi (Record). Bạn thử tìm xem domain này còn có những bản ghi nào chứa những điều kì quặc không?

> letspentest.org

### ***Cách giải:***

Bước 1: Sau khi đọc đề thì mình cảm thấy câu này cần được chú ý " DNS cũng chứa các thông tin khác, nó gọi là các bản ghi (Record). Bạn thử tìm xem domain này còn có những bản ghi nào chứa những điều kì quặc không? ".

Bước 2: Việc mình làm là tìm Record của DNS, ở đây mình dùng trang này

> https://dnschecker.org/all-dns-records-of-domain.php?query=letspentest.org&rtype=ALL&dns=google

Bước 3: Sau đấy ta thấy được flag

> ![image](https://user-images.githubusercontent.com/90112096/140309337-f55f4305-f984-4be0-849f-b9e89b7e1b72.png)

**Flag{DNS_A_AAAA_TXT_CNAME}**

### Bài 4: SCAN ME IF YOU CAN
Nếu coi mỗi máy chủ là một ngôi nhà, trước khi xâm nhập vào bên trong, các Hacker phải thực hiện việc thăm dò. Họ xem xét đâu là điểm yếu nhất của ngôi nhà, chỗ nào là điểm mù camera? Chủ nhà hoặc bảo vệ sẽ phản ứng thế nào khi có xuất hiện các dấu hiệu bất thường?

Trong quá trình tìm kiếm lỗ hổng, Hazy thường xem xét ngôi nhà này có bao nhiêu cánh cửa đang mở (Port). Hãy sử dụng công cụ thân quen để "ném đá" vào tất cả các cánh cửa của ngôi nhà.

Biết rằng, cửa sổ được đánh số từ 8100 tới 9100

Dựa vào sự phản hồi bạn sẽ biết được những điều thú vị!

> network-insecure.letspentest.org

### ***Cách giải:***

Bước 1: Sử dụng công cụ nmap để scan các cổng đang có

> ![image](https://user-images.githubusercontent.com/90112096/140309649-71cf588b-1409-4b9e-8d9e-02741d1513ca.png)

Bước 2: Do cửa sổ được đánh số từ 8100 tới 9100, nên ta sẽ kết nối tới network-insecure.letspentest.org qua cổng 9003 bằng netcat. Sau đó ta nhận được flag.

> ![image](https://user-images.githubusercontent.com/90112096/140309811-bce420fb-896a-493c-83e4-17797e9f7f30.png)


**Flag{Every-Header-Have-It-Own-Meaning}**

### Bài 5 : SECURE HTTP 
HTTP và HTTPS đều là hai giao thức giúp trình duyệt của bạn truy cập, tương tác với các trang Web. Tuy nhiên khi sử dụng giao thức HTTP để truy cập Web ở một quán cà phê hay trong cùng một khu trọ thì tất cả các nội dung trao đổi nhạy cảm, cũng như mật khẩu của bạn trên Web đều có thể nghe lén.

Còn HTTPS (chữ S có nghĩa là Secure - Bảo mật) sinh ra để mã hóa dữ liệu trong quá trình trao đổi giữa trình duyệt và máy chủ bằng một chiếc Chứng chỉ (Certificate)

> network-insecure.letspentest.org 9004

### ***Cách giải:***
Bước 1: Ban đầu mình có ý định là kết nối network-insecure.letspentest.org 9004 bằng netcat. Tuy nhiên sau khi kết nối mình không hề nhận được gì nên mình thay đổi hướng khác ( Flag các bạn thấy là của bài scan me if you can ) 

> ![image](https://user-images.githubusercontent.com/90112096/140310067-8375e77d-d9bb-4b85-a857-08c88c44022d.png)

Bước 2: Sau đó mình nghĩ tới hướng sẽ dùng https look up để xem có gì bất thường không qua trang

> https://mxtoolbox.com/HTTPSLookup.aspx

Bước 3: Như dự đoán ta tìm được flag của bài :> 

> ![image](https://user-images.githubusercontent.com/90112096/140310336-724b71dc-1bbb-4c34-98fc-b0d327234098.png)

**Flag{This-Is-A-Trusted-One}**

## FORENSIC
### Bài 1: AUDICATY
Hazy gửi cho Gà một thông điệp bí mật, kèm một lời nhắn "Đừng vội vàng kết luận môt vấn đề, luôn phải để mắt thấy tai nghe"

> [squitgaem (2).zip](https://github.com/Peteraad/COOKIEHANHOAN2021/files/7474621/squitgaem.2.zip)

### ***Cách giải:***


