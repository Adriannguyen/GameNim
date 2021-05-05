# GameNim
Có một vài đống đá, mỗi đống sẽ có một số lượng biết trước các viên đá. Hai người sẽ chơi với nhau, đến lượt của mình, mỗi người sẽ lấy ra một số viên đá (ít nhất là 1 viên) từ một đống đá bất kỳ. Ai là người có lượt chơi cuối cùng sẽ là người chiến thắng. (Cũng có nghĩa là ai không thể tiếp tục cuộc chơi sẽ là người thua cuộc)

# Định lý Sprague - Grundy áp dụng vào thuật toán Nim
Có một trò chơi tổng hợp, hợp thành từ N trò chơi nhỏ giống nhau, và có 2 người chơi A và B. Nếu cả A và B đều có lựa chọn tối ưu trong mỗi bước đi của họ (nghĩa là không ai mắc một sai lầm nào), thì người chơi đầu tiên sẽ giành chiến thắng nếu XOR của các số Grundy của từng trò chơi nhỏ cho kết quả khác 0. Ngược lại, nếu kết quả này bằng 0, người chơi đầu tiên sẽ thất bại, bất kể anh ta dùng cách gì đi nữa.

Nếu cả A và B đều lựa chọn cách chơi tối ưu (nghĩa là họ không mắc một sai lầm nào trong bước đi của họ), thì người chơi A sẽ giành chiến thắng nếu tổng Nim của game khác không. Ngược lại, người chơi B sẽ chiến thắng, bất kể hai người đi như thế nào.
