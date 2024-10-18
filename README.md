# Vietnamese Misspell Dataset from Social Media - Tập dữ liệu chính tả tiếng Việt trên mạng xã hội



[![DOI](https://zenodo.org/badge/499798982.svg)](https://zenodo.org/doi/10.5281/zenodo.10938147)

Dữ liệu được tập hợp thông qua các cuộc trò chuyện, bình luận trên các mạng xã hội, các đánh giá trên các trang thương mại điện tử thông dụng tại Việt Nam, với mục tiêu mở rộng thêm nguồn dữ liệu chính tả ngôn ngữ tiếng Việt, bên cạnh các nguồn dữ liệu chính tả hàn lâm thông dụng hiện tại như: Wikipedia, VNTC,...

Nếu muốn sử dụng, mời các bạn vui lòng liên hệ đến email: [thanh.hoquang@pm.me](mailto:thanh.hoquang@pm.me), và vui lòng dẫn nguồn của repo này trong bài viết của bạn:

Đóng góp dữ liệu tại: [___dataset collecting form___](https://forms.gle/YnE7nseD48dvhta4A)

## Nguyên tắc thu thập dữ liệu chính tả của nhóm
Một số nguyên tắc thu thập dữ liệu tin tức trên mạng xã hội mà chúng tôi áp dụng:
1. Trích dẫn, lấy một phần dữ liệu hoặc lấy hoàn toàn dữ liệu từ các bình luận, trao đổi trên các mạng xã hội thông dụng tại Việt Nam, tuy nhiên các thông tin liên quan đến thông tin cá nhân của những người có liên quan đến nội dung sẽ được loại bỏ hoặc xử lý. Ví dụ: _chú X gặp chú Y_, _anh X có đi làm không_,... Các trường hợp để tên riêng: Các nhân vật công chúng, nhân vật lịch sử, nhân vật hư cấu tiểu thuyết
2. Chủ đề thu thập không giới hạn, các chủ đề như: xe cộ, kinh tế, chính trị, giáo dục, y tế,... là mảnh đất màu mỡ của việc tranh luận trên mạng xã hội và cũng là nguồn dữ liệu vô hạn về chính tả tiếng Việt - cả ngôn ngữ nói và ngôn ngữ viết, cả hàn lâm lẫn bình dân, cả từ ngữ thông dụng và phương ngữ.
3. Khác với dữ liệu giàu ngữ cảnh \(rich context\) như Wiki spelling, Github typo, bộ dữ liệu VMDS lấy dữ liệu cơ bản từ các trang mạng xã hội \(facebook, youtube, zalo,...\), thương mại điện tử \(shopee, lazada, tiki, chợ tốt...\),... nơi mà dữ liệu ít ngữ cảnh hơn \(poor context\), tuy nhiên tần suất sai chính tả sẽ nhiều hơn.

## Danh sách các tập dataset khác về chủ đề chính tả tiếng Việt
1. [VNTC](https://github.com/duyvuleo/VNTC): bộ dữ liệu của tác giả [duyvuleo](https://github.com/duyvuleo)
2. Các bộ dữ liệu liên quan đến Vi-Wiki: [Dữ liệu chưa xử lý](https://dumps.wikimedia.org/viwiki/latest/), đã xử lý bởi [heraclex12](https://github.com/heraclex12/Viwiki-spelling)
3. [Github Typo Corpus](https://github.com/mhagiwara/github-typo-corpus/issues): Dữ liệu tổng hợp các lỗi chính tả từ các commit trên Github của Masato Hagiwara and Masato Mita, cấu trúc tương tự như bộ Wiki, tuy nhiên tiếng Việt chỉ là một trong 15 ngôn ngữ (hình như chỉ có khoảng 40 cases là tiếng Việt), nhưng với kích thước của bộ dataset này phù hợp cho việc phát triển các ứng dụng đa ngôn ngữ

## Trích dẫn

```
@software{thanh_h_2024_10938148,
  author       = {Thanh, H},
  title        = {{VFND/VMDS-vietnamese-misspell-dataset-from-Social- 
                   media: VMDS version 0.0.1: 5100 cases}},
  month        = apr,
  year         = 2024,
  publisher    = {Zenodo},
  version      = {v0.0.1.005},
  doi          = {10.5281/zenodo.10938148},
  url          = {https://doi.org/10.5281/zenodo.10938148}
}
```
