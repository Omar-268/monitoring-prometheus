# Container Monitoring Stack (Extended Version)

This project is a container-based monitoring stack using Prometheus, Grafana, Alertmanager, and Node Exporter.  
I extended the original project by adding NGINX monitoring and cAdvisor

## Key Enhancements 
I have implemented the following features to simulate a professional production environment:

- Nginx Web Server Integration: Added a live Nginx service to act as the monitored application.

- Application-Level Metrics: Integrated nginx-prometheus-exporter to track real-time traffic, including active connections and request rates.

- Container Observability (cAdvisor): Integrated Google’s cAdvisor to provide deep insights into individual container performance. Unlike Node Exporter which monitors the host, cAdvisor monitors the specific resource consumption (CPU, RAM, Network) of each running container.



## Stack Components
- **Prometheus** → Metrics collection
- **Grafana** → Visualization dashboards
- **Alertmanager** → Alert handling
- **Node Exporter** → Host-level metrics
- **NGINX** → Sample service to monitor
- **NGINX Exporter** → Exposes NGINX metrics for Prometheus
- **cAdvisor** → Container-level resource & performance analysis.


