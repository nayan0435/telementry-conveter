Telemetry Data Format Converter
This Python project converts two different telemetry message formats into a single unified JSON format.

Problem
Two telemetry data files contain the same information but use different structures and timestamp formats.

data-1.json uses a path-based location format and timestamp in milliseconds.
data-2.json uses separate location fields and ISO timestamp format.
The goal is to convert both formats into a unified structure.

Files Included
data-1.json → First telemetry format
data-2.json → Second telemetry format
data-result.json → Expected unified output format
main.py → Python program that performs the conversion
Features
Converts location string into structured fields
Converts ISO timestamp to milliseconds since epoch
Normalizes device and telemetry data
Validates results using automated comparison
How to Run
Run the program using Python:
