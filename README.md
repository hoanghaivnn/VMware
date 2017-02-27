# VMware
### Mục lục
[I.Giới thiệu](#gioithieu)

[II.Ưu và nhược điểm](#uuvanhuoc)
- [2.1 Ưu điểm](#uudiem)
- [2.2 Nhược điểm](#nhuocdiem)

[III.Hướng dẫn cài đặt VMware](#caidat)
- [3.1 Trên Windows](#trenwindows)
<ul>
<li>  [3.1.1 Cài đặt chương trình trên Windows](#ctwindows)</li>
<li>  [3.1.2 Cài đặt một hệ điều hành trên Windows](#hdhwindows)</li>
</ul>
- [3.2 Trên Linux](#trenlinux)
<ul>
<li>  [3.1.1 Cài đặt chương trình trên linux](#ctlinux)</li>
<li>  [3.1.2 Cài đặt một hệ điều hành trên linux](#hdhlinux)</li>
</ul>

[IV. Cấu hình mở rộng của VMware](#cauhinhmorong)
- [4.1 Lưu trạng thái ảo Snapshot](#snapshot)
- [4.2 Nhân bản máy ảo Clone](#clone)
- [4.3 Sử dụng VMware player](#vmwareplayer)
- [4.4 Sử dụng VMware tool](#vmwaretool)
- [4.5 Sử dụng Virtual Netwok Edittor](#vne)

[V. Kết luận](#ketluan)

=============================
<a name="gioithieu"></a>
## I.Giới thiệu
`VMware Workstation` là một phần mềm ảo hóa desktop mạnh mẽ dành cho các nhà phát triển/kiểm tra phần mềm và các chuyên gia IT cần chạy nhiều HĐH một lúc trên một máy PC. Người dùng có thể chạy các HĐH Windows, Linux, Netware hay Solaris x86 trên các máy ảo di động mà không cần phải khởi động lại hay phân vùng ổ cứng. VMware Workstation cung cấp khả năng hoạt động tuyệt vời và nhiều tính năng mới như tối ưu hóa bộ nhớ và khả năng quản lý các thiết lập nhiều lớp. Các tính năng thiết yếu như mạng ảo, chụp ảnh nhanh trực tiếp, kéo thả, chia sẻthư mục và hỗtrợPXE khiến VMware Workstation trởthành công cụmạnh mẽnhất và không thểthiếu cho các nhà doanh nghiệp phát triển tin họcvà các nhà quản trị hệ thống.

VMware Workstation họat động bằng cách cho phép nhiều HĐH và các ứng dụng của chúng chạy đồng thời trên một máy duy nhất. Các HĐH và ứng dụng này được tách ra vào trong các máy ảo. Những máy ảo này cùng tồn tại trên một phần cứng duy nhất. Các layer ảo của VMware sẽ kết nối các phần cứng vật lý với các máy ảo, do đó mỗi máy ảo sẽ có CPU, bộnhớ, các ổ đĩa, thiết bịnhập/xuất riêng

Có 3 loại VMware :
-  *Vmware work station*
- *Vmware server*
- *Vmware vsphere*

Trong đó :

- Vmware work station và vmware server dùng cho desktop, nó là 1 chương trình ứng dụng chạy trên hệ điều hành window hoặc linux giúp cho chúng ta tạo ra máy ảo 1 cách dễ dàng nhằm mục đích thử nghiệm PC hay tần dụng tối đa hiệu năng của PC để làm được nhiều việc khác
- Vmware vsphere nó là 1 nền tảng giúp chúng ta có thể tạo ra hạ tầng điện toán đám mây, nó gồm có các bộ ảo hóa hay được sử dụng cho các doanh nghiệp, khác với vmware work station, vmware server thì vmware vsphere không được sử dụng trong các máy tính cá nhân mà nó được sự dụng để cài đặt trực tiếp trên các máy server (máy chủ)

<a name="uuvanhuoc"></a>
## II. Ưu và nhược điểm
<a name="uudiem"></a>

### 2.1 Ưu điểm

Việc dùng máy ảo có rất nhiều lợi ích mạng lại như :
<ul>
<li> Khả năng bảo mật, tính tiện dụng cao , nếu máy ảo bị trục trặc hoặc bị virus thì máy thật vẫn không bị ảnh hưởng.</li>
<li>Tận dụng được tài nguyên thừa của máy thật.</li>
<li> Thiết lập và cài đặt nhiều hệ điều hành trên 1 hệ điều hành ban đầu.Tạo môi trường thử nghiệm cho nhiều mục đích
</ul>

<a name="nhuocdiem"></a>
### 2.2 Nhược điểm

Bên cạnh những ưu điểm trên thì việc sử dụng máy ảo cũng có nhiều hạn chế :
<ul>
<li> Thông thường, mỗi máy ảo chỉ dùng một tập tin để lưu tất cả những gì diễn ra trong máy ảo. Do đó nếu bị mất tập tin này xem như mất tất cả.</li>
<li> Nếu máy tính có phần cứng thấp thì việc chạy thêm máy ảo sẽ bị chậm và không đáp ứng được nhu cầu sử dụng của người dùng.</li>
<li>Do các máy ảo đều được thiết lập trên một máy tính nên khi máy thật xảy ra lỗi như hỏng hóc thì  các máy ảo cũng bị ảnh hưởng theo.</li>

<a name="caidat"></a>
## III.Hướng dẫn cài đặt VMware

<a name="trenwindowns"></a>
### 3.1 Trên Windows

<a name="ctwindows"></a>
#### 3.1.1 Cài đặt chương trình trên Windows

Sau khi đã tải bản VMware Workstation mới nhất tại [Trang chủ VMware](http://www.vmware.com/products/player/playerpro-evaluation.html), Chúng ta bắt đầu tiến hành cài đặt :

<img src=http://imgur.com/KJ9TK8g>
- Bước 2 : Sau đó bạn chọn `I accept the terms in the License Agreement` sau đó bạn nhấn Next để tiếp tục.

<img src=http://imgur.com/RuML1ut>
- Bước 3 :Nhấn Next để tiếp tục.

<img src=http://imgur.com/L07a0iD>
- Bước 4 : Ở bước này bạn bỏ chọn 2 phần như trong hình sau đó nhấn Next để tiếp tục.

<img src=http://imgur.com/Z2ZmPtI>

  Tích thứ nhất là kiểm tra cập nhật phiên bản khi máy tính khởi động.

  Tích thứ hai là gửi dữ liệu cho nhà sản xuất

- Bước 5 : Ở bước này ta chọn nơi lưu `shortcut`. Có thể chọn như hình

<img src=http://imgur.com/t5IaObT>

- Bước 6 : Chọn `Install`

<img src=http://imgur.com/HtF1SlH>

- Bước 7 : Chờ cài đặt

<img src=http://imgur.com/p2dFGhf>

- Bước 8 :Quá trình cài đặt thành công nhấn `License` để kích hoạt phần mềm.

<img src=http://imgur.com/2oSz1Uu>

- Bước 9 : Điền `Key` và chọn `Enter` để hoàn thành

<img src=http://imgur.com/ckRDdPF>

- Bước 10 : Finish - Kết thúc cài đặt

<img src=http://imgur.com/3pgLmZf>

<a name="hdhwindows"></a>
#### 3.1.2 Cài đặt một hệ điều hành trên Windows
