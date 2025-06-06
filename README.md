# Phím tắt cho Vim

<details> 
  <summary>Normal mode</summary>

  Là để di chuyển con trỏ chuột:
  ### Di chuyển
  - `h`: ←
  - `j`: ↓
  - `k`: ↑
  - `l`: →
  - `f + từ khóa`: đến ký tự đang có trên dòng đó

  --- 
  ### Nhảy trỏ đến 
  - `w`: nhảy đến đầu từ tiếp theo
  - `e`: nhảy đến cuối từ hiện tại/ tiếp theo
  - `^`: nhảy đến ký tự đầu tiên của dòng
  - `$`: nhảy đến cuối dòng 
  - `G`: nhảy đến cuối file
  - `số + j`: nhảy xuống dòng cách số 
  - `số + k`: nhảy lên dòng cách số 
  - `số + G`: nhảy đến dòng số
  --- 
  ### Nhảy trỏ về
  - `b`: nhảy về đầu từ trước 
  - `gg`: nhảy về đầu file 
  - `0`: nhảy về đầu dòng
  ---
  ### Xóa 
  - `x`: xóa ký tự dưới con trỏ 
  - `X`: xóa ký tự trước con trỏ
  - `dd`: xóa cả dòng 
  - `dw`: xóa từ hiện tại  
  - `d$`: xóa từ vị trí hiện tại đến cuối dòng  
  - `D`: xóa từ vị trí hiện tại đến cuối dòng  
  - `di(`: xóa trong dấu ()
  - `di[`: xóa trong dấu [] 
  - `di{`: xóa trong dấu {}  
  ---
  ### Sao chép và Hoàn tác
  - `u`: hoàn tác 
  - `Ctrl + r`: làm lại thao tác vừa hoàn tác
  - `yy`: sao chép dòng hiện tại
  - `yw`: sao chép từ hiện tại
  - `p`: dán sau con trỏ 
  - `P`: dán trước con trỏ
  ---
  ### Tìm kiếm 
  - `/từ khóa`: Tìm kiếm từ khóa xuống dưới (tức là tìm ở dưới con trỏ trước)
  - `?từ khóa`: Tìm kiếm từ khóa lên trên (tức là tìm ở trên con trỏ trước)
  - `n`: nhảy đến kết quả tiếp theo
  - `N`: nhảy đến kết quả trước
  - `r`: thay thế ký tự tại con trỏ
  - `cw`: thay thế từ hiện tại (xóa luôn từ đó) 
  - `cc`: thay thế cả dòng ( xóa luôn cả dòng)


</details>
<details> 
  <summary>Insert mode</summary>

  Để chèn nội dung (trước khi bấm thì đang ở Normal mode)
  - `i`: vào insert mode con trỏ chuột bên trái 
  - `a`: vào insert mode con trỏ chuột bên phải 
  - `I`: vào insert mode con trỏ chuột đầu dòng 
  - `A`: vào insert mode con trỏ chuột cuối dòng
  - `o`: vào insert mode và chèn dòng bên dưới 
  - `O`: vào insert mode và chèn dòng lên trên 
  - `Esc` hoặc `Ctrl + c`: về Normal mode 
</details>

<details> 
  <summary>Visual mode</summary>
  
  Để như bôi đen 
  - `v`: vào `visual` mode 
  - `V`: chọn cả dòng
  - `Ctrl + v`: chọn cả khối (và nó là multi-cursor) 
  ---
  ### Chỉnh sửa sau khi chọn
  - `d`: xóa đoạn đã chọn
  - `y`: sao chép đoạn đã chọn
  - `p`: dán đè đoạn đã chọn
</details>

<details> 
  <summary>Command mode</summary>
  
  Dùng để dùng lệnh
  - `:w`: lưu file 
  - `:q`: thoát (lưu rồi mới thoát được)
  - `:wq`: lưu và thoát 
  - `:q!`: thoát không lưu
  - `:e` + tên file: mở file khác
  - `:vsp + tên file`: mở file bên split dọc
  - `:sp + tên file`: mở file bên split ngang
  - `:42`: nhảy đến dòng 42
  ---
  ### Thay thế 
  - `:%s/old/new/g`:  Thay tất cả `old` thành `new` trong toàn file
  - `:%s/old/new/gc`:  Thay có xác nhận từng cái (`y/n`)
  - `:10,20s/old/new/g`:  Thay từ dòng 10 đến 20
  - `:.s/old/new/g`:  Thay trên dòng hiện tại
  - `:'<,'>s/old/new/g`:  Thay trong đoạn đã chọn (visual mode)
  - `:noh`: no highlight search (xóa chế độ tìm kiếm)
</details>

--- 
### Split màn hình 

- `Ctrl + w + s`: Split ngang
- `Ctrl + w + v`: Split dọc
- `Ctrl + w + w`: di chuyển các màn hình 
- `Ctrl + w + h/j/k/l`: di chuyển các màn hình 
- `Ctrl + w + q`: Đóng cửa sổ hiện tại   

--- 
### Thoát nhanh 

- `ZZ`: Lưu và thoát 
- `ZQ`: Thoát không lưu
- ...
**
