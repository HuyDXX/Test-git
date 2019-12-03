# Graylog Sidecar



Graylog 3.0 đi kèm với việc triển khai 1 Sidecar mới( Graylog Sidecar) (vẫn hỗ trợ Collector Sidecar cũ) **System / Collectors (legacy)**

**Định nghĩa**: Graylog Sidecar là 1 hệ thống quản lý cấu hình nhẹ cho các log collector khác nhau. Các Graylog node hoạt động như trung tâm chứa các cấu hình của các log collector.Sidecar có thể chạy như service( trên Win) hay daemon (trên Linux)

![Imgur](https://i.imgur.com/5WirnEg.png)

Các cấu hình của log collector được quản lý tập trung thông qua giao diện web Graylog.