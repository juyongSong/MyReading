# MyReading Assets Archive 📚

노션(Notion) 블로그에 사용하는 이미지와 에셋을 저장하는 아카이브 저장소입니다.

A repository for archiving images and assets used in Notion blog.

---

## 📂 폴더 구조 (Folder Structure)

```
MyReading/
├── 2024/
│   ├── images/       # 2024년 이미지 파일
│   └── assets/       # 2024년 기타 에셋 (아이콘, 파일 등)
├── 2025/
│   ├── images/       # 2025년 이미지 파일
│   └── assets/       # 2025년 기타 에셋 (아이콘, 파일 등)
├── 2026/
│   ├── images/       # 2026년 이미지 파일
│   └── assets/       # 2026년 기타 에셋 (아이콘, 파일 등)
└── README.md
```

---

## 📋 사용 가이드 (Usage Guide)

### 1️⃣ 파일 업로드
해당 연도의 `images` 또는 `assets` 폴더에 파일을 업로드합니다.

Upload files to the appropriate `images` or `assets` folder for the corresponding year.

### 2️⃣ 파일 명명 규칙 (File Naming Convention)
- **의미 있는 이름 사용**: `book-cover-atomic-habits.jpg`
- **소문자 사용**: `my-image.png` (권장)
- **공백 대신 하이픈 사용**: `book-review-2024.png`
- **날짜 포함 (선택사항)**: `20240315-meeting-notes.jpg`

Examples:
- ✅ `notion-icon-reading.png`
- ✅ `2024-01-15-book-cover.jpg`
- ❌ `Image 1.png`
- ❌ `스크린샷 2024.png`

### 3️⃣ 노션에서 사용하기 (Using in Notion)

1. GitHub에서 파일을 열고 `Raw` 버튼 클릭
2. URL 복사
3. 노션에서 이미지 블록 추가 → "링크" 선택 → URL 붙여넣기

Or use GitHub raw URL format:
```
https://raw.githubusercontent.com/juyongSong/MyReading/main/[YEAR]/images/[FILENAME]
```

예시 (Example):
```
https://raw.githubusercontent.com/juyongSong/MyReading/main/2024/images/book-cover.jpg
```

---

## 🎯 Best Practices

### 이미지 최적화 (Image Optimization)
- 웹에 적합한 크기로 리사이즈 (권장: 1200px 이하)
- 적절한 포맷 사용:
  - **사진**: `.jpg` or `.webp`
  - **그래픽/아이콘**: `.png` or `.svg`
  - **애니메이션**: `.gif` or `.webp`

### 파일 관리 (File Management)
- 연도별로 폴더 분리하여 체계적 관리
- `images/`: 블로그 포스트에 사용되는 모든 이미지
- `assets/`: 아이콘, PDF, 기타 파일 등

### 새 연도 추가하기 (Adding New Year)
```bash
mkdir -p [YEAR]/images [YEAR]/assets
touch [YEAR]/images/.gitkeep [YEAR]/assets/.gitkeep
```

---

## 📝 License

This repository is for personal use.

---

## 🔗 Links

- [Notion](https://www.notion.so)
- [Repository](https://github.com/juyongSong/MyReading)

---

**Made with ❤️ for organized asset management**