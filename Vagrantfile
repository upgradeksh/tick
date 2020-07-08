Vagrant.configure("2") do |config|

  config.vm.define "web" do |web|
    config.vm.box = "ubuntu/bionic64"
    config.vm.hostname = "web"
  end

  config.vm.define "grafana" do |grafana|
    config.vm.box = "ubuntu/bionic64"
    config.vm.hostname = "grafana"
  end

  config.vm.define "influxdb01" do |db|
    config.vm.box = "ubuntu/bionic64"
    config.vm.hostname = "influxdb01"
  end

  config.vm.define "inflxudb02" do |inflxudb02|
    config.vm.box = "ubuntu/bionic64"
    config.vm.hostname = "inflxudb02"
  end
end
