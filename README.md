# Stopwatch Script
This is an accurate stopwatch script that uses setInterval(getShowtime(), 1). 

getShowtime() will thus run every millisecond. It checks the current time and compares it to the amount of time elapsed, then displays the difference to the user. It does not rely on setInterval to determine the amount of time passed because that is a highly inaccurate way to keep track of time in javascript.

Also included is a pause button, reset button, and some basic styling.

You can easily change the script to run every second by running setInterval(getShowTime(), 1000) instead of setInterval(getShowTime(), 1). If you choose to run it every second, you should probably comment out the millisecond display options in the getShowTime() function.

Example usage below. Go to the page and click the Timer link. On this website we are using it to run every second, but the script in this repository will run in milliseconds. You can also include the days, just comment the days code in the getShowTime() function.

I try to double the Stopwatch for a timer for fencing. There is a 3 * 3 min Timer for the complete bout and a 1min Timer for passivität. Also a timer for the 1-minute break.
