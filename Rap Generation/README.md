# Vietnamese Rap Generation Tool
Tôi sẽ cố gắng tạo một tool có thể tạo ra các đoạn rap bằng tiếng việt, với input là "Hãy generate cho tôi một đoạn rap với chủ để {chủ đề nào đó}",

## Ý tưởng
### 1. Dataset
- Cần tạo 1 instruction dataset có cấu trúc như kiểu:
[
    {
        "instruction": "Viết một bài rap về cuộc sống.",
        "input": "Phong cách: mạnh mẽ, quyết đoán.",
        "output": "Cuộc đời là con sóng, ta là thuyền vượt bão."
    },
    {
        "instruction": "Viết một bài rap về tình yêu.",
        "input": "",
        "output": "Tình yêu như nốt nhạc, vang lên trong đêm dài."
    },
    {
        "instruction": "Sáng tác một bài rap truyền cảm hứng.",
        "input": "Cảm xúc: lạc quan, tích cực.",
        "output": "Vượt qua nghịch cảnh, niềm tin chẳng hề phai."
    }
]
