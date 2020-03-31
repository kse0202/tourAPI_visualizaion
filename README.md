# tourAPI_visualizaion
Data collecting with API and visualization using `matplot`, `folium`

* 한국관광공사에서 제공하는 tourAPI를 이용하여 2019년의 축제 및 행사들의 데이터를 수집하고, 시각화했습니다. 
* `matplot` 라이브러리를 이용하여 그래프를 그리고 데이터의 특성을 파악했습니다. 
* SouthKorea 깃허브에서 제공하는 `GeoJson`과 `folium.Choropleth` , `MarkerCluster()` , `folium.marker` 를 이용하여 다양한 시각화를 했습니다.
* 서울의 시각화를 위해 편집한 데이터를 함께 올립니다. `geo_data/skorea-municipalities-2018-geo-seoul2.json`

## Language
Python 3.7.4  

## Summary

#### matplot을 이용한 시각화
![ex_screenshot](./img/month_readcounts.png)  
봄(3,4월)과 가을(9, 10월)에 행사 수가 많은 것을 알 수 있다.     
여름(6, 7월)의 행사에 대한 페이지 뷰의 평균이 높은걸로 보아 여름에 하는 행사에 대한 관심이 많다는 것을 알 수 있다.     


![ex_screenshot](./img/area_month.png)  
서울, 경기도, 강원도 순으로 행사 수가 많다.    
각 지역별 바의 색 분포를 보았을 때, 분포가 비슷한 것을 보아 지역에 따른 월별 행사 분포는 대체로 비슷한 것을 알 수 있다.  

#### folium을 이용한 visualization
![ex_screenshot](./img/provinces_festival_counts.JPG)  
folium의 Choropleth 이용한 지역별 행사 수 시각화  
마우스 커서를 pin에 올리면 지역명과, 그 지역의 행사 수를 보여준다.  

![ex_screenshot](./img/markerCluster.jpg)  
folium의 markerCluster 이용한 지역별 행사 수 clustering 시각화   

![ex_screenshot](./img/seoul_geojson.jpg)   
GeoJson을 이용한 서울의 구 지도 시각화

![ex_screenshot](./img/seoul_chor.jpg)  
folium의 Choropleth 이용한 서울의 구별 행사 수 시각화  

![ex_screenshot](./img/seoul_chor_marker.jpg)  
folium의 Choropleth, markerCluster 이용한 서울의 구별 행사 수 시각화   
서울의 중심부(종로구)와 한강 주변에 행사가 밀집되어 있는 것을 알 수 있다.   

![ex_screenshot](./img/seoul_marker.jpg)  
좌표를 이용해 서울 내 행사가 일어난 곳에 marker를 삽입했다.  

![ex_screenshot](./img/seoul_marker_color.jpg)  
구별 marker의 색을 바꿔보았다.   

## Reference & License
 
[tourAPI from Korea Tourism Organization](http://api.visitkorea.or.kr/)

[GeoJson from SouthKorea github](https://github.com/southkorea/southkorea-maps)

[Folium Documentation](https://python-visualization.github.io/folium/index.html) 

