# Adaptive Estimation of the Extreme Value Index for Warehouse Risk Analytics

This project was developed as part of advanced risk modeling initiatives at Uline to identify and quantify rare, high-impact operational events—such as extreme shipment delays, equipment failures, or demand surges—in large-scale warehouse environments. It leverages **Extreme Value Theory (EVT)** and **Probability Weighted Moments (PWM)** to estimate the tail behavior of event distributions, allowing for improved planning and mitigation strategies.

## 🔍 Project Overview

- Implements adaptive estimation of the **Extreme Value Index (EVI)** using PWM methods
- Incorporates **automated threshold selection** using a double-bootstrap approach
- Benchmarked across simulated and historical warehouse operational data
- Designed to enhance decision-making under uncertainty for supply chain risk management

## ⚙️ Technical Features

- Supports both **Hill** and **PWM** estimators
- Includes bias correction to improve EVI accuracy
- Provides visual diagnostics and quantile tail estimation plots
- Built in Python with modular, reusable components

## 🏭 Use Case at Uline

By applying this method to historical warehouse metrics (e.g., delay times, incident costs), we can:

- Quantify the likelihood of **extreme operational disruptions**
- Set more accurate **risk thresholds** for high-cost events
- Improve **resilience planning** for logistics and inventory systems

## 📊 Example Applications

- Estimating risk of warehouse shipment backlogs exceeding historical norms
- Modeling tail behavior of forklift downtime or supply chain interruptions
- Forecasting the probability of rare, high-volume reorder events

## 🧠 Tools & Libraries

- `numpy`, `scipy`, `matplotlib`
- Custom PWM and EVI estimation routines
- Bootstrap simulation framework

## 🔄 Future Extensions

- Integration with live WMS (Warehouse Management Systems) data streams
- Dynamic EVI estimation for real-time anomaly detection
- Coupling with time series forecasting models for compound risk modeling
