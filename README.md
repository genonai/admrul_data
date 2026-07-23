# admrul_data

**행정규칙류** 미러 저장소 — 행정규칙(고시·훈령·예규)·학칙(school)·공단정관(pi)·공공기관(public).

- **자동 생성**입니다. 손으로 편집하지 마세요. `temporal_law` 파이프라인(`pipeline/gitexport.py`)이 수집할 때마다 이 레포에 커밋합니다.
- 각 문서의 조문·인용·별표/첨부를 **인라인 링크가 박힌 Markdown** 으로 미러링합니다.
- 원본 데이터·메타데이터는 Postgres `lawdb` 의 `admrul_*` 테이블에 함께 적재됩니다.
- 행정규칙류 수집은 **별도 PC** 에서 돕니다(`ADMRUL_ENABLED=true` 인 머신). 법령 전용 PC 에서는 이 레포에 아무것도 쌓이지 않습니다.

> 생성 주체: [temporal_law](https://github.com/sehunpark-genon/temporal_law) · `ADMRUL_ENABLED`
