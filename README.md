Установка и настройка Grafana + Prometheus + Node Exporter + VictoriaMetrics на Kali Linux (ARM) 
Этот документ описывает процесс установки и настройки Grafana, Prometheus, Node Exporter и VictoriaMetrics в Kali Linux, работающей в виртуальной машине Parallels Desktop на Mac M1 ARM.
1. Установка Prometheus
 1. Загрузка версии Prometheus для ARM:
sudo apt update
wget https://github.com/prometheus/prometheus/releases/download/v2.45.0/prometheus-2.45.0.linux-arm64.tar.gz
