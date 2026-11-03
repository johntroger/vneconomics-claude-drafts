# Lộ trình 75 — Ứng dụng di động

Từ quản lý trạng thái Flutter, giao diện và kiểu dáng React Native, danh sách và hoạt ảnh đến chia sẻ giao diện bằng Kotlin và ứng dụng Android mẫu; chú ý tương thích với kiến trúc mới của React Native, phiên bản Expo, tình trạng Beta và các tuyên bố hiệu năng của tác giả.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Riverpod: khung bộ nhớ đệm phản ứng và liên kết dữ liệu cho Dart và Flutter, xử lý trạng thái tải và lỗi mặc định, tách logic khỏi giao diện, dễ kiểm thử** (key 562, độ khó: Khó) — Quản lý trạng thái Flutter (khó).  
   Repo: [rrousselGit/riverpod](https://github.com/rrousselGit/riverpod) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
2. **Bloc: thư viện quản lý trạng thái dễ đoán cho Dart và Flutter theo mẫu BLoC, tách phần trình bày khỏi logic nghiệp vụ; kho có nhiều gói (bloc, flutter_bloc, hydrated_bloc, bloc_test...)** (key 563, độ khó: Khó) — Quản lý trạng thái Flutter theo mẫu BLoC (khó).  
   Repo: [felangel/bloc](https://github.com/felangel/bloc) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
3. **NativeWind: thư viện kiểu dáng đưa Tailwind CSS vào React Native, tính kiểu lúc build và dùng runtime nhỏ, không phải thư viện thành phần** (key 565, độ khó: Trung bình) — Tailwind cho React Native (trung bình).  
   Repo: [nativewind/nativewind](https://github.com/nativewind/nativewind) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
4. **FlashList: danh sách nhanh cho React Native thay FlatList, tái chế view để không còn ô trắng; v2 chỉ chạy kiến trúc mới của React Native và không cần ước lượng kích thước** (key 569, độ khó: Trung bình) — Danh sách nhanh; v2 chỉ kiến trúc mới (trung bình).  
   Repo: [Shopify/flash-list](https://github.com/Shopify/flash-list) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
5. **React Native Reanimated và Worklets: thư viện hoạt ảnh mượt và tương tác cho React Native, cùng thư viện chạy JavaScript đa luồng; bản 4 chỉ hỗ trợ kiến trúc mới** (key 564, độ khó: Khó) — Hoạt ảnh mượt; bản 4 chỉ kiến trúc mới (khó).  
   Repo: [software-mansion/react-native-reanimated](https://github.com/software-mansion/react-native-reanimated) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
6. **Tamagui: bộ thư viện kiểu dáng và giao diện chia sẻ mã giữa React và React Native, có trình biên dịch tối ưu biến thành phần kiểu thành div và CSS nguyên tử trên web hoặc View trên di động** (key 568, độ khó: Rất khó) — Giao diện chung web và di động (rất khó).  
   Repo: [tamagui/tamagui](https://github.com/tamagui/tamagui) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
7. **Compose Multiplatform: khung khai báo của JetBrains để chia sẻ mã giao diện bằng Kotlin giữa iOS, Android, máy tính để bàn và web (beta), xây trên Jetpack Compose** (key 566, độ khó: Rất khó) — Chia sẻ giao diện Kotlin; web còn Beta (rất khó).  
   Repo: [JetBrains/compose-multiplatform](https://github.com/JetBrains/compose-multiplatform) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
8. **Now in Android: ứng dụng Android mẫu của Google viết bằng Kotlin và Jetpack Compose, làm tài liệu tham khảo về kiến trúc, mô-đun hóa, kiểm thử và hiệu năng; README ghi đang là công việc dang dở** (key 567, độ khó: Rất khó) — Ứng dụng Android mẫu của Google (rất khó).  
   Repo: [android/nowinandroid](https://github.com/android/nowinandroid) · Bản nháp: `content-drafts/2026-11-03-ung-dung-di-dong/content.json`
