<h1>Simple Calendar</h1>

사용자가 원하는 달을 직접 조회할 수 있는 Javascript 달력 앱입니다.

<br />

## 참고 학습

+ date() 객체

  ```javascript
  var d = new Date() // 시간 객체 생성
  document.write(d); // Fri Nov 2 2019 00:27:55 GMT+0900 (대한민국 표준시)
  ```

+ Date 객체 메서드

  <table>
      <thead>
      	<tr>
          	<th>메서드명</th>
          	<th>설명</th>
          </tr>
      </thead>
      <tbody>
      	<tr>
          	<td>getFullYear()</td>
          	<td>연도</td>
          </tr>
          <tr>
          	<td>getMonth()</td>
              <td>월, 0부터 11까지의 값을 반환</td>
          </tr>
          <tr>
          	<td>getDate()</td>
          	<td>일, 1부터 31까지의 값을 반환</td>
          </tr>
          <tr>
          	<td>getDay()</td>
          	<td>요일, 일요일부터 토요일까지의 0에서 6의 값 반환</td>
          </tr>
          <tr>
          	<td>getHours()</td>
          	<td>시</td>
          </tr>
          <tr>
          	<td>getMinutes()</td>
              <td>분</td>
          </tr>
          <tr>
          	<td>getSeconds()</td>
          	<td>초</td>
          </tr>
      </tbody>
  </table>

+ 당월 총 일수 = 32 - new Date(연, 월, 32).getDate()

<br />

## Screenshot

![simple-calculator](https://github.com/usong2/simple-calendar/blob/master/img/calendar.jpg?raw=true)

