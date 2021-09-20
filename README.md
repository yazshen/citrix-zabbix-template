# Zabbix Template for Citrix Network Product

## Author
Name: Yazhong(Robbie) Shen

Contact: yazhong.shen@citrix.com

## Table of Contents
### 1. Citrix SD-WAN
https://github.com/yazshen/citrix-zabbix-template/blob/main/citrix_sdwan_template_v0.1.yaml

#### 1.1 Requirement
Zabbix 5.4.x

#### 1.2 Support
System:
+ CPU Usage
+ Memory Usage
+ HA Status

Virtual Path:
+ Status
+ Send-Latency
+ Send-Jitter
+ Receive-Latency
+ Receive-Jitter

### 2. Citrix ADC
https://github.com/yazshen/citrix-zabbix-template/blob/main/citrix_adc_temlate_v0.1.yaml

#### 2.1 Requirement
Zabbix 5.4.x

#### 2.2 Support
System Usage
+ Mgmt CPU Usage
+ Packet CPU Usage
+ Memory Usage
+ Disk Partition Usage
+ SSL Card Usage

Hardware Monitor
+ CPU Temperature
+ CPU Fan Speed
+ System Fan Speed
+ Disk Error
+ PowerSupply Status

High Availability
+ Status
+ State
+ PeerState

Performance
+ TCP CPS
+ HTTP RPS
+ SSL TPS
+ Concurrent TCP Connections(Server)
+ Concurrent TCP Connections(Client)
+ Concurrent SSL Sessions

SSL
+ SSL Card
+ SSL Card Status
+ SSL Engine Status

Interface
+ Admin Status
+ Oper Status


