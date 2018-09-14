<div align="center">
    <img src="logo.bpm"/>
</div>

# TSGauge

Extension for Chart.js that allows you to draw "Speedometer" graphs.

### Compatibility
Requires [Chart.js](https://github.com/chartjs/Chart.js/releases) **2.7.0** or later.

### Install
```html
<script src="Gauge.js"></script>
```

### Config example:
```js
{
	type: "tsgauge",
	data: {
		datasets: [{
			backgroundColor: ["#0fdc63", "#fd9704", "#ff7143"],
			borderWidth: 0,
			gaugeData: {
				value: 7584,
				valueColor: "#ff7143"
			},
			gaugeLimits: [1000, 3000, 5000, 8000]
		}]
	},
	options: {
		events: [],
		layout: {
			padding: {
				top: 10
			}
		},
		legend: {
			display: false
		},
		scales: {},
		tooltips: {
			enabled: false
		}
	}
}
```
