# Autodidact — joonan-lab 학습 시각화

연구실 구성원이 논문·방법론을 공부하면서 만든 **자습용 시각화 페이지 모음**이다. 각 주제 폴더가 독립된 정적 HTML 페이지이고, GitHub Pages로 공개된다.

- 사이트: https://joonan-lab.github.io/autodidact/
- 운영 규칙(에이전트 포함): [AGENTS.md](AGENTS.md). 공개 사이트이므로 미출판 연구실 논문은 올리지 않고, 변할 숫자(페이지 수·모델 수)를 본문에 박지 않으며, 자폐를 질병처럼 다루는 표현을 피한다.

## 구조

```
index.html            홈. 모든 주제 페이지로 가는 목록
<topic>/index.html    주제별 페이지 (예: gwas-fine-mapping, organoids, rna-seq-deg)
<topic>/<sub>/        같은 주제 아래 세부 페이지
<topic>/assets/       그 페이지 전용 이미지
assets/               공용 이미지(로고 등)
```

주제 페이지는 자유 형식이되, 홈으로 돌아가는 링크와 저자 메타데이터를 둔다.

## 새 페이지 추가

1. `<topic>/index.html`을 만든다. 기존 페이지 하나를 복사해 시작하면 된다.
2. `index.html` 홈 목록에 링크를 추가한다.
3. [AGENTS.md](AGENTS.md)의 세 규칙(미출판 논문 금지, 변하는 숫자 금지, 표현 규칙)을 확인한다.
4. `main`에 push하면 Pages가 갱신된다.

빌드 도구는 없다. 브라우저에서 파일을 직접 열어 확인한다.
