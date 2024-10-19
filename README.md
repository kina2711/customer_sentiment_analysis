# BÁO CÁO PHÂN TÍCH DỮ LIỆU BÌNH LUẬN NGƯỜI DÙNG FPT PLAY

**Link báo cáo chi tiết**: [[Link](https://south-fine-1b1.notion.site/Project-4-B-O-C-O-PH-N-T-CH-D-LI-U-B-NH-LU-N-NG-I-D-NG-FPT-PLAY-1237359e5f5880219141c3656e5c502e?pvs=4)]

# **1. Giới thiệu**

Bối cảnh cạnh tranh của các nền tảng phát trực tuyến (OTT) tại Việt Nam đang ngày càng trở nên gay gắt, với sự xuất hiện của nhiều đối thủ mạnh mẽ như Vieon, Galaxy Play, và nhiều dịch vụ khác. Để duy trì lợi thế cạnh tranh và thu hút người dùng, việc phân tích hành vi và cảm xúc người dùng qua bình luận trở thành yếu tố thiết yếu, giúp doanh nghiệp hiểu rõ hơn về trải nghiệm khách hàng, tối ưu hóa nội dung và cải thiện chất lượng dịch vụ.

Báo cáo này phân tích 885.169 bình luận từ người dùng FPT Play trong giai đoạn từ **13/05/2015 đến 30/08/2022**, sử dụng phương pháp phân tích chẩn đoán (**diagnostic analytics**) kết hợp với phân tích mô tả (**descriptive analytics**) - không chỉ mô tả các xu hướng và mẫu dữ liệu mà còn đưa ra các nguyên nhân tiềm năng gây ra các kết quả này, đồng thời đề xuất giải pháp cụ thể. Các yếu tố chính được xem xét bao gồm: xu hướng bình luận theo thời gian, loại thiết bị, loại nội dung, và cảm xúc của người dùng. **Mục tiêu chính của báo cáo là xác định nguyên nhân các xu hướng bình luận, cảm xúc người dùng, và đưa ra các khuyến nghị cụ thể nhằm cải thiện hiệu quả dịch vụ.**

# **2. Phương pháp**

## 2.1. Nguồn dữ liệu

Dữ liệu được thu thập từ bình luận của người dùng trên nền tảng FPT Play, bao gồm các loại nội dung chính:

- **Video on Demand (VOD)**: Phim truyền hình, phim lẻ, và các nội dung độc quyền.
- **Sport**: Các trận đấu thể thao và sự kiện liên quan.
- **TV Show**: Các chương trình truyền hình giải trí.

## 2.2. Phân tích cảm xúc

Mô hình phân tích ngôn ngữ **PhoBERT AI** của VinAI được sử dụng để phân loại các bình luận thành ba nhóm cảm xúc chính:

- **Tích cực**
- **Tiêu cực**
- **Trung tính**

## 2.3. Phân tích chẩn đoán

Phương pháp phân tích chẩn đoán được áp dụng nhằm xác định các nguyên nhân tiềm năng của các xu hướng bình luận, bao gồm cả những vấn đề kỹ thuật và nội dung, từ đó đưa ra các khuyến nghị mang tính cải thiện dịch vụ.

# **3. Kết quả phân tích**

## 3.1. Tổng quan bình luận

Dữ liệu về lượt bình luận của người dùng FPT Play kéo dài từ ngày 13/05/2015 đến hết 30/08/2022.

**Phạm vi tương tác của người dùng:**

Người dùng FPT Play có thể bình luận trên ba loại nội dung chính:

- **Chương trình phát sóng trực tiếp** như thể thao, sự kiện của FPT Play.
- **VOD** (phim truyền hình, phim lẻ và các nội dung độc quyền của FPT).
- **TV Show** trên nền tảng FPT Play.

**Số lượng nội dung được FPT Play cung cấp:**

Tổng cộng có **22.545 nội dung số** được cung cấp, với số lượt bình luận trung bình trên mỗi nội dung là **39.3 lượt**, cho thấy **mức độ quan tâm cao của người dùng**, đặc biệt là với các chương trình **VOD**.

**Trong tổng số 885.169 bình luận:**

- **Tích cực**: **285.639 (32.3%)**
- **Tiêu cực**: **303.983 (34.3%)**
- **Trung tính**: **295.547 (33.4%)**
    
    Số lượng bình luận tiêu cực cao hơn so với bình luận tích cực, chủ yếu tập trung vào các vấn đề kỹ thuật và trải nghiệm người dùng trên các nội dung **VOD** và **Sport**.
    

**Có 3 loại nội dung chính cho phép người dùng bình luận là VOD, Sport và TV Show có tỷ lệ Comment như sau:**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/7e5cc2fb-24ba-48f5-a663-eef35ead753c/image.png)

**Các lượt bình luận của người dùng tập trung vào khung giờ từ 13 đến 17 giờ hàng ngày.**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/d205c65d-56cf-4d7e-9fa9-b80f91c31c3d/image.png)

