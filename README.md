**Design-Finite-State-Machine-Calculator-and-Digital-Stopwatch-using-Verilog-HDL-on-FPGA**

Đồ án cuối kỳ tập trung ứng dụng **Verilog HDL** để thiết kế, hiện thực hóa và kiểm chứng các hệ thống tuần tự đồng bộ trên FPGA. 
Mục tiêu của đồ án nhằm củng cố các kiến thức cốt lõi về:
1. Thiết kế Máy trạng thái hữu hạn (FSM - Finite State Machine): Quản lý luồng điều khiển, xử lý tín hiệu bất đồng bộ và đồng bộ hóa qua các trạng thái hoạt động của hệ thống
2. Xử lý tín hiệu ngoại vi: Thiết kế mạch lọc nhiễu nút nhấn (Debouncer) bằng thanh ghi dịch, mạch chia tần số (Clock Divider) để tạo xung nhịp chính xác từ nguồn xung hệ thống 50 MHz.
3. Giao tiếp thiết bị ngoại vi phần cứng: Điều khiển hiển thị số liệu trực quan qua các cụm LED 7 đoạn (`HEX0` – `HEX5`) và đèn LED đơn (`LEDR`) trên board mạch thực nghiệm DE10-Standard.

<img width="909" height="644" alt="image" src="https://github.com/user-attachments/assets/73f4fef4-9cb7-4825-ba02-d98da4426c7e" />
<img width="1050" height="643" alt="image" src="https://github.com/user-attachments/assets/c2a710f4-d210-47c8-8775-876613a216fb" />

