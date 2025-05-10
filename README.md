# 🪙 Simple Hardhat Token (MHT)

Đây là một dự án smart contract đơn giản sử dụng Hardhat, được xây dựng như một phần của portfolio Web3 Developer. Smart contract triển khai một token ERC-20 cơ bản với các chức năng tối thiểu như khởi tạo token, chuyển token, và kiểm tra số dư.

---

## 🚀 Triển khai

- ✅ Đã deploy lên mạng **Sepolia Testnet**
- 📄 Địa chỉ contract: [`0xf9Fd16806fEf33Eab2b48533E687B4D098CEE336`](https://sepolia.etherscan.io/address/0xf9Fd16806fEf33Eab2b48533E687B4D098CEE336)

---

## 🔧 Chức năng chính

- 🏷️ Tên token: `My Hardhat Token`
- 💱 Ký hiệu: `MHT`
- 🪙 Tổng cung: `1,000,000 MHT` (toàn bộ phân phối cho `msg.sender` khi deploy)
- 🔁 Chuyển token với hàm `transfer(address to, uint256 amount)`
- 📊 Kiểm tra số dư với hàm `balanceOf(address account)`
- 📡 Sử dụng event `Transfer` để theo dõi giao dịch

---



