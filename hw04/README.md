# HW04 - Raspberry Weather Station

## Reading

Look in 05-midterm-hw

## Weather Station

Compared to some of the other homework that you've had previously, this one is going to seem very simple. All you need to do is modify the existing sensor reading code to record temperature and humidity readings. Then you need to write a quick script to scan a log file and report min + max values.

### Requirements
- Modify the existing code on the Raspberry Pi so that it records temperature to a log.
- Log that high and low somewhere using `bunyan`.
- Write a Node script that will take a calendar date and a log file as input, returning the temperature high and low for that day.
    - You might need to read "https://nodejs.org/en/knowledge/command-line/how-to-parse-command-line-arguments/" for help on processing command line input.
