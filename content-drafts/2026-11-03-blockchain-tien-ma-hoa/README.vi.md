# Nhóm "Blockchain và tiền mã hóa (kỹ thuật)" — bản nháp 03/11/2026

8 bài, key 515–522, `batch: 88`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 515 | Bitcoin Core: phần mềm nút đầy đủ của mạng Bitcoin, tải và xác thực mọi khối và giao dịch, có ví và giao diện tùy chọn; README nhắc dự án bảo mật nhạy cảm, một sai sót có thể làm mất nhiều tiền | [bitcoin/bitcoin](https://github.com/bitcoin/bitcoin) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 90594 | 2026-11-02 |
| 516 | go-ethereum (geth): bản cài đặt tầng thực thi của giao thức Ethereum bằng Go; README nêu yêu cầu phần cứng tối thiểu (4+ nhân, 8GB RAM, SSD 2TB) và giấy phép LGPL cho thư viện, GPL cho tệp thực thi | [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) | {'key': 'lgpl-3.0', 'name': 'GNU Lesser General Public License v3.0', 'spdx_id': 'LGPL-3.0', 'url': 'https://api.github.com/licenses/lgpl-3.0', 'node_id': 'MDc6TGljZW5zZTEy'} | 51460 | 2026-11-03 |
| 517 | Foundry: bộ công cụ viết bằng Rust để phát triển ứng dụng Ethereum gồm Forge (dựng, kiểm thử, fuzz hợp đồng Solidity), Cast, Anvil (nút cục bộ), Chisel (REPL Solidity) | [foundry-rs/foundry](https://github.com/foundry-rs/foundry) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 10751 | 2026-11-03 |
| 518 | OpenZeppelin Contracts: thư viện hợp đồng thông minh Solidity đã được cộng đồng thẩm định (ERC20, ERC721, phân quyền); README nói dùng không thay thế kiểm toán bảo mật | [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 27340 | 2026-11-02 |
| 519 | Cosmos SDK: bộ công cụ blockchain theo mô-đun bằng Go để dựng chuỗi lớp 1 tùy biến; README nói được dùng bởi hơn 200 chuỗi và có mô-đun doanh nghiệp theo giấy phép khác | [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 7082 | 2026-11-02 |
| 520 | Scaffold-ETH 2: bộ khởi tạo mã nguồn mở dựng ứng dụng phi tập trung (dapp) trên Ethereum với NextJS, RainbowKit, Foundry hoặc Hardhat, Wagmi, Viem; README nói sẵn sàng cho AI agent | [scaffold-eth/scaffold-eth-2](https://github.com/scaffold-eth/scaffold-eth-2) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 2064 | 2026-10-13 |
| 521 | BTCPay Server: bộ xử lý thanh toán Bitcoin miễn phí mã nguồn mở, tự host, cho người bán nhận Bitcoin trực tiếp không phí hay trung gian (theo README) | [btcpayserver/btcpayserver](https://github.com/btcpayserver/btcpayserver) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 7887 | 2026-11-03 |
| 522 | lnd: bản cài đặt đầy đủ của nút Lightning Network (mạng thanh toán lớp 2 của Bitcoin), quản lý kênh, định tuyến và thanh toán; README nêu mức tuân thủ đặc tả BOLT | [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 8209 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **NomicFoundation/hardhat**, **wevm/viem**, **vyperlang/vyper**, **MetaMask/metamask-extension**: GitHub trả giấy phép NOASSERTION; loại.
- **ethers-io/ethers.js**: commit gần nhất 2026-06-18, quá 60 ngày; loại.
- **wevm/wagmi**: README ở thư mục gốc không có tên README.md (trả 404); chưa đọc; có thể làm sau. **anza-xyz/agave**, **ethereum/solidity**, **ethereum/web3.py**: tìm kiếm GitHub không trả kết quả ở thời điểm kiểm tra.

## Điều chưa biết

- Chưa cài hay chạy phần mềm nào; độ khó là đánh giá biên tập. Nhãn danh mục là nhãn gần nhất trong 9 nhãn có sẵn, chưa khớp hoàn toàn với blockchain.
- Toàn bộ nhóm chỉ là giới thiệu kỹ thuật, không phải lời khuyên đầu tư, kinh doanh hay pháp lý. Pháp lý và thuế tiền mã hóa (kể cả tại Việt Nam) chưa được kiểm tra.
- Scaffold-ETH 2: README phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub (MIT). Bitcoin Core, BTCPay Server, lnd, OpenZeppelin, go-ethereum, Foundry, Cosmos SDK: giấy phép theo README hoặc huy hiệu (Cosmos SDK có mô-đun enterprise theo điều khoản khác).
- Các số liệu và tuyên bố của README (Cosmos SDK 200+ chuỗi và 10k+ TPS; Foundry 'nhanh'; BTCPay 'không phí hay trung gian'; lnd 'tuân thủ đầy đủ BOLT') là của README, bài không kiểm chứng.
- Lệnh cài tải từ mạng và lệnh dựng trong README (Foundry, go-ethereum, Scaffold-ETH 2, OpenZeppelin) không được chép vào bài. Nhận định về sao lưu kênh Lightning và mở cổng RPC là nguyên tắc chung của bài.

