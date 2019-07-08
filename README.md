# Giới thiệu về Word2Vec và Neural Word Embbedding
## Giới thiệu về Word2Vec
Word2Vec là mạng neural 2 lớp được dùng để xử lý text. Đầu vào là một corpus văn bản. Đầu ra là một tập các vector đặc trưng đại diện cho các từ trong corpus. Word2vec không phải là một deep neural netword. Nó chuyển text thành dạng số thứ mà deep nets có thể hiểu được. [Deeplearning4j](https://deeplearning4j.org/) triển khai một dạng Word2vec phân tán cho Java và Scala, hoạt động trên Spark với GPU.
Ứng dụng Word2Vec không chỉ áp dụng trong việc phân tích ngữ pháp câu mà còn sử dụng cho [genes, code, lượt thích, playlists, social media đồ thị and chuỗi lời nói, chuỗi biểu tượng]... - những thứ mà có thể phân chia, tách biệt ra được.
