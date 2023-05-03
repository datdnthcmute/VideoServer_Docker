# [HTTP API video server](https://github.com/datdnthcmute/VideoServer_Group20) nhóm 20  

<b><i>GVHD: TS. Huỳnh Xuân Phụng</i></b>

Thành viên nhóm 20:
- Đặng Nguyễn Thiên Đạt - 20110629
- Nguyễn Thị Bích Liên - 20110335   

## Các yêu cầu về môi trường

Các yêu cầu dưới đây phải được cài đặt:

 * Python (>= 3.6)
 * FFmpeg
 * MongoDB 
 * RabbitMQ (celery backend)
 
 
## Các bước cài đặt:
 
### Chạy với Docker
 
#### Sử dụng Docker-compose
```
Đầu tiên sử dụng git clone đồ án của nhóm về:
> git clone https://github.com/superdesk/video-server-app.git
Tiến hành chạy docker-compose để tạo container:
> docker-compose up -d
```

:Lưu ý:  
 Khi chạy với docker compose mọi yêu cầu dịch vụ như trên FFmpeg, MongoDB, RabbitMQ sẽ không được yêu cầu tải trên localhost mà sẽ được tải tự động vào container của docker.


### Superdesk

Bản quyền thuộc về Superdesk việc sử dụng ở đây chỉ dành cho mục đích học tập 

To use a video-server with a [Superdesk](https://github.com/superdesk/superdesk-core) see the [docs](https://github.com/superdesk/superdesk-core/blob/develop/docs/video_server.rst)