## 3.2. Phân tích xu hướng bình luận theo thời gian

### 3.2.1. Phân tích theo năm

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/1f28c204-bf68-4af1-9f81-4d896e2ae2e0/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/e203d9b2-6176-4555-93c4-b409caafcb4d/image.png)

Lượng bình luận của người dùng đạt đỉnh vào **năm 2018** và **năm 2019**, chủ yếu do ảnh hưởng của sự kiện thể thao lớn là **World Cup 2018**. Các đợt tăng đột biến bình luận trong các tháng 6 và 7/2018 trùng khớp với thời gian diễn ra vòng bảng và các trận đấu knock-out của giải đấu này. Trong năm 2019, tuy thể thao ít nổi bật hơn, nhưng VOD lại chiếm ưu thế trong thu hút tương tác người dùng, cho thấy người dùng ngày càng chuyển hướng từ thể thao sang các chương trình giải trí và phim ảnh. Tuy nhiên, từ **năm 2020**, lượng bình luận bắt đầu giảm mạnh, một phần do thiếu vắng các sự kiện thể thao lớn trong bối cảnh dịch bệnh và sự thay đổi trong thói quen người dùng.

- **Giai đoạn World Cup 2018**: Bình luận tập trung vào các trận đấu và highlight, với những trận quan trọng thu hút hàng nghìn bình luận, cả tích cực lẫn tiêu cực. Tương tác cao đồng nghĩa với việc gia tăng nhận diện thương hiệu cho FPT Play trong khoảng thời gian này.
- **Năm 2019**: Tuy có ít sự kiện thể thao hơn, nhưng nội dung **VOD** và các chương trình **phim bộ Trung Quốc** phát sóng song song đã giữ vững lượng tương tác, chứng tỏ sức hút mạnh mẽ của các nội dung giải trí dài tập.

**Nguyên nhân tiềm năng**:

- Tương tác tăng đột biến vào năm 2018 là do sự hấp dẫn của các sự kiện thể thao quốc tế lớn.
- Sự giảm sút sau 2019 có thể liên quan đến sự thiếu hụt của các sự kiện lớn và thay đổi trong cách người dùng tiêu thụ nội dung giải trí.

**Khuyến nghị**: Tận dụng các sự kiện thể thao lớn như World Cup và Euro, đồng thời lên kế hoạch cho các **chiến dịch quảng bá nội dung VOD** vào các thời điểm ít sự kiện thể thao để giữ vững tương tác.

### 3.2.2. Phân tích tương tác người dùng theo khung giờ

Hoạt động của người dùng chủ yếu diễn ra trong khung giờ từ **13 giờ đến 17 giờ** hàng ngày. Đây là khoảng thời gian lý tưởng để FPT Play giới thiệu nội dung mới, chạy các chương trình khuyến mãi hoặc thúc đẩy tương tác trong ứng dụng nhằm tối đa hóa sự tham gia của người dùng.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/1a97c42c-b8d9-4f8d-8897-28657150a9f7/image.png)

Đây là dữ liệu về lượng comment của người dùng tại thời điểm tháng 06/2018. Các nội dung nhận được nhiều lượt bình luận nhất là các Highlight về bóng đá.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/ba72ed97-98e0-4b09-9eb9-b12cd262a7b7/image.png)

Xu hướng này tiếp tục diễn ra trong tháng 07/2018 khi số lượng bình luận vẫn tăng đột biến, chỉ thấp hơn một chút so với VOD. Nguyên nhân khá rõ ràng, từ ngày 30/06/2018, vòng chung kết World Cup đã bước vào giai đoạn 1/8, do đó số trận đấu cũng như các video highlight giảm đáng kể so với vòng bảng. Ngoài ra, các trận đấu được tổ chức với mật độ giãn hơn, tối đa chỉ 2 trận mỗi ngày, so với 4 trận một ngày diễn ra liên tục từ ngày 14/06/2018.

Số lượng bình luận cao cho thấy người dùng đã biết đến và sử dụng FPT Play nhiều hơn nhờ sự kiện World Cup 2018.

