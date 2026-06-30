# GTFS Project — Tuyến xe buýt / dữ liệu giao thông 
Một tập dữ liệu GTFS-like và các bảng phụ trợ cho thông tin tuyến tàu/xe buýt (CSV). Mục tiêu: cung cấp tập dữ liệu thô (operators, routes, station fixes, headsigns, bus metadata) để phân tích, trực quan hoá hoặc làm nguồn cho chuyển đổi sang định dạng GTFS/khác.

---

## Tổng quan dự án
Kho này chứa nhiều bảng CSV mô tả:
- danh sách nhà vận hành (operators.csv),
- tuyến tàu (train_routes.csv),
- các sửa tọa độ nhà ga (train_stations_fixes.csv),
- thông tin headsign / hướng dừng tàu (train_stop_headsigns.csv),
- một bảng bus_data.csv với một số metadata cho nhà vận hành xe buýt.

Dữ liệu chủ yếu là bảng CSV có thể mở bằng Excel, pandas, hoặc các công cụ ETL/BI. Hai ảnh chụp màn hình (PBIDesktop_*.png) được thêm vào kho để minh họa trực quan (ví dụ: báo cáo Power BI làm mẫu).

---

## Tính năng (những gì thực sự có trong repo)
- Tập CSV dữ liệu về nhà vận hành, tuyến và một số bản vá tọa độ nhà ga.
- Thông tin headsign (những dòng hiển thị trên tàu/dừng) cho một số tuyến.
- Tập bus_data.csv chứa metadata nhanh cho nhà vận hành xe buýt (màu, có timetable hay không, comment).

Lưu ý: repo chỉ chứa dữ liệu thô (CSV) và hai hình minh họa; không có script chuyển đổi GTFS hay ứng dụng web trong kho.

---

## Hình ảnh minh họa
Ảnh được lưu trong repo và dùng để làm ví dụ trực quan (chụp từ Power BI hoặc báo cáo tương tự). Bạn có thể xem trực tiếp:
- Power BI — ví dụ 1  
  ![Power BI sample 1](https://raw.githubusercontent.com/viettu98/gtfs_project_tuyen_xe_bus/main/PBIDesktop_eg4LRcCpqq.png)
  - Ghi chú: ảnh này thể hiện dashboard/biểu đồ (minh họa) được tạo từ dữ liệu tuyến/nhà vận hành.

- Power BI — ví dụ 2  
  ![Power BI sample 2](https://raw.githubusercontent.com/viettu98/gtfs_project_tuyen_xe_bus/main/PBIDesktop_2JfVC3AwUB.png)
  - Ghi chú: ảnh này là chụp màn hình khác của báo cáo trực quan (bảng/biểu đồ/đoạn bản đồ).


---


