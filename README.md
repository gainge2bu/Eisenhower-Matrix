# Eisenhower Matrix

> 단일 페이지 아이젠하워 매트릭스 — 할 일을 적고 중요·긴급을 체크하면 4분면에 자동 맵핑

🌐 **라이브**: https://gainge2bu.github.io/Eisenhower-Matrix/

## 기능 (v0.1 MVP)

### Task List
- 20개 기본 행 (필요 시 자동 확장)
- 각 항목에 **긴급 / 중요** 체크박스 + 데드라인
- 호버 시 삭제 가능, Enter로 다음 행 이동
- localStorage 자동 저장

### 4분면 자동 맵핑
| 중요 | 긴급 | 분류 |
|---|---|---|
| ✓ | ✓ | **Q1 · Do First** (즉시 실행) |
| ✓ | ✗ | **Q2 · Schedule** (계획 수립) |
| ✗ | ✓ | **Q3 · Delegate** (위임) |
| ✗ | ✗ | **Q4 · Don't Do** (삭제/보류) |

데드라인 임박 순 자동 정렬, 기한 초과는 빨간 배지, 오늘 마감은 노란 배지.

### 부가
- 🌙 / ☀ 라이트·다크 모드 토글
- 모든 데이터는 브라우저 localStorage에만 저장 (서버 없음)

## 기술 스택
- HTML/CSS/JS 단일 파일
- Pretendard 폰트
- GitHub Pages 호스팅

## 제작
- **임종은 컨설턴트(Tim)** · 가인지컨설팅그룹
- Business Is Love
