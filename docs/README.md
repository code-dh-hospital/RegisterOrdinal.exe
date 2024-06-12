<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#
## 1.24.0612.1 [⬇️OneDrive](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FRegisterOrdinalexe%2F12406121-OneDrive.json) [⬇️GoogleStorage](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FRegisterOrdinalexe%2F12406121-GoogleStorage.json) [⬇️NasDHSolutions](https://dh-hos-code.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2F%2FdirectTo%2FRegisterOrdinalexe%2F12406121-NasDHSolutions.json)
- 🐛: Fix lỗi para tenphankhu bị thiếu giá trị khi quét và in stt tự động
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/395
## [v.1.24.0612.0]()
- ✨: TỰ ĐỘNG NHẬN DIỆN THẺ BHYT ƯU TIÊN VÀ TỰ ĐỘNG IN STT
- 🐛: Khi quét CCCD, tự động nhận dạng, không cần ấn nút lấy thông tin nửa.
- 🐛: Thông báo khi không tìm thấy mã thẻ BHYT
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/395
## [v.1.24.0611.0]()
- 🐛: Thêm điều kiện uutien = 1 khi check thẻ bhyt có được ưu tiên không theo dmchucai
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0607.3]()
- ✨:Build lại
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0607.2]()
- 🐛: Fix lỗi không bắt số được khi thêm điều kiện phankhu để get thông tin bệnh nhân

## [v.1.24.0607.1]()
- 🐛: Thêm điều kiện get thông tin bệnh nhân theo phankhu, tránh trường hợp gọi sai STT của phân khu khác
## [v.1.24.0607.0]()
- 🐛: Fix lỗi bắt STT tại quầy thuốc không lưu được, do thiếu điều kiên phankhu trong SQL


## [v.1.24.0606.0]()
- ✨: Thêm giao diện bắt STT tại quầy thuốc
- 🐛: Fix lỗi không bắt số ưu tiên được đối với trường hợp mã thẻ BH là mã định danh
![](https://i.imgur.com/Eq9ipK5.png)

## [v.1.24.0605.1]()
- 🐛: Fix lỗi xữ lý bệnh nhân ưu tiên
## [v.1.24.0605.0]()
- 🐛: Fix lỗi không nhận được bệnh nhân ưu tiên theo tuổi
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0604.0]()
- ✨: Thêm chức năng cho bắt số ưu tiên khi đã check ưu tiên từ lần khám trước đó
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0602.0]()
- 🐛: sữa lỗi phân khu cuối không bị set ưu tiên mặc định
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0601.0]()
- ✨: Bổ sung chức năng nhận diện đối tượng ưu tiên theo mã quyền lợi (3 ký tự đầu của mã thẻ BHYT)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0525.1]()
- ✨: Thêm chức năng bắt số thứ tự trên KIOS tại Trà Cú
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/368
## [v.1.24.0525.0]()
- ✨: Testv1
## [v.1.24.0517.0]()
- ✨: test