Tiếp theo, chúng ta sẽ xem xét đến năm 2019, khi số lượng bình luận đạt đỉnh vào tháng 07/2019.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/47c58c32-6141-4f1d-a064-038e7167a9f0/image.png)

Mặc dù tháng 07/2019 có diễn ra giải bóng đá Nam Mỹ, nhưng giải đấu này hầu như ít được khán giả Việt Nam theo dõi do khung giờ phát sóng không thuận lợi (bắt đầu vào lúc 2 giờ sáng và thường kết thúc gần 9 giờ sáng).

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/f4ab27eb-2006-4577-878b-42e2853509f9/image.png)

Mặc dù các nội dung thể thao vẫn được xem, nhưng số lượng rất nhỏ và không đáng kể so với VOD. Điều này cho thấy lượng bình luận và sự thu hút người dùng chủ yếu đến từ các VOD về phim ảnh, hoạt hình, và các chương trình giải trí mà FPT Play đang cung cấp, thay vì nội dung thể thao như năm 2018.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/fc889dd6-ed80-40ea-870d-9ec07d03c5ed/image.png)

Trên đây là biểu đồ thể hiện số lượt bình luận của người dùng theo từng khung giờ. Có thể thấy, lượng bình luận tập trung chủ yếu trong khoảng từ 13 giờ đến 17 giờ.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/c733f64e-6b34-4d3b-933c-73ac39512a6d/image.png)

Lượng bình luận chủ yếu tập trung vào VOD và các video highlight thể thao (World Cup 2018). Tương tự, trong năm 2019, khoảng thời gian từ 13 giờ đến 17 giờ cũng ghi nhận số lượt bình luận cao nhất. Tuy nhiên, điểm khác biệt là lượng bình luận năm 2019 chủ yếu tập trung vào VOD thay vì các nội dung thể thao như năm 2018.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/c877130d-ff55-4f10-81c4-22f1f39702aa/image.png)

Dữ liệu cho thấy lượng bình luận của người dùng tập trung nhiều nhất vào khung giờ từ **13 giờ đến 17 giờ** mỗi ngày. Đây là khoảng thời gian mà nhiều người dùng có khả năng truy cập vào FPT Play, đặc biệt là dân văn phòng hoặc học sinh, sinh viên.

**Nguyên nhân tiềm năng**:

- Khung giờ buổi chiều thường là thời gian nghỉ ngơi hoặc giải trí, khiến người dùng có nhiều thời gian để tương tác với các nội dung trên nền tảng.

**Khuyến nghị**:

- **Tăng cường quảng bá** nội dung mới vào khoảng thời gian này để tăng khả năng tương tác của người dùng.
- **Chạy các chương trình khuyến mãi** hoặc sự kiện đặc biệt vào giờ cao điểm này để thu hút thêm người dùng.

## 3.3. Phân tích số lượng bình luận của người dùng trên các thiết bị

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/12f84442-87c9-487c-995a-453f74e9a286/image.png)

Phân tích cho thấy phần lớn người dùng truy cập FPT Play và để lại bình luận thông qua **thiết bị Android**, tiếp theo là **iOS** và **trình duyệt web**. Đây là điều dễ hiểu khi nhiều người dùng tiếp cận FPT Play qua các thiết bị di động thông minh hoặc Smart TV.

- **Android**: Chiếm tỷ lệ cao nhất, phần lớn do sự phổ biến của Android trên thị trường thiết bị thông minh tại Việt Nam, bao gồm cả Smart TV và điện thoại di động.
- **iOS**: Đứng thứ hai, chủ yếu từ các thiết bị di động như iPhone và iPad.
- **Web**: Dù không phải là nền tảng phổ biến nhất, vẫn chiếm một tỷ lệ đáng kể, đặc biệt từ các người dùng trên desktop.

**Nguyên nhân tiềm năng**:

- Android chiếm lĩnh thị trường Smart TV và điện thoại tại Việt Nam, giúp FPT Play dễ dàng tiếp cận người dùng qua nền tảng này.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/778fdcda-32f9-4867-ba8b-0d4cacc32e15/image.png)

Trên đây là biểu đồ hiển thị số lượng bình luận của những người dùng có lượt bình luận cao nhất. Phần lớn người dùng chỉ bình luận trên một loại thiết bị, chủ yếu là Android và iOS. Tuy nhiên, có một người dùng, mã 1704078, đã bình luận trên cả ba nền tảng: Android, iOS và web của FPT Play. Điều này có thể lý giải bởi chính sách chia sẻ tài khoản của FPT Play trong cùng một gia đình, cho phép người dùng chia sẻ tài khoản và truy cập nội dung trên nhiều nền tảng khác nhau.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/bab529e1-18cf-498b-b285-8c0688bab933/image.png)

