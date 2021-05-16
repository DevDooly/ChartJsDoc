# Chart.js

[![slack](https://img.shields.io/badge/slack-chartjs-blue.svg?style=flat-square&maxAge=3600)](https://chartjs-slack.herokuapp.com/)

## 설치

[npm](https://npmjs.com/package/chart.js), [GitHub releases](https://github.com/chartjs/Chart.js/releases/latest) 또는 [Chart.js CDN](https://www.jsdelivr.com/package/npm/chart.js) 에서 최신 버전의 Chart.js 를 가져와 사용할 수 있습니다. 자세한 설치 방법은 [설치 페이지](./getting-started/installation.md)에서 찾을 수 있습니다.

## 차트 만들기

Chart.js를 만드는 것은 간단합니다. 필요한 것은 차트를 렌더링하기 위한 `<canvas>` 노드와 함께 페이지에 포함 된 스크립트뿐입니다.

아래 예시에서는 단일 데이터 세트에 대한 막대 차트를 만들고 페이지에서 렌더링합니다. [사용 설명서](./getting-started/usage.md)에서 Chart.js를 사용하는 모든 방법을 볼 수 있습니다.

```html
<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>
```

## 기여하기

프로젝트에 이슈 또는 풀 리퀘스트를 제출하기 전에 먼저 [기여 가이드 라인](./developers/contributing.md) 을 살펴 보시기 바랍니다 .

Chart.js 사용에 대한 지원을 받으려면 [`chartjs` Stack Overflow 태그](https://stackoverflow.com/questions/tagged/chartjs) 를 사용하여 질문을 게시하십시오 .

## 라이센스

Chart.js는 [MIT 라이센스](https://opensource.org/licenses/MIT)를 따릅니다.
