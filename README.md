<img width="340" height="441" alt="home_cisco" src="https://github.com/user-attachments/assets/358dde68-fd34-4066-b381-627d3518a0b7" />
Smart Home IoT - Architecture Comparison
Comparative study of three IoT architectures for smart home automation using Cisco Packet Tracer 9.
Project Overview
This project compares Cloud Server, Local Gateway, and WiFi Direct architectures across five home zones: outdoor security, garage automation, kitchen safety, and living room comfort.
Key Question: Which architecture offers the best balance between speed, reliability, and cost?
Applications
Outdoor (Cloud Server): Motion detection, webcam surveillance, automatic lawn sprinkler, and smart street lighting.
Garage (Gateway): Fire detection with smoke sensor, automatic sprinkler, two motorized windows, garage door, and 90 dB siren.
Kitchen (Gateway): Grease fire detection, fire sprinkler, motorized window and door for evacuation, 85 dB alarm.
Living Room (WiFi Direct): Fire monitoring, smart heating (2000W), motorized window, fire sprinkler via MCU0 coordinator.
Results Summary
Cloud Server: 3.2s latency, unlimited storage, requires Internet (0% autonomy), €800-1400 over 5 years.
Local Gateway: 0.05-0.5s latency, 97% reliability, works without Internet (97.5% autonomy), €200-250 one-time cost.
WiFi Direct: 0.12s latency, 92% reliability, 92% autonomy, only €80 total cost.
Key Findings
Gateway is 64× faster than Cloud for kitchen safety (0.05s vs 3.2s).
Gateway maintains 97.5% functionality without Internet - Cloud drops to 0%.
WiFi Direct is 10-17× cheaper than Cloud over 5 years (€80 vs €800-1400).
Recommendations
Critical Safety: Use Gateway for kitchen/garage (ultra-fast 0.05-0.5s response).
Surveillance: Use Cloud Server for outdoor (unlimited storage, AI analytics).
Budget/Small Spaces: Use WiFi Direct for living room (€80 total, simple setup).
Best Solution: Hybrid approach combining all three saves €1,070-1,670 vs full cloud deployment.
Usage
Open Cisco Packet Tracer 9, load simulation files, and observe automation scenarios across different architectures.
Authors
Chemlali Ibtihal • Abdessadek Fatima-zahra • Elguerrab Wiaam
Supervised by: M. BAKkAS
 | ENSAM - Meknès | 2025-2026
