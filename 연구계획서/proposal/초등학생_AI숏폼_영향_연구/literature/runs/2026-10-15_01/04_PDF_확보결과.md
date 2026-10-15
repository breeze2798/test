# 원문 PDF 확보·검증 결과

2026-10-15 기준 핵심논문 **선정 5편, PDF 검증 저장 5편, 미확보 0편**. 다운로드 대상이 실제 `%PDF-` 파일인지 확인했고, `pypdf`로 파일을 열어 페이지 수와 첫 페이지 제목·저자를 대조했다. 검수용 요약 PDF나 오류 HTML은 저장하지 않았다.

| ID | 버전·출처 | 페이지 | 바이트 | SHA-256 | 검증 |
|---|---|---:|---:|---|---|
| L001 | 출판본, [PMC 공개 데이터](https://pmc-oa-opendata.s3.amazonaws.com/PMC11214215.1/PMC11214215.1.pdf) | 9 | 1,128,106 | `B7E4C5C2FE88528AADBD987045E8BF62EB3B38430A5C13D200D6240A01BE6004` | [원문 PDF](../../pdf/L001_2024_Jiang_short_video_sleep.pdf) |
| L002 | 출판본, [PMC 공개 데이터](https://pmc-oa-opendata.s3.amazonaws.com/PMC12833232.1/PMC12833232.1.pdf) | 13 | 184,025 | `FDEC3EB429D6B0D5163D8DBC7C4E191ED6938503F45FDABB8099BCEBF626B874` | [원문 PDF](../../pdf/L002_2026_Chen_screen_behavior_sleep.pdf) |
| L003 | 출판본, [PMC 공개 데이터](https://pmc-oa-opendata.s3.amazonaws.com/PMC3040363.1/PMC3040363.1.pdf) | 7 | 546,185 | `08C124B9BFC9BCA96CFF71D8E225BC4C96D828157BE0C96567BBC434A59440E0` | [원문 PDF](../../pdf/L003_2011_Rhie_Korean_PDSS.pdf) |
| L004 | 출판본, [PMC 공개 데이터](https://pmc-oa-opendata.s3.amazonaws.com/PMC8482627.1/PMC8482627.1.pdf) | 14 | 872,374 | `7E36976F83BCCF16BA42D3B0F550A97C2666F10852EC49042640E21F10798728` | [원문 PDF](../../pdf/L004_2021_Lund_media_sleep_review.pdf) |
| L005 | 출판본, [학술지 원문](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2024.1290935/pdf) | 7 | 411,611 | `67076AB5ED9FAEB70FC3DC08AE5F0114608DC1A262582BD6E83AEB6D9E91FE3B` | [원문 PDF](../../pdf/L005_2024_Poulain_bedtime_media_sleep.pdf) |

첫 시도였던 Springer/BMC 직접 PDF 경로는 이 실행 환경에서 HTML 접근 안내를 반환해 채택하지 않았다. 공개 라이선스가 붙은 PMC 데이터 원문으로 L001·L004를 확보했고, L002·L003도 같은 공식 공개 데이터에서 받았다. 후보였던 So 등(2021)은 이번 선정 5편에 포함하지 않았다. 해당 PMC 저자 원고의 자동 배포 데이터에는 PDF가 없어 [원문 페이지](https://pmc.ncbi.nlm.nih.gov/articles/PMC8340849/)를 검색 기록에 남겼다.
