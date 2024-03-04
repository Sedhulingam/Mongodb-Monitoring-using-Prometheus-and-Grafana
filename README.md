# Mongodb-Monitoring-using-Prometheus-and-Grafana
Let’s get started with monitoring MongoDB using Prometheus and the MongoDB Exporter.

## Prerequists
Before we get started, make sure you have the following prerequisites:

  1. A MongoDB instance running on your system or a remote server.
  2. Prometheus is installed on your system or a remote server.<No need>
  3. Grafana installed on your system or a remote server (optional).

# How to install Mongodb in local machine
Steps:
1. Download Mongodb community Edition from here : https://www.mongodb.com/try/download/community
2. Install it in your program files of localdisk C
3. Install MongoDB compass gui or robo3t for CRUD on mongodb from gui
4. while installing the mongodb server you should also install mongoshell which helps to query the mongodb server the link is this : https://www.mongodb.com/try/download/shell
5. add the bin folder of this mongoshell to system environment then the installation of mongo db on local machine is done


# How to install grafana in Local machine
Steps
1. Go this official grafana website for download https://grafana.com/grafana/download
2. then in the conf folder(C:\Program Files\GrafanaLabs\grafana\conf) of the grafana create custom.ini which is the copy of sample.ini and change the http port = 8080
3. Then add the bin file of the grafana to the system environment
4. run the grafana-server.exe to host it in localhost:8080 for the grafana GUI


# You need to download the mongodb exporter
Steps:
1. Go to this github link and clone it in a particular directory say desktop "git clone https://github.com/JamesOsgood/mongodb-grafana.git"
2. After that go to that folder mongodb-grafana in cmd and type npm install
3. after that cut that folder and paste that in grafana plugin folder which is in program files
   


# How to install prometheus in windows (ignore this)
Steps:
1. Go to this website for download prometheus in windows https://prometheus.io/download/
2. Extract in local Drive under program files
3. Run this command in cmd " prometheus.exe --config.file prometheus.yml --web.listen-address ":9090" --storage.tsdb.path "data" " under   C:\Program Files\prometheus-     2.50.1.windows-amd64
4. After successful installation run the localhost:9090 to see the prometheus ui
5. Check this website for reference http://www.liferaysavvy.com/2021/07/prometheus-installation-on-windows.html
