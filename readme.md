# Highcharts
https://www.highcharts.com/demo
https://www.tutorialspoint.com/angular_highcharts/angular_highcharts_quick_guide.htm https://codesandbox.io/s/pk2z0qvk0q

```
npm install highcharts --save
npm install highcharts-angular --save
```

Add the following entry in highchartsApp.module.ts file

```
import { HighchartsChartComponent } from 'highcharts-angular';
declarations: [
   ...
   HighchartsChartComponent    
],
```
Following is the content of the modified HTML host file app.component.html.

```
<highcharts-chart
   [Highcharts] = "highcharts" 
   [options] = "chartOptions" 
   style = "width: 100%; height: 400px; display: block;">
</highcharts-chart>
```
