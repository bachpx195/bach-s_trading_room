```
Version 1:
  * Thêm nguyên tắc/chỉ dẫn
  * Sửa nguyên tắc/chỉ dẫn
     * Lý do?

Version 2:
  * Thêm nguyên tắc không giao dịch vào ngày chủ nhật
  * Thêm chỉ dẫn về đòn bẩy
  
Version 3:
  * Thêm nguyên tắc không giao dịch, chốt lời, cắt lỗ vào những mốc số tròn
  
Version 4:
  * Thêm nguyên tắc giao dịch vào khoảng thời mở đầu ngày
  
Version 5:
  * Thêm chỉ dẫn giao dịch vào chủ nhật và thứ 2
  
Version 6:
  * Thêm chỉ dẫn đặt TP trước khi ngủ

Version 7:
  * Thêm nguyên tắc cắt lệnh chạm entry khi giá đi sai dự đoán
```

RC: Real combat
PSY: Psycholog
FUND: fund management

# Nguyên tắc

### RC1: Không giao dịch
* Không giao dịch từ 14h - 18h
* Không giao dịch vào tối ngày chủ nhật.
* Không giao dịch ở các mốc số tròn.
* Khi nến ngày hôm trước tăng (hoặc giảm) mạnh so với các cây nên trước đó thì không giao dịch cùng chiều vào khoảng thời gian bắt đầu ngày.

### RC2: Không đặt lệnh vào lúc đóng nến
* Không đặt lệnh vào lúc đóng nến 1h hoặc 15m mà nên đợi đặt lệnh ở cây nến 15m tiếp theo

### RC3: Cắt lệnh
* Cắt lệnh khi giá chạm entry nếu giá đi sai dự đoán ~2% và mất 12h để giá quay lại entry

# Chỉ dẫn

### RC1: Quan sát cặp xxx/BTC
* Không nên mua khi xxx/BTC có dấu hiệu giảm và ngược lại

### RC2: Mua vào khi
* Khi giá mở cửa ngày giảm mạnh trong khoảng 7h thì cân nhắc đặt lệnh mua vào khoảng 9h khi giá quay về test đáy lần 1.

### FUND3: Chỉ dẫn đòn bẩy.
* Lệnh thua đầu tiên -> giữ nguyên đòn bẩy.
* Lệnh thua liên tiếp  thứ hai -> giữ nguyên đòn bẩy cho đến khi hòa vốn.
* Lệnh thua liên tiếp thứ ba ->  x2 nguyên đòn bẩy cho đến khi hòa vốn.
* Lệnh thua liên tiếp thứ tư ->  x3 nguyên đòn bẩy cho đến khi hòa vốn.
* Lệnh thua liên tiếp thứ năm ->  max đòn bẩy cho đến khi hòa vốn.

### FUND4: Chỉ dẫn quản lý vốn.
* Khi một lệnh thua thì cắt lệnh và đặt lại lệnh sao cho tổng vốn với đòn bẩy không đổi.

### RC5: Cắt lỗ lệnh bán vào cuối ngày chủ nhật và cắt lỗ lệnh mua vào cuối ngày thứ 2
* Xu hướng tăng khi kết thúc 1 tuần giao dịch và xu hướng giảm vào ngày thứ 2

### RC6: Đặt lệnh chốt lời (hoặc hoà vốn) trước khi đi ngủ
* Đặt lệnh chốt lời (~1%) hoặc dừng lệnh hoà vốn trước khi đi ngủ.
