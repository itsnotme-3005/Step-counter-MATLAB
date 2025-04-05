# Step Counter Using Accelerometer Data

This MATLAB project estimates the number of steps taken by analyzing accelerometer data. It uses signal processing techniques to detect peaks in the magnitude of acceleration, corresponding to human steps.

## Features

- Reads 3-axis accelerometer data (X, Y, Z)
- Computes the magnitude of acceleration
- Applies a low-pass filter to reduce noise
- Detects peaks in the filtered signal to count steps
- Plots the filtered signal with detected steps marked
- Outputs total number of steps

## Requirements

- MATLAB (R2018 or later recommended)
- Accelerometer data in `.mat` format (or modify code for `.csv` or other)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/step-counter-matlab.git
   cd step-counter-matlab
   ```

2. Load your accelerometer data into the `accelerometer_data.mat` file. It should contain a variable named `data` with 3 columns: `Ax`, `Ay`, `Az`.

3. Run the script in MATLAB:

   ```matlab
   step_counter.m
   ```

4. View the plot showing step detection and total step count.

## Example

The script will output:

```
Total Steps: 123
```

And display a plot with detected steps marked as red circles on the filtered acceleration magnitude.

## Customization

- Adjust the sampling frequency `fs` according to your data.
- Tune the peak detection parameters (`MinPeakHeight`, `MinPeakDistance`) for better accuracy.

## License

This project is licensed under the MIT License.

## Author

Your Name – [your-website.com](https://your-website.com)  
GitHub: [@your-username](https://github.com/your-username)
