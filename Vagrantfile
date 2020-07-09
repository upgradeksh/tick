Vagrant.configure("2") do |config|

  config.vm.define "web" do |web|
    web.vm.box = "ubuntu/bionic64"
    web.vm.hostname = "web"

    config.vm.provider "virtualbox" do |v|
      v.name = "web"
      v.memory = 1024
      v.cpu = 1
    end
  end

  config.vm.define "grafana" do |grafana|
    grafana.vm.box = "ubuntu/bionic64"
    grafana.vm.hostname = "grafana"

    config.vm.provider "virtualbox" do |v|
      v.name = "grafana"
      v.memory = 1024
      v.cpu = 1
    end
  end

  config.vm.define "influxdb01" do |influxdb01|
    influxdb01.vm.box = "ubuntu/bionic64"
    influxdb01.vm.hostname = "influxdb01"

    config.vm.provider "virtualbox" do |v|
      v.name = "influxdb01"
      v.memory = 2048
      v.cpu = 2
    end
  end

  config.vm.define "inflxudb02" do |inflxudb02|
    influxdb02.vm.box = "ubuntu/bionic64"
    influxdb02.vm.hostname = "inflxudb02"

    config.vm.provider "virtualbox" do |v|
      v.name = "influxdb02"
      v.memory = 2048
      v.cpu = 2
    end
  end

end
