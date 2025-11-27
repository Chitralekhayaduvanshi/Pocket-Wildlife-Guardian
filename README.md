# Pocket-Wildlife-Guardian

Pocket Wildlife Guardian: Solar-Powered Acoustic Edge AI + LoRa for Wildlife Protection

⭐ Objective
Pocket Wildlife Guardian is a low-cost, solar-powered embedded AI device that uses Edge Impulse models running on an ESP32-S3 to detect wildlife activity as well as signs of illegal logging such as chainsaws or gunshots. The device processes audio on-device using MFCC + quantized neural networks and transmits detection events via long-range LoRa communication without requiring any cloud connectivity.

⭐ Innovation
Triple-model pipeline (wildlife, illegal activity, anomaly)
Fully offline inference
Solar-powered continuous operation
Event-driven LoRa alerts
Highly optimized quantized models using Edge Impulse EON

⭐ Impact
Helps conservationists monitor protected areas
Detects illegal activity in real time
Ultra-low cost for large-scale deployments

⭐ Datasets
Xeno-Canto bird dataset (CC BY)
BirdNET mini dataset (MIT)
ESC-50 (MIT)
UrbanSound8K (CC BY)
FSD50K (CC BY 4.0)

⭐ Model Pipeline Overview
MFCC extraction
CNN and CRNN classifiers
Anomaly detection via clustering
All models quantized to int8

⭐ Edge Hardware
ESP32-S3
ICS-43434 I2S microphone
LoRa SX1276 module
LiPo battery + solar charger

⭐ Results
Chainsaw detection accuracy: ~96%
Bird/animal detection accuracy: ~85–92%
Gunshot detection accuracy: ~98%

Full system latency: <150 ms

Battery life: infinite with 1W solar panel
