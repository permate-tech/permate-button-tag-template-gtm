# Permate Button Tag - Google Tag Manager

Button Tag Template của Permate hỗ trợ chuẩn Google Tag template. Permate Button Tag nên được đặt ở trang cần theo dõi có button CTA, buộc đặt cùng với [Permate SuperTag](https://github.com/permate-tech/permate-supertag-template-gtm).

## Tổng quan tài liệu tích hợp

<ol>
  <li>Nhập (Import) Permate Button Tag Template vào mẫu Google Tag Manager của bạn.</li>
  <li>Cài đặt Permate Button Tag vào danh sách Tag của bạn.</li>
  <li>Cấu hình nâng cao Permate Button Tag.</li>
</ol>

## 1. Nhập (Import) Permate Button Tag Template

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Templates/Mẫu</b> sau đó chọn <b>New/Mới</b>.</li>
  <li>Click chọn vào dấu 3 chấm trên cùng bên phải, sau đó chọn <b>Import/Nhập</b>.</li>
  <li>Bạn cần tải về file <a href="https://github.com/permate-tech/permate-button-tag-template-gtm/blob/main/template.tpl"><b>template.tpl</b></a> sau đó nhập vào Template/Mẫu.</li>
  <li>Chọn Save/Lưu</li>

  ![GTM_Permate_Import_ButtonTag](https://github.com/user-attachments/assets/3db1a9ad-00ee-425f-8abd-d8b62047f573)
  ![GTM_Permate_ButtonTag_Template](https://github.com/user-attachments/assets/ceffc0d1-3127-4569-a07a-b6f2579ba035)
</ol>

## 2. Cài đặt Permate Button Tag

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Tag/Thẻ</b> sau đó chọn <b>New/Mới</b>.</li>
  <li>Chọn vào <b>Tag Configuration/Cấu Hình Thẻ</b>.</li>
  <li>Tại mục <b>Custom/Tuỳ chỉnh</b> tìm <b>Permate Button Tag</b> của Permate. Nếu bạn không tìm thấy, hãy thực hiện Import ở bước 1.</li>

  ![GTM_Permate_ButtonTag_View](https://github.com/user-attachments/assets/c1dbf61a-4b47-4696-8058-3d3239170d26)
  <li>Thẻ này sẽ cần sử dụng Trigger kích hoạt tất cả sự kiện <b>DOM Ready/DOM Sẵn sàng</b>. Bạn hãy đảm bảo khi cấu hình <a href="https://github.com/permate-tech/permate-supertag-template-gtm">Permate SuperTag</a> hoạt động được ở Trigger này.</li>
  
  ![GooogleTagManager_Trigger](https://github.com/user-attachments/assets/0cb3bff8-9490-4eec-b161-7637714b684c)
  <li>Đặt tên cho thẻ của bạn và mọi thứ đã hoàn thành.</li>
</ol>

## 3. Cấu hình nâng cao cho thẻ

<ol>
  <li>Đăng nhập vào tài khoản Google Tag Manager của bạn, chọn Account/Container tương ứng, chọn vào <b>Tag/Thẻ</b> sau đó chọn thẻ <b>Permate Button Tag</b> vừa mới tạo ở bước 2.</li>
  <li>Chọn vào <b>Advanced Settings/Cài Đặt Nâng Cao</b>.</li>
  <li>Tại mục <b>Tag firing priority</b>: Bạn cần điền giá trị nhỏ hơn giá trị của <a href="https://github.com/permate-tech/permate-supertag-template-gtm"><b>Permate SuperTag</b></a> (bắt buộc).</li>

  ![GTM_Permate_ButtonTag_Priority](https://github.com/user-attachments/assets/757e994c-5bbe-46e1-bec4-c5a5d28173cf)
  <li>Chọn <b>Save/Lưu</b> và mọi thứ đã hoàn thành.</li>
</ol>

## Tìm hiểu chi tiết hơn về Permate Button Tag
#### :arrow_right: Ghé thăm tại đây [Trung Tâm Trợ Giúp](https://permate.com/docs-category/brand-en/)
