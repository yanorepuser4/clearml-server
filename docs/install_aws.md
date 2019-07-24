# **TRAINS-server**: AWS pre-installed images

In order to easily deploy **trains-server** on AWS, we created the following Amazon Machine Images (AMIs).

Service port numbers on these AMIs are:
 - Web: 8080
 - API: 8008
 - File Server: 8081

Persistent storage configuration:
 - MongoDB: /opt/trains/data/mongo/
 - ElasticSearch: /opt/trains/data/elastic/
 - File Server: /mnt/fileserver/

Instructions on launching a custom AMI from the EC2 console can be found [here](https://aws.amazon.com/premiumsupport/knowledge-center/launch-instance-custom-ami/)
and a detailed version [here](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/launching-instance.html).

The minimum recommended instance type is **t3a.large**

## Upgrading

In order to upgrade **trains-server** on an existing EC2 instance based on one of these AMIs, SSH into the instance and follow the [upgrade instructions](../README.md#upgrade) for **trains-server**.

## Released versions

The following sections provide a list containing AMI Image ID per region for each released **trains-server** version.

### Latest Version AMI
**For easier upgrades: The following AMI automatically update to the latest release every reboot**

* **eu-north-1** : ami-0a8e95b10d114f76c
* **ap-south-1** : ami-03d9fac7e8135fd04
* **eu-west-3** : ami-0bed4b2370f302790
* **eu-west-2** : ami-059324ba0d5654589
* **eu-west-1** : ami-00c06eb6a5b00d232
* **ap-northeast-2** : ami-0b33a9d6c664a603a
* **ap-northeast-1** : ami-07e009465d393dced
* **sa-east-1** : ami-09f13cbfe97c7feb7
* **ca-central-1** : ami-01dda915fb6839526
* **ap-southeast-1** : ami-0f4dc19d07d5dcfc3
* **ap-southeast-2** : ami-0a93d6954e60498f9
* **eu-central-1** : ami-0dd62c8096e7e5bbd
* **us-east-2** : ami-07e89b3eab48a3c03
* **us-west-1** : ami-093b365a75c8457ab
* **us-west-2** : ami-0b3c068037f8cb03d
* **us-east-1** : ami-0f2e1f2d006287666

### v0.10.1
* **eu-north-1** : ami-0059e722ab7aff31b
* **ap-south-1** : ami-05aa09b6dfaef2057
* **eu-west-3** : ami-03ce396ad6c08c684
* **eu-west-2** : ami-0ef9a00780ca4a6c6
* **eu-west-1** : ami-0cd75eef75fbfeb28
* **ap-northeast-2** : ami-04fc511ca43663746
* **ap-northeast-1** : ami-0681413e88c6c3716
* **sa-east-1** : ami-0e7373671cc5280c2
* **ca-central-1** : ami-0e1af38b0c9d18e70
* **ap-southeast-1** : ami-0d49dbd7d7abfbb80
* **ap-southeast-2** : ami-041160f24b8e62635
* **eu-central-1** : ami-0ecb6bba2ee7bd63b
* **us-east-2** : ami-0f668fc81356df4f5
* **us-west-1** : ami-032a3e3ae5f1bb661
* **us-west-2** : ami-02dae03bb9708579a
* **us-east-1** : ami-0ca191ee0226617cb

### v0.10.0
* **eu-north-1** : ami-05ba33c763877e54e
* **ap-south-1** : ami-0529eec569161cae5
* **eu-west-3** : ami-03cb9396f63e26ff6
* **eu-west-2** : ami-0dd28cc97283cc201
* **eu-west-1** : ami-059cf379ae14b0a24
* **ap-northeast-2** : ami-031409d71f1280616
* **ap-northeast-1** : ami-0171437c68b3660aa
* **sa-east-1** : ami-0eb440a3b6e591c7a
* **ca-central-1** : ami-097da9ec155ee654a
* **ap-southeast-1** : ami-0ab7ff3ea09826e39
* **ap-southeast-2** : ami-00969c550ef2d1f60
* **eu-central-1** : ami-02246400c51990acb
* **us-east-2** : ami-0cafc1d730381d6fa
* **eu-central-1** : ami-02246400c51990acb
* **us-west-1** : ami-0e82a98ddbe995a65
* **us-west-2** : ami-04a522ecb2250fb44
* **us-east-1** : ami-0a66ddbd50959f91e

### v0.9.0

* **us-east-1** : ami-0991ad536ecbacdac
* **eu-north-1** : ami-07cbcdff501b14afe
* **ap-south-1** : ami-014cf398b00d4db83
* **eu-west-3** : ami-0396ba51e9b733581
* **eu-west-2** : ami-09134f4c7a20bad09
* **eu-west-1** : ami-00427ed0a1bbfa7b0
* **ap-northeast-2** : ami-041756675ca1be954
* **ap-northeast-1** : ami-0c09ebad05c9128ff
* **sa-east-1** : ami-017a8de4e8d1e8c8e
* **ca-central-1** : ami-049ec444470f852be
* **ap-southeast-1** : ami-0c919b8f821a6c635
* **ap-southeast-2** : ami-04844a0594712d27b
* **eu-central-1** : ami-0b4e756e0f7c0617d
* **us-east-2** : ami-03b01914b07428488
* **us-west-1** : ami-0cf4768e9d47ed076
* **us-west-2** : ami-0b145f37da31eb9fb