# Lộ trình 69 — Blockchain và tiền mã hóa (kỹ thuật)

Từ nút Bitcoin, Lightning, thanh toán và nút Ethereum đến hợp đồng thông minh, ứng dụng phi tập trung và dựng chuỗi riêng; chỉ là giới thiệu kỹ thuật, không phải lời khuyên đầu tư hay pháp lý; chú ý khóa riêng, mạng thử, kiểm toán hợp đồng và luật địa phương.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Bitcoin Core: phần mềm nút đầy đủ của mạng Bitcoin, tải và xác thực mọi khối và giao dịch, có ví và giao diện tùy chọn; README nhắc dự án bảo mật nhạy cảm, một sai sót có thể làm mất nhiều tiền** (key 515, độ khó: Rất khó) — Nút Bitcoin đầy đủ; nhạy cảm về bảo mật (rất khó).  
   Repo: [bitcoin/bitcoin](https://github.com/bitcoin/bitcoin) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
2. **BTCPay Server: bộ xử lý thanh toán Bitcoin miễn phí mã nguồn mở, tự host, cho người bán nhận Bitcoin trực tiếp không phí hay trung gian (theo README)** (key 521, độ khó: Rất khó) — Nhận Bitcoin tự host; kiểm tra thuế và pháp lý (rất khó).  
   Repo: [btcpayserver/btcpayserver](https://github.com/btcpayserver/btcpayserver) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
3. **lnd: bản cài đặt đầy đủ của nút Lightning Network (mạng thanh toán lớp 2 của Bitcoin), quản lý kênh, định tuyến và thanh toán; README nêu mức tuân thủ đặc tả BOLT** (key 522, độ khó: Rất khó) — Nút Lightning Network (rất khó).  
   Repo: [lightningnetwork/lnd](https://github.com/lightningnetwork/lnd) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
4. **go-ethereum (geth): bản cài đặt tầng thực thi của giao thức Ethereum bằng Go; README nêu yêu cầu phần cứng tối thiểu (4+ nhân, 8GB RAM, SSD 2TB) và giấy phép LGPL cho thư viện, GPL cho tệp thực thi** (key 516, độ khó: Rất khó) — Nút Ethereum; yêu cầu SSD 2TB (rất khó).  
   Repo: [ethereum/go-ethereum](https://github.com/ethereum/go-ethereum) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
5. **Foundry: bộ công cụ viết bằng Rust để phát triển ứng dụng Ethereum gồm Forge (dựng, kiểm thử, fuzz hợp đồng Solidity), Cast, Anvil (nút cục bộ), Chisel (REPL Solidity)** (key 517, độ khó: Khó) — Bộ công cụ hợp đồng Solidity; thử trên mạng cục bộ (khó).  
   Repo: [foundry-rs/foundry](https://github.com/foundry-rs/foundry) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
6. **OpenZeppelin Contracts: thư viện hợp đồng thông minh Solidity đã được cộng đồng thẩm định (ERC20, ERC721, phân quyền); README nói dùng không thay thế kiểm toán bảo mật** (key 518, độ khó: Khó) — Thư viện hợp đồng; không thay thế kiểm toán (khó).  
   Repo: [OpenZeppelin/openzeppelin-contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
7. **Scaffold-ETH 2: bộ khởi tạo mã nguồn mở dựng ứng dụng phi tập trung (dapp) trên Ethereum với NextJS, RainbowKit, Foundry hoặc Hardhat, Wagmi, Viem; README nói sẵn sàng cho AI agent** (key 520, độ khó: Khó) — Dựng dapp thử với ví burner (khó).  
   Repo: [scaffold-eth/scaffold-eth-2](https://github.com/scaffold-eth/scaffold-eth-2) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
8. **Cosmos SDK: bộ công cụ blockchain theo mô-đun bằng Go để dựng chuỗi lớp 1 tùy biến; README nói được dùng bởi hơn 200 chuỗi và có mô-đun doanh nghiệp theo giấy phép khác** (key 519, độ khó: Rất khó) — Dựng blockchain riêng; mô-đun enterprise giấy phép khác (rất khó).  
   Repo: [cosmos/cosmos-sdk](https://github.com/cosmos/cosmos-sdk) · Bản nháp: `content-drafts/2026-11-03-blockchain-tien-ma-hoa/content.json`
