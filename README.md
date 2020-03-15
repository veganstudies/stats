# stats

동물 관련 각종 통계 모음

## 사료-식량 에너지 효율

먹은 사료 대 생산된 에너지의 비율. 돼지, 닭, 달걀, 우유, 소의 칼로리 및 단백질 기준 에너지 효율. 미국 2000년-2010년 기준 추정치.

* 파일: [feed-food-efficiency.csv](feed-food-efficiency.csv)
* 변수: `fcr_live`, `fcr_edible`, `fcr_consumed`는 `content / intake` 단위, 나머지는 `intake / content`
* 출처: [Energy and protein feed-to-food conversion efficiencies in the US and potential food security gains from dietary changes](https://iopscience.iop.org/article/10.1088/1748-9326/11/10/105002)에 인용된 USDA 수치
* 수집 방법: 논문의 수치를 수기로 입력

## 도축 통계

2004년 이후 전국의 소, 돼지, 말, 양, 닭, 오리를 도축하는 도축장(도계장)의 도축검사실적, 도축실적 보고내용을 집계. 생체검사두수에서 도살금지두수를 제외한 도살두수.

* 파일: [slaughter-kr.csv](slaughter-kr.csv)
* 출처: [농림축산검역본부 도축실적](http://www.qia.go.kr/livestock/clean/listTcsjWebAction.do?clear=1)
* 수집 방법: 엑셀 파일을 열어서 충종별 통계량을 수기로 변환
