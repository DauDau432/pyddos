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
                                                               
        DDos python script | Script used for testing ddos | Ddos attack     
         Author: ___T7hM1___                                                
         Github: http://github.com/t7hm1/pyddos                             
        Version:2.0 

    usage: ./pyddos -t [target] -p [port] -t [number threads]

    optional arguments:
    -h, --help       show this help message and exit
    -v, --version    show program's version number and exit

    options:

    -d <ip|domain>   Specify your target such an ip or domain name
    -t <float>       Set timeout for socket
    -T <int>         Set threads number for connection (default = 1000)
    -p <int>         Specify port target (default = 80) |Only required with pyslow attack|
    -s <int>         Set sleep time for reconnection
    -i <ip address>  Specify spoofed ip unless use fake ip
    -Request         Enable request target
    -Synflood        Enable synflood attack
    -Pyslow          Enable pyslow attack
    --fakeip         Option to create fake ip if not specify spoofed ip

    Example:
         ./pyddos -d www.example.com -p 80 -T 2000 -Pyslow
        ./pyddos -d www.domain.com -s 100 -Request
        ./pyddos -d www.google.com -Synflood -T 5000 -t 10.0
