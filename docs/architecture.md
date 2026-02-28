# System Architecture

This project simulates a cloud-based monitoring and anomaly detection workflow commonly used in Site Reliability Engineering (SRE) environments.

## Pipeline Flow
Application Logs → Python Processing → Validation → Storage → Visualization → Alerts

### Steps
1. Operational logs are collected from multiple services
2. Python scripts validate schema and clean records
3. Cleaned events are stored for analysis
4. Events are indexed for monitoring dashboards
5. Kibana dashboards visualize abnormal behavior
6. Alerts are triggered when thresholds are exceeded

## Example anomalies detected
- Latency spikes
- Error bursts
- Repeated failed requests
- Service downtime patterns

## Future Enhancements
- Real-time streaming ingestion
- Machine learning based anomaly detection
- CloudWatch alert integration
