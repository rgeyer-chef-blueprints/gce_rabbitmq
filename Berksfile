site :opscode

cookbook "rabbitmq", git: "git://github.com/rgeyer-rs-cookbooks/rabbitmq.git", branch: "ac8580ec43bf8ff287354187073921b2e92c6097"

cookbook "block_device", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/block_device"
cookbook "logging", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/logging"
cookbook "logging_rsyslog", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/logging_rsyslog"
cookbook "logging_syslog_ng", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/logging_syslog_ng"
cookbook "rightscale", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/rightscale"
cookbook "sys", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/sys"
cookbook "sys_dns", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/sys_dns"
cookbook "sys_firewall", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/sys_firewall"
cookbook "sys_ntp", git: "git://github.com/rightscale/rightscale_cookbooks.git", branch: "fb5162b30eaaaed02d61a411cad9e7aa45c4e7ca", rel: "cookbooks/sys_ntp"

group :vagrant_only do
  cookbook "rs_vagrant_shim", git: "https://github.com/rgeyer-rs-cookbooks/rs_vagrant_shim.git", branch: "f34435d604a45a8c1eb0b6a0c2a4a397012a45b4"
end