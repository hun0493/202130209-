# StudySpot (스터디스팟)
모바일 최신기술 **중간고사 제출 — 202130209**

> 주변 독서실·스터디카페·카페의 **좌석·요금·혼잡도**를 한눈에 비교하는 모바일 퍼스트 웹앱

- **Notion 제출본:** https://www.notion.so/202130209-26f9a663a1f880458575e4f0a92f72d2?source=copy_link

---

## ✨ 기능 & 스택 (한 번에)
| 구분 | 내용 |
|---|---|
| **주요 기능** | 스마트 검색 & 고급 필터(카테고리/가격/시설/혼잡도/반경 1·3·5km)<br>지도 뷰(핀·바텀시트·줌·현재 위치 대체 UX)<br>상세 다이얼로그(16:9 갤러리, 가격, 혼잡도 차트, 공유/길찾기)<br>즐겨찾기(localStorage 지속)<br>(로드맵) Owner 대시보드: 혼잡도 토글, OCR 가격표 업로드 |
| **스택** | **React 18 · TypeScript 5 · Vite 5 · Tailwind CSS v4**<br>UI/도구: **shadcn/ui · Lucide · Recharts · Motion · Embla Carousel** |

---

## 🚀 실행
```bash
npm install
npm run dev    # http://localhost:5173
📊 데이터
Mock Dataset v2.1 (총 116개) = CSV 12 + TS Mock 104 (경로: data/csvData.ts, data/mockData.ts)

현 버전 혼잡도는 모의 산출(사용자 신고 + 시간대 평균)이며 실제 사업자/지점 실데이터 미사용

🗺 참고 문서(지도)
Kakao Map Developers — https://apis.map.kakao.com/

Naver Maps — https://api.ncloud-docs.com/docs/ai-naver-maps

♿ 접근성 & 성능 목표
WCAG AA, 키보드 네비/스크린리더, 대비 4.5:1+

LCP ≤ 2.0s · View 전환 ≤ 220ms · Lighthouse Perf 95+

🧾 Attributions
이미지: Picsum · Unsplash / 아이콘·컴포넌트: Lucide · shadcn/ui · Radix UI
차트·애니메이션: Recharts · Motion · Embla / 프레임워크: React · TypeScript · Tailwind · Vite

📄 라이선스
MIT

