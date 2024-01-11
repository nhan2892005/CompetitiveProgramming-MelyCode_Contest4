# J. Hộp quà Noel

## Mô tả
Ông già Noel đã gửi tặng cho Minh một hộp quà đặc biệt trong ngày Lễ Giáng Sinh. Bên trong hộp quà là n viên bi đầy màu sắc được xếp thành một hàng, viên bi thứ i có màu ci. Vì yêu thích sự đối xứng nên Minh quyết định chơi trò chơi sau: Tại mỗi bước, gọi len là số viên bi còn lại trong hộp, Minh chọn ra 2 số l và r (1≤l≤r≤len) sao cho dãy màu tạo bởi các viên bi từ l đến r tạo thành một dãy palindrome, tức là: cl=cr,cl+1=cr−1,cl+2=cr−2... Sau đó, Minh thực hiện lấy những viên bi từ l đến r ra khỏi hộp và những viên bi còn lại sẽ sáp lại với nhau. Tính số bước tối thiểu để lấy toàn bộ bi ra khỏi hộp với luật chơi trên.

## Input
- Dòng đầu tiên gồm số tự nhiên n (1≤n≤500) là số viên bi trong hộp.
- Dòng thứ hai gồm n số, số thứ i là màu sắc ci (1≤ci≤n) của viên bi thứ i trong hộp.

## Output
In ra số bước tối thiểu để lấy toàn bộ bi ra khỏi hộp.

## Examples
### Input
3

2 1 2

### Output
1

### Input
3

3 2 1

shell
Copy code
### Output
3


### Input
7

1 2 2 4 3 4 1

shell
Copy code
### Output
2


## Note
- Trong test thứ nhất, có thể lấy toàn bộ bi ra khỏi hộp trong lần đầu tiên.
- Trong test thứ hai, mỗi lần chỉ có thể lấy một viên bi ra khỏi hộp.
- Trong test thứ ba, lấy các bi 2,2 trước, sau đó lấy 1,4,3,4,1 ra khỏi hộp.
