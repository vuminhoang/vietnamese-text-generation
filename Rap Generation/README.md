# Vietnamese Rap Generation Tool
Tôi sẽ cố gắng tạo một tool có thể tạo ra các đoạn rap bằng tiếng việt, với input là "Hãy generate cho tôi một đoạn rap với chủ để {chủ đề nào đó}",

## Ý tưởng
### 1. Dataset
Cần tạo 1 instruction dataset có cấu trúc như kiểu:

---
- **Primer Prompt:**
- Khi có **input**, sử dụng:  
  `Below is an instruction that describes a task, paired with an input that provides further context. Write a response that appropriately completes the request.`
- Khi không có **input**, sử dụng:  
  `Below is an instruction that describes a task. Write a response that appropriately completes the request.`
- **Instruction:** Mô tả yêu cầu chính mà người dùng đặt ra.
- **Input:** Thông tin bổ sung giúp tạo ngữ cảnh hoặc phong cách (có thể để trống nếu không cần thiết).
- **Output:** Kết quả là lời rap được sinh ra dựa trên yêu cầu và ngữ cảnh.
---
