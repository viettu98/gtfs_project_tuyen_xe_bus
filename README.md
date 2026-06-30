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

Tạo 2 dashboard PowerBI: 1 tổng quan - 1 chi tiết:

- Power BI — Ví dụ 1  
  ![Power BI sample 1](https://raw.githubusercontent.com/viettu98/gtfs_project_tuyen_xe_bus/main/PBIDesktop_eg4LRcCpqq.png)  
  Ảnh này thể hiện một dashboard tổng quan, nơi các biểu đồ và bản đồ được dựng từ dữ liệu tuyến và thông tin nhà vận hành.

- Power BI — Ví dụ 2  
  ![Power BI sample 2](https://raw.githubusercontent.com/viettu98/gtfs_project_tuyen_xe_bus/main/PBIDesktop_2JfVC3AwUB.png)  
  Ảnh chụp khác cho thấy bảng số liệu và các biểu đồ tương tác, minh họa cách trình bày và khám phá dữ liệu.


---


