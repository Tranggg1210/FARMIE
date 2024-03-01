### 1. Cắt web là gì 
- Cắt web tức là cắt HTML
- Cắt HTML tức là chuyển đổi giữa file PSD (hoặc file Adobe Illustrator hoặc cũng có thể là file PNG, figma tùy cách xuất file của thiết kế) sang một loại ngôn ngữ mới mà các trình duyệt và máy tính có thể đọc hiểu được. Ngôn ngữ đó được gọi là HTML. Phổ biến nhất bây giờ là HTML5/ CSS3. Cắt HTML là một phần của công nghệ Front End và người thực hiện công việc này được gọi là lập trình viên Front End.
- link tham khảo: https://freelancervietnam.vn/cat-html/

### 2. Các thẻ ngữ nghĩa trong html
- Các thẻ ngữ nghĩa trong html là: 
    + \<article>
    + \<aside>
    + \<details>
    + \<figcaption>
    + \<figure>
    + \<footer>
    + \<header>
    + \<main>
    + \<mark>
    + \<nav>
    + \<section>
    + \<summary>
    + \<time>
- link tham khảo: https://tedu.com.vn/hoc-html-can-ban/cac-phan-tu-ngu-nghia-trong-html5-222.html

### 3. box model css
- Box model trong css bao gồm: 
    + border
    + padding
    + content
    + margin
- Link tham khảo: https://www.w3schools.com/css/css_boxmodel.asp

### 4. box sizing css
- Theo mặc định, chiều rộng và chiều cao của một phần tử được tính như sau:
```
    chiều rộng + phần đệm + đường viền = chiều rộng thực tế của một phần tử
    chiều cao + phần đệm + đường viền = chiều cao thực tế của một phần tử
```
- Điều này có nghĩa là: Khi bạn đặt chiều rộng/chiều cao của một phần tử, phần tử đó thường xuất hiện lớn hơn mức bạn đã đặt (vì đường viền và phần đệm của phần tử được thêm vào chiều rộng/chiều cao được chỉ định của phần tử).
- Để khắc phục điều này người ta sử dụng: box-sizing
- Các thuộc tính của box-sizing là:
    + border-box
    + content-box
- Link tham khảo: https://www.w3schools.com/css/css3_box-sizing.asp
### 5. flexbox
- Flexbox là một phần của CSS3 được thiết kế để cung cấp một cách linh hoạt và mạnh mẽ để sắp xếp, căn chỉnh và điều khiển các phần tử trong một container hoặc layout. Flexbox cung cấp một cách tiếp cận dễ dàng và hiệu quả hơn so với các phương pháp truyền thống như sử dụng float, inline-block và bố cục bằng table.
- VD:
```sh
    .section{
        display: flex;
        justify-content: center;
        align-items: center;
    }
```
- Link tham khảo: https://www.w3schools.com/css/css3_flexbox.asp
### 6. responsive css
- Làm cho trang web tương thích hơn với từng loại thiết bị
- Cú pháp
```sh
@media not|only mediatype and (mediafeature and|or|not mediafeature)
{
    CSS-Code;
}
```
- Trong đó:
1. Keywords:
    + not: loại trừ (vd: not A nghĩa là loại A)
    + only: chỉ (vd: only A nghĩa là chỉ áp dụng với thằng A)
    + and
    + or
2. Mediatypes:
    + print: css cho chế độ in
    + screen: css cho chế độ màn hình
    + speech: css cho màn hình nói được
    + all-defaull
3. Media Features:
    + Min-width
    + Max-width 
- Link tham khảo: https://www.w3schools.com/css/css_rwd_mediaqueries.asp
### 7. thực hành 
- clone website: https://preview.colorlib.com/theme/farmie/