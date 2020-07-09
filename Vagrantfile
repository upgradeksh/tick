box = "generic/ubuntu1804"

Vagrant.configure("2") do |config|

  config.vm.define "web" do |web|
    web.vm.box = box
    web.vm.hostname = "web"

    web.vm.provider "virtualbox" do |v|
      v.name = "web"
      v.memory = 1024
      v.cpus = 1
    end
  end

  config.vm.define "grafana" do |grafana|
    grafana.vm.box = box
    grafana.vm.hostname = "grafana"

    grafana.vm.provider "virtualbox" do |v|
      v.name = "grafana"
      v.memory = 1024
      v.cpus = 1
    end
  end

  config.vm.define "influxdb01" do |influxdb01|
    influxdb01.vm.box = box
    influxdb01.vm.hostname = "influxdb01"

    influxdb01.vm.provider "virtualbox" do |v|
      v.name = "influxdb01"
      v.memory = 2048
      v.cpus = 2
    end
  end

  config.vm.define "influxdb02" do |influxdb02|
    influxdb02.vm.box = box
    influxdb02.vm.hostname = "influxdb02"

    influxdb02.vm.provider "virtualbox" do |v|
      v.name = "influxdb02"
      v.memory = 2048
      v.cpus = 2
    end
  end
end