Trên đây là các nội dung mà người dùng 1704078 đã bình luận trên FPT Play.

**Khuyến nghị**:

- **Tối ưu hóa trải nghiệm người dùng trên Android**, với giao diện thân thiện hơn và tốc độ phản hồi nhanh hơn. Đặc biệt là trải nghiệm xem trực tuyến và tương tác trên Smart TV.
- **Nâng cấp ứng dụng iOS** để đảm bảo tính cạnh tranh và giữ chân người dùng trong nhóm thiết bị cao cấp.

## 3.4. Phân tích số lượng bình luận của người dùng trên nội dung được FPT Play cung cấp

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/071b9eba-e26d-4925-b741-3f186de37c4d/image.png)

1. **VOD (Video on Demand)**:
    - VOD là loại nội dung có nhiều bình luận nhất, trong đó bình luận tiêu cực chủ yếu liên quan đến **quảng cáo quá nhiều** và **tốc độ tải phim chậm**. Một số phim dài tập nhận bình luận tiêu cực khi người dùng cảm thấy thời gian phát hành tập mới quá chậm.
2. **Sport (Thể thao)**:
    - Bình luận về thể thao, đặc biệt là **highlight và trận đấu trực tiếp**, thường mang cảm xúc mạnh mẽ, nhất là khi đội nhà thua hoặc chất lượng phát sóng không đạt yêu cầu (bị giật lag, mất kết nối). Đây là khu vực nhạy cảm, đòi hỏi sự đầu tư về hạ tầng kỹ thuật để tránh làm mất lòng người dùng.
3. **TV Show**:
    - Các chương trình giải trí và TV Show ít nhận được bình luận tiêu cực hơn, thường là các bình luận tích cực liên quan đến nội dung giải trí nhẹ nhàng như chương trình thiếu nhi và phim hoạt hình.

**Nguyên nhân tiềm năng**:

- **Quảng cáo nhiều** trên các VOD gây khó chịu cho người dùng không đăng ký gói VIP.
- Các sự cố về kỹ thuật trong phát sóng trực tiếp ảnh hưởng đến trải nghiệm xem thể thao.

**Khuyến nghị**:

- **Giảm thiểu số lượng quảng cáo** cho người dùng miễn phí hoặc cải thiện trải nghiệm quảng cáo để tránh bình luận tiêu cực.
- **Cải thiện chất lượng đường truyền** cho các sự kiện thể thao trực tiếp, đặc biệt là các giải đấu lớn như Ngoại Hạng Anh, nơi người dùng rất nhạy cảm với sự gián đoạn.

## 3.5. Phân tích lượt bình luận của người dùng theo cảm xúc

Để giải quyết bài toán này, mình sử dụng một AI có tên PhoBERT, được phát triển bởi VinAI tại VinUni. "Pho" trong tên là viết tắt từ "Phở" – món ăn rất phổ biến tại Việt Nam.

Link tham khảo: [[Link](https://github.com/VinAIResearch/PhoBERT)]

PhoBERT là mô hình phân tích ngôn ngữ tiếng Việt, được ứng dụng trong nhiều lĩnh vực như xác định loại từ, tự động hoàn thiện câu, và nhiều tác vụ ngôn ngữ khác.

Trong bài toán phân tích cảm xúc (Sentiment Analysis), chúng ta sẽ sử dụng một mô hình có sẵn, được huấn luyện dựa trên PhoBERT và một bộ dữ liệu gồm 30.000 bình luận đánh giá bằng tiếng Việt từ một trang thương mại điện tử.

Link mã nguồn tham khảo của tác giả Phạm Hữu Quang: [[Link](https://huggingface.co/wonrax/phobert-base-vietnamese-sentiment)]

Dưới đây là quy trình xử lý để tạo ra kết quả phân tích cảm xúc:

![Sentiment Analysis Procedure.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/0c07fdbf-a765-4ddb-9af6-d125699f7346/Sentiment_Analysis_Procedure.png)

Sau khi chạy Model, chúng ta sẽ thu được các kết quả lần lượt là:

- 0: Tiêu cực (Negative)
- 1: Tích cực (Positive)
- 2: Trung tính (Neutral)

Trước khi tiến hành phân tích, chúng ta sẽ mã hóa các giá trị 0, 1, 2 tương ứng với các trạng thái Tiêu cực, Tích cực và Trung tính.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/1078086b-92d6-4e6c-a12d-7cb9e9b5cb57/image.png)

Trên đây là một số kết quả tham khảo sau khi áp dụng mô hình để tạo ra kết quả trong cột "sentiment".

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/000399f9-ab96-4975-93d7-c3d11b2d3263/image.png)

**Phân tích kết quả:**

1. **VOD**: Nhận nhiều bình luận tiêu cực nhất, do **quảng cáo quá nhiều**, **tốc độ phát hành chậm**, và **chất lượng kỹ thuật kém**.
2. **Sport**: Các sự kiện thể thao, đặc biệt là **trực tiếp và highlight**, có xu hướng nhận nhiều bình luận tiêu cực liên quan đến **chất lượng đường truyền** và **trải nghiệm giật lag**.
3. **TV Show**: Nhận ít bình luận tiêu cực hơn, chủ yếu là các nội dung giải trí nhẹ nhàng và an toàn cho gia đình.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/7972d9b0-a4e8-411b-985b-d72f2387c2e6/image.png)

Bảng dữ liệu trên cho thấy số lượng bình luận tích cực và tiêu cực theo các thể loại mà người dùng đã bình luận (chỉ xem xét các thể loại có hơn 10 bình luận). Có thể thấy rằng các nội dung nhận được nhiều bình luận tích cực nhất thuộc về các nhóm như fadio, tvshow, phim-le, thể thao, tv-show, thiếu nhi, v.v.

Hầu hết những nội dung này là lành mạnh, do đó, mặc dù có một số bình luận tiêu cực, nhưng vẫn chiếm tỷ lệ nhỏ so với bình luận tích cực. Đây là nhóm thể loại nội dung mà FPT Play không cần quá lo lắng về việc kiểm soát bình luận của người dùng.

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0b482dd-ba81-4e7b-9b52-d1f61affe890/86aee211-4f60-4850-b876-f83dbb5aafa5/image.png)

Trong khi đó, các nội dung nhận được nhiều bình luận tiêu cực nhất thuộc về các nhóm như highlight, sự kiện, ngoại hạng Anh, v.v. Điều này cho thấy rằng các bình luận liên quan đến thể thao cần được phân bổ nguồn lực để hạn chế những nhận xét tiêu cực, bởi vì những nội dung này có ảnh hưởng lớn đến người dùng của FPT Play.

Ngoài ra, một số bình luận tiêu cực cũng xuất phát từ chất lượng dịch vụ mà FPT Play cung cấp, chẳng hạn như tình trạng lag và mất kết nối khi xem giải ngoại hạng Anh từ K+.

Bên cạnh đó, nếu xét về số lượng, nhóm sản phẩm phim VOD của FPT Play cũng đang nhận được nhiều bình luận tiêu cực. Một số vấn đề được người dùng đề cập khá chính xác, như quảng cáo quá dài đối với những người không đăng ký gói VIP của FPT Play, hay âm lượng quảng cáo lớn trong khi âm lượng phim VOD lại quá nhỏ. Thêm vào đó, chất lượng lồng tiếng của các bộ phim trên FPT Play không thực sự tốt, đặc biệt so với Vieon trên thị trường (So với Vieon trên thị trường thì FPT Play đang có chất lượng lồng tiếng và giọng đọc không thực sự tốt).

# **4. Kết luận**

Phân tích dữ liệu cho thấy FPT Play đã đạt được mức tương tác người dùng cao, đặc biệt là trong các sự kiện thể thao lớn và nội dung VOD. Tuy nhiên, có những thách thức rõ ràng trong việc **cải thiện trải nghiệm người dùng** liên quan đến quảng cáo, chất lượng phát sóng và tốc độ phát hành nội dung.

**Khuyến nghị tổng quan**:

1. **Tối ưu hóa trải nghiệm trên nền tảng Android** và **iOS**, với đặc biệt chú trọng vào các Smart TV và điện thoại thông minh.
2. **Cải thiện hạ tầng kỹ thuật** để đảm bảo chất lượng phát sóng trực tiếp cho các giải đấu thể thao, tránh sự cố gián đoạn.
3. **Tăng cường chiến lược quảng cáo**: Giảm số lượng quảng cáo hoặc tối ưu hóa nội dung quảng cáo để không làm phiền người dùng.
4. **Đẩy mạnh nội dung VOD**, đặc biệt là các chương trình phát sóng song song với Trung Quốc, đồng thời cải thiện tốc độ phát hành tập mới để giữ chân người xem.

Với các bước cải thiện này, FPT Play có thể tiếp tục giữ vững vị thế trong thị trường OTT đầy cạnh tranh, đồng thời cải thiện đáng kể sự hài lòng của người dùng.
