# FIREWALL-BREACH-DETECTION

Overview

This project uses machine learning to detect firewall breaches based on network logs. It classifies network traffic as normal or suspicious, helping to identify potential security threats.

Features

✅ Preprocesses firewall logs for ML training
✅ Uses Logistic Regression & Random Forest for classification
✅ Detects misclassified firewall events
✅ Provides feature importance analysis
✅ Optimized for high accuracy & low false positives

Dataset

File: log2.csv

Columns: IP Address, Protocol, Port, Timestamp, Status (Allow/Block), etc.

Target Variable: Breach Status (0 = Normal, 1 = Suspicious, 2 = Breach)
