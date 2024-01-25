# Configurable Interval Timer
The code and the documentation was created with the help of chat gpt.

Run the timer:
https://tblsoft.github.io/interval-timer/interval-timer.html

## Description

This project is a simple, configurable interval timer web page. It displays a timer with configurable intervals and changes the background color and text for each interval. The timer settings, including interval durations, text labels, and colors, can be customized using URL query parameters.

## Features

- Two intervals with configurable durations.
- Customizable text labels for each interval (e.g., "Training", "Pause").
- Customizable background colors for each interval.
- Display of total elapsed time since the timer started.

## Setup

To set up this project locally:

1. Clone the repository to your local machine.
```sh
   git clone git@github.com:tblsoft/interval-timer.git
```

2. Open the index.html file in a web browser to view the timer.

## Usage

The timer can be configured using URL query parameters. Below are the available parameters:

- firstInterval: Duration of the first interval in seconds (default: 60).
- secondInterval: Duration of the second interval in seconds (default: 120).
- firstText: Text label for the first interval (default: "Pause").
- secondText: Text label for the second interval (default: "Training").
- firstColor: Background color for the first interval (default: "blue").
- secondColor: Background color for the second interval (default: "green").

```css
https://tblsoft.github.io/interval-timer/interval-timer.html?firstInterval=30&secondInterval=45&firstText=Rest&secondText=Work&firstColor=red&secondColor=yellow

```

This will set the first interval to 30 seconds with "Rest" text and red background, and the second interval to 45 seconds with "Work" text and yellow background.
Contributing

Contributions to this project are welcome. Please feel free to submit issues and pull requests.


### License

[MIT License](https://opensource.org/licenses/MIT)


