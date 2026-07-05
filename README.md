# Seoul_transit_accessibility

# 접근성을 고려한 서울시 대중교통 취약지역 도출

경사도를 반영한 실제 보행 네트워크(Tobler 함수 + Dijkstra) 위에서 2SFCA로 실질 접근성을 측정하고,
사분면 분석으로 **"수요는 많은데 접근성이 낮은" 핵심 취약지역 2,211개 격자를 도출**한 공간 분석 프로젝트.

## 파일 구성

| 파일 |
| --- |
01_접근성_분석_최종_4_5.ipynb
02_100m 격자별 인구.ipynb
03_hex_grid_final.zip
04_relative_quadrant_7090_visual_joined.gkpg
05_priority_vulnerable_top10_polygon_joined.gpkg

## 데이터

서울시 빅데이터캠퍼스 · 구글 Elevation API · SGIS
> ⚠️ 원본 데이터는 재배포 제한으로 레포에 포함하지 않았습니다. 위 출처에서 동일 데이터를 신청·수집할 수 있습니다.

## 기술 스택

`Python` `NetworkX` `GeoPandas` `Folium` `scikit-learn` `QGIS`
