Tài liệu chỉ mang tính chất tham khảo 
Nếu có sai sót thì cút đừng xài

*** Phân biệt 2 điều dữ liệu trả về từ store - tap rxjs operator ***

this.store.pipe(
  select([SELECTOR]),
  tap(data => {
    ============================ DATA sẽ là kiểu dữ liệu cơ bản, hoặc do ta định nghĩa ========================
})



this.store.pipe(
  select([SELECTOR])
}) ============================= DATA sẽ là Observable ===================================================
