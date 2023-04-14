# RHEL_Server_Resource_Monitoring.py
This code is a Python program that monitors various system resources (CPU usage, memory usage, and disk usage) on a RHEL 8.5 server and writes the results to a log file. The program uses the psutil module to gather system resource information and writes the information to a log file specified by the LOG_FILE variable. If the log file size exceeds 500 MB, the program starts overwriting it.

In addition to the Python code, there are instructions to convert this code into a systemd service, which will enable it to run automatically on startup and continuously monitor system resources until stopped or the server is shut down..
