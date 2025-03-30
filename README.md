# instrumental_music_generation_PM09_AIO2024

# Instrumental Music Generation - Project M09 - AIO2024

Music Generation là một bài toán thuộc lĩnh vực Xử lý âm thanh và các mô hình tạo sinh (generative models), liên quan đến việc xây dựng một hệ thống có khả năng tạo ra các đoạn nhạc mới dựa trên một đoạn nhạc mẫu (sound snippet) hoặc các tham số âm thanh nhất định. Mục tiêu của bài toán sinh nhạc không chỉ dừng lại ở việc sao chép phong cách của mẫu nhạc, mà còn hướng đến sự biến tấu sáng tạo, để có thể sinh ra các đoạn nhạc hoàn toàn mới và độc đáo.

Project này phát triển một chương trình tạo sinh nhạc mới dựa trên một tín hiệu âm thanh gốc kèm theo một danh sách nhãn các thể loại nhạc. Tổng quan,
 Input và Output của bài toán như sau:

- **Input:** Một mẫu âm thanh và danh sách nhãn thể loại âm thanh đầu ra mong muốn.
- **Output:** Đoạn âm thanh mới được sinh ra, mang đặc trưng của đoạn âm thanh mẫu giao
 thoa với danh sách các nhãn thể loại đầu vào

![Pipeline project](/readme_image/pipeline.png "AIO2024")

## Reference: 
Kiến thức về AE và VAE xem tại: [exercise M09W03 - VAE Model](https://github.com/hieuhatinh/VAE_model_exM09W03_AIO2024)