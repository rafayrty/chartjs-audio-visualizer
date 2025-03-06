# Audio Visualizer with Chart.js & Flame Graph

This project is an **audio visualizer** that utilizes **Chart.js** to display real-time frequency data. It includes:

- A **bar chart** representing the frequency spectrum of the audio.
- A **flame graph** that layers past frequency data over time, mimicking fire-like visuals.

Check out the demo here [Vist Demo](https://chartjs-audio-visualizer.netlify.app)

## Features
- Real-time audio visualization using the Web Audio API.
- Interactive **bar chart** to see frequency intensity.
- Dynamic **flame graph** to track audio evolution over time.
- Works with any audio file format supported by HTML5 `<audio>`.

## How to Use
1. **Include Chart.js** in your project:
   ```html
   <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
   ```
2. **Load an audio file** inside the `<audio>` element.
3. **Play the audio**, and the visualization will automatically start.

## Experimenting with Chart.js
You can customize the visualization by modifying the **Chart.js** configurations:
- Change `backgroundColor` and `borderColor` for different visual effects.
- Adjust `fftSize` in the `AudioContext` to fine-tune frequency granularity.
- Modify the `datasets` in `flameChart` to alter the flame graph style.

## Example Modification: Change Bar Color
Modify the bar chart dataset to use **a gradient effect**:
```js
this.barChart.data.datasets[0].backgroundColor = 'rgba(255, 69, 0, 0.5)';
this.barChart.data.datasets[0].borderColor = 'rgba(255, 69, 0, 1)';
```

## Future Enhancements
- Add **user-controlled themes** for different visual styles.
- Implement **3D visualization** using WebGL.
- Explore **more visualization types**, like radial or waveform charts.

## Contributing
Feel free to fork this repository, experiment with new features, and submit pull requests!

Happy coding! 🎶🔥
