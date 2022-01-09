# pyddos.py

* Đây là bản cập nhật mới của tôi
* Script này có 3 kiểu tấn công ddos: SYNFLOOD | YÊU CẦU | Pyslow
* Script có kiểu tấn công pyslow tương tự như kiểu tấn công slowloris

# Ghi chú
* Tôi viết kịch bản này cho mục đích giáo dục không nhằm mục đích phá hoại và các hành động bất hợp pháp, vì vậy tôi sẽ không chịu trách nhiệm về điều đó

# Yêu cầu mô-đun
* màu sắc
* bức tranh màu

# Cách sử dụng
       
      _ \        __ \  __ \               ___|           _)       |   
     |   | |   | |   | |   |  _ \   __| \___ \   __|  __| | __ \  __|  
     ___/  |   | |   | |   | (   |\__ \       | (    |    | |   | |   
    _|    \__, |____/ ____/ \___/ ____/ _____/ \___|_|   _| .__/ \__|  
           ____/                                            _|         
                                                               
  Tập lệnh python DDos | Tập lệnh dùng để kiểm tra ddos | Tấn công Ddos      
  Tác giả: ___T7hM1___                                               
  Github: https://github.com/DauDau432/pyddos                             
  Version: 3.0 

    usage: ./pyddos -t [target] -p [port] -t [number threads]

    đối số tùy chọn:
    -h, --help       hiển thị thông báo trợ giúp này và thoát
    -v, --version    hiển thị số phiên bản của chương trình và thoát

    tùy chọn:

    -d <ip|domain>   Chỉ định mục tiêu của bạn như một ip hoặc tên miền
    -t <float>       Đặt thời gian chờ cho ổ cắm
    -T <int>         Đặt số luồng cho kết nối (mặc định = 1000)
    -p <int>         Chỉ định mục tiêu cổng (mặc định = 80) | Chỉ bắt buộc với tấn công pyslow |
    -s <int>         Đặt thời gian ngủ để kết nối lại
    -i <ip address>  Chỉ định ip giả mạo trừ khi sử dụng ip giả
    -Request         Bật mục tiêu yêu cầu
    -Synflood        Bật tấn công synflood
    -Pyslow          Bật tấn công pyslow
    --fakeip         Tùy chọn tạo ip giả nếu không chỉ định ip giả mạo

    Thí dụ:
        ./pyddos -d www.example.com -p 80 -T 2000 -Pyslow
        ./pyddos -d www.domain.com -s 100 -Request
        ./pyddos -d www.google.com -Synflood -T 5000 -t 10.0
