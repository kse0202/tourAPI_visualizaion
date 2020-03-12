# tourAPI_visualizaion
Data collecting with API and visualization using matplot, folium 

## Language
Python 3.7.4  

## ScreenShot

#### matplot을 이용한 시각화
![ex_screenshot](./img/month_readcounts.png)  
봄(3,4월)과 가을(9, 10월)에 행사 수가 많다.    
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
GeoJson을 이용하여 서울의 구를 지도에 표시했다.  
SouthKorea github에서 받은 skorea-municipalities-2018-geo.json을 이용했다.  
서울의 구만 추려 만든 GeoJson 파일을 만들었다.  

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

