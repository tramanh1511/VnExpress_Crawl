# Dataset: Vietnamese News (VnExpress)

## 1. Giới thiệu

Bộ dữ liệu này gồm các bài báo tiếng Việt được thu thập từ [VnExpress](https://vnexpress.net). Mỗi dòng tương ứng với một bài báo.

---

## 2. Cấu trúc dữ liệu

Các cột trong dataset:

- **id**: ID bài báo (trích từ URL)  
- **url**: Link bài báo  

- **title**: Tiêu đề  
- **summary**: Mô tả ngắn (đoạn văn đầu bài)  
- **content**: Nội dung bài báo  
- **word_count**: Số từ trong nội dung  

- **author**: Tác giả (có thể thiếu)  
- **publish_date**: Thời gian đăng bài  

- **category**: Chuyên mục chính  
- **sub_category**: Chuyên mục con (nếu có)  

- **num_images**: Số lượng ảnh  
- **images**: Danh sách ảnh (dạng JSON string)  

- **tags**: Từ khóa liên quan  
- **num_comments**: Số lượng bình luận  

---

## 3. Đặc điểm dữ liệu

- Nội dung là văn bản tiếng Việt từ báo điện tử  
- Bao gồm nhiều lĩnh vực: thời sự, kinh tế, thể thao, giáo dục,...  
- Một số trường có thể bị thiếu (author, comments, ...)  
- Nội dung đã được làm sạch cơ bản (loại bỏ khoảng trắng thừa)


