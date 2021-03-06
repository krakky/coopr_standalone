# Coopr Standalone | v 1.0
Coopr is used internally as a self-service cluster provisioner for our developers, as a CI tool for integration testing, and as a DevOps tool to test new and incremental features. We’ve been developing and using Coopr for over a year, and we’re noticing the benefits: our developer and DevOps productivity have doubled, and our development and test cycles have become faster.

# SHA256 | (.tar.gz) integrity check
**69118F6418453C9B6B5F6D7E3EC5143D56771B6DE308469294B5BDEA656217C4**

# License | Apache License 2.0
Refer to the [LICENSE](https://github.com/krakky/coopr_standalone/blob/master/LICENSE) file for more info !

# Requirements
- Coopr UI RAM: 512 MB minimum | 1 GB RAM recommended
- Coopr Server RAM: 1 GB minimum | 3 GB RAM recommended
- Coopr Provisioners RAM: 256 MB allocated for each of the running workers
  - for example, with 10 workers = 2.5 GB minimum
- Database (ex: MySQL) RAM: 1 GB minimum | 2 GB recommended
- Disk 	Disk usage increases as Coopr usage increases; suggested minimum of 50GB
- amd64 processor

# Supported OS:
- CentOS 6.4
- Ubuntu 12.04
