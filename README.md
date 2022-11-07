# 介绍
借用：https://github.com/UltramanGaia/Xiaomi_Mi_WiFi_R3G_Vulnerability_POC
随便改了一下，大佬勿喷，凑活能用

# 优化后使用

## 格式

`http://<url>:<port>`

## 例子

```
python3 arbitrary_file_read_vulnerability.py -u http://192.168.0.1:8098                                   
```

```
usage: arbitrary_file_read_vulnerability.py [-h] [-u remote_address]

arbitrary_file_read_vulnerability.py

options:
  -h, --help            show this help message and exit
  -u remote_address, --url remote_address
                        Please input url to read.

```



```
python3 remote_command_execution_vulnerability.py -u http://192.168.0.1:8098 
```

```
usage: remote_command_execution_vulnerability.py [-h] [-u remote_address]

remote_command_execution_vulnerability.py

options:
  -h, --help            show this help message and exit
  -u remote_address, --url remote_address
                        Please input url to attack.
                                                       
```

