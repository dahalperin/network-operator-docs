.. license-header
  SPDX-FileCopyrightText: Copyright (c) 2024 NVIDIA CORPORATION & AFFILIATES. All rights reserved.
  SPDX-License-Identifier: Apache-2.0

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

  http://www.apache.org/licenses/LICENSE-2.0

  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.

.. headings # #, * *, =, -, ^, "
.. include:: ../common/vars.rst

.. _container_images_digest:

****************************************
NVIDIA Network Operator Container Images
****************************************



.. list-table::
   :header-rows: 1

   * - Repository
     - Image Name
     - Tag
     - Digest
   * - nvcr.io/nvidia/cloud-native
     - network-operator
     - v26.4.0
     - sha256:07867535ee9853e9da28824e1334fe3577e5c843c6c54e372b6e86cae09bd0fd
   * - nvcr.io/nvidia/mellanox
     - network-operator-init-container
     - network-operator-v26.4.0
     - sha256:d1fcdf836604591d018628f9ac8ecec30d14cee85e2aa1ea6fe762cfe463df75
   * - nvcr.io/nvidia/mellanox
     - k8s-rdma-shared-dev-plugin
     - network-operator-v26.4.0
     - sha256:c50fe96cfb2e32cf497f3723cc0b90f72582c2bc84b3593389dc14bc813a58fc
   * - nvcr.io/nvidia/mellanox
     - ib-kubernetes
     - network-operator-v26.4.0
     - sha256:5a1a672498ddee1d0176824f6b0f0528992924816e751d2aaf90ded168796e07
   * - nvcr.io/nvidia/mellanox
     - ipoib-cni
     - network-operator-v26.4.0
     - sha256:3e283b4371fa4a06d0bfbf6daddff7362741b289e1e7e9d165a06bf938eba3e7
   * - nvcr.io/nvidia/mellanox
     - nvidia-k8s-ipam
     - network-operator-v26.4.0
     - sha256:ff7cadaf425a2def4db2ff769c4f2c293090f6970f0c27b40a2b472014b5cfb8
   * - nvcr.io/nvidia/mellanox
     - nic-feature-discovery
     - network-operator-v26.4.0
     - sha256:87a40b10a44cd3e028ea16725af8f22b16f5e8ddc533441632616fd9bc53228a
   * - nvcr.io/nvidia/doca
     - doca_telemetry
     - 1.25.5-doca3.4.0-host
     - sha256:e728430bdde27bc0f2e57cedb83814f21d23113385328034af9727e900724d09
   * - nvcr.io/nvidia/mellanox
     - sriov-network-operator
     - network-operator-v26.4.0
     - sha256:a799fe3c9fd376a30083909da5a5b39f7851af4dc00d719493eb0256dd396446
   * - nvcr.io/nvidia/mellanox
     - sriov-network-operator-webhook
     - network-operator-v26.4.0
     - sha256:b811ba0fa8fb88482ba9bee06287bb64854f9c7c56d1772103d5bb4b8ebabf43
   * - nvcr.io/nvidia/mellanox
     - sriov-network-operator-config-daemon
     - network-operator-v26.4.0
     - sha256:52aa75fe434448164885c1c3b7bd7f319775ecfc941f47532c0e789bb6aeb584
   * - nvcr.io/nvidia/mellanox
     - sriov-network-device-plugin
     - network-operator-v26.4.0
     - sha256:549c8e6baec0f682780124212f552147b2e41776fcc3453f98c28c001d65e119
   * - nvcr.io/nvidia/mellanox
     - sriov-cni
     - network-operator-v26.4.0
     - sha256:90e88077aea8b720c5b754f65e6b61699d66b73e2574dc8908801c9330e170e7
   * - nvcr.io/nvidia/mellanox
     - ib-sriov-cni
     - network-operator-v26.4.0
     - sha256:8e726d20729bb9446f66fa96552af9afdde9916e2ac5f2d03211afa60f8feb9c
   * - nvcr.io/nvidia/mellanox
     - dra-driver-sriov
     - network-operator-v26.4.0
     - sha256:4826e987fd4e2d9886a5329e6dde50bf4a5cdcba1320546cd2eb16d86e854a2d
   * - nvcr.io/nvidia/mellanox
     - plugins
     - network-operator-v26.4.0
     - sha256:9d50e188ecba0071aaecee735770f75d6c9a76c3705f0731da3f7153b20b7e00
   * - nvcr.io/nvidia/mellanox
     - multus-cni
     - network-operator-v26.4.0
     - sha256:0982edc0b68a288b90e4be8bfb219e0119d48ee51f6c0bb3383a82ebc3fa09a1
   * - nvcr.io/nvidia/mellanox
     - ovs-cni-plugin
     - network-operator-v26.4.0
     - sha256:324a5d0ddcc35a57e3bfb8992f86c065ca2d0b033d54de20cc709f3825c80276
   * - nvcr.io/nvidia/mellanox
     - rdma-cni
     - network-operator-v26.4.0
     - sha256:343b921d5458b8ad758524d7c8a4f250919b5f218a15db49f045205e82aca135
   * - nvcr.io/nvidia/mellanox
     - nic-configuration-operator
     - network-operator-v26.4.0
     - sha256:71ce9925c5b03b50be12e55b616dbde424e40e31e889c41485c5bda29908b54c
   * - nvcr.io/nvidia/mellanox
     - nic-configuration-operator-daemon
     - network-operator-v26.4.0
     - sha256:fe970471827cef38d4270e275d58282d140aeb3b4f19636506b02b1cdd20de2e
   * - nvcr.io/nvidia/mellanox
     - maintenance-operator
     - network-operator-v26.4.0
     - sha256:fa285b8b3ea1b2ee8136136ef73ff92ccaf66818b3f62d90d02da556de754292
   * - nvcr.io/nvidia/mellanox
     - spectrum-x-operator
     - network-operator-v26.4.0
     - sha256:e9d26776153a74abaf9c7813bd580dfd9aa424921d09825a732bfe9cbf9661f6

=================================
DOCA-OFED Driver Container Images
=================================


.. list-table::
   :header-rows: 1

   * - Repository
     - Image Name
     - Version
   * - nvcr.io/nvidia/mellanox
     - doca-driver
     - doca3.4.0-26.04-0.8.6.0-0


The followings tags are available for the above DOCA-OFED Driver container version:

------
Ubuntu
------

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-5.15.0-179-generic-ubuntu22.04-amd64
     - sha256:e2fb98399b0b9c0ab7c07ac08145595101c791dec60fe4488b0a262d38e4da12
   * -
       | doca3.4.0-26.04-0.8.6.0-0-5.15.0-179-generic-ubuntu22.04-arm64
     - sha256:b93f54181a049ef2b1ba0cf19d1ff258ec2121cffaa3ab8bad68d00dd85c37da
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1016-oracle-ubuntu24.04-amd64
     - sha256:f3c7cc66e73651c48c95b25fab1325ad15dca0b1e89b91cd7b17b7d761199d38
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1016-oracle-ubuntu24.04-arm64
     - sha256:8e9c0d34d807d580e5e65ea2aefea3ea2bd602b99190a5799b6222a5227c1ce1
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1017-aws-ubuntu24.04-amd64
     - sha256:d9b183f33c26ab1a82589d893ca8225ec34ddad029c5ea2218bd4e3d686a976d
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1017-aws-ubuntu24.04-arm64
     - sha256:b6e509826f0c5fae4e48dbce78bddaf41602df9cd7ce64ac482096ffaeb2d753
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1017-azure-ubuntu24.04-amd64
     - sha256:434cb80dea54e3ace776967f51e04c25ab131dbdcebc483282d569152a05c2e0
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1017-azure-ubuntu24.04-arm64
     - sha256:e88758718985959464609fe5005a60b048225eb22a4c75fb9efd7ea4aacc759c
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1021-nvidia-ubuntu24.04-amd64
     - sha256:fb9495a8f5c1089e8c5e35d888295885141a71630f4cb31aa9a99f3373c3393c
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.17.0-1021-nvidia-ubuntu24.04-arm64
     - sha256:51f50ae84d4fa518464aaa5efce1d63300e88b909349e91abb7eb8fc9b061f6e
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1052-azure-ubuntu22.04-amd64
     - sha256:9b0ea352c763ca10a372c2de3fc42a13b3b406471e1392514a0ea318c4046ee0
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1052-azure-ubuntu22.04-arm64
     - sha256:6a6c5903e72fc29b8edb132f72e50a64b4cbc1a30b82112fc08d78a67b2c802e
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1054-oracle-ubuntu22.04-amd64
     - sha256:729346073c8be7a4ae1bb1c2ab663d8c1a33ea6f4474a66d88bc044b524572ce
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1054-oracle-ubuntu22.04-arm64
     - sha256:821c6278d67fe545ecce479721f6d3892b19cea27b6d718deaa29f66921914b1
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1055-nvidia-ubuntu22.04-amd64
     - sha256:ce830598283ce7279801a03e8ab0d0ab91d503e07d9bd63591927389a1d45cd9
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1055-nvidia-ubuntu22.04-arm64
     - sha256:f1d52907e2dd4ef2bc3307a37d9fa6f4a16ca83fa988e6b2e0eb8e82d0344a34
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1057-aws-ubuntu22.04-amd64
     - sha256:e3af9a6fe7b36e70d73010a0e1a39f888bf3b71e13a80e5cdd4dd5fd60923d8b
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-1057-aws-ubuntu22.04-arm64
     - sha256:ead899c2a7c8d1fecc4652591665ea9878e733dbed21cc5f1833404f8aee1311
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-124-generic-ubuntu24.04-amd64
     - sha256:4de6000085edda2b2bab0af7825bb9563560440158e1dce5df203822e4ad20a1
   * -
       | doca3.4.0-26.04-0.8.6.0-0-6.8.0-124-generic-ubuntu24.04-arm64
     - sha256:f1fab0a966f157a0281826b544fb6f73439af948037387313ffe5a0597497677
   * -
       | doca3.4.0-26.04-0.8.6.0-0-ubuntu22.04-amd64
     - sha256:598cd0acfbb006f410ade8d3f8cb60972889b80c934e1ea74f94855c412406e4
   * -
       | doca3.4.0-26.04-0.8.6.0-0-ubuntu22.04-arm64
     - sha256:17e32032dd2c7722d0b4cc4da768ac19015aebb9839e02f5dc1111ae55b51bc2
   * -
       | doca3.4.0-26.04-0.8.6.0-0-ubuntu24.04-amd64
     - sha256:e38627c791bde4afcc3eb23268eca3cd38cb1062a515ca8abd4707501d022fa3
   * -
       | doca3.4.0-26.04-0.8.6.0-0-ubuntu24.04-arm64
     - sha256:4ae76785ee4dbdd663bf5821a85b6879875e32ad111913792b3472217599646a

-----
RHCOS
-----

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhcos4.17-amd64
       | doca3.4.0-26.04-0.8.6.0-0-rhcos4.18-amd64
     - sha256:1b03602d22a73fec168188237c29bd9eb842e3d23db294a4acd0d383ff078713
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhcos4.17-arm64
       | doca3.4.0-26.04-0.8.6.0-0-rhcos4.18-arm64
     - sha256:19b615a50c9950a35a5b51231e22c11eea2abc9cb79c36d0e2ccc5e02cf6fbb7

----
RHEL
----

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel10.0-amd64
     - sha256:8d7f8a3f5376d668c061a3ea976cf4f1b7007bd5b15a80fa6a1a029e1670b8a8
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel10.0-arm64
     - sha256:2d2b852f418a715fdaf05a5a34c23d4d0bcceef0b1a3cf6529f66899a65031ba
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel8.10-amd64
     - sha256:4e1c87863298e20d680d1ad2a08dc3e76939cfccfc66b2e8b3f2583014aa9335
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel8.10-arm64
     - sha256:65045cc7af14d52b5d742e37ae4ec9effb56cb69dfb1506cdd682a2c78ba4904
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel9.4-amd64
       | doca3.4.0-26.04-0.8.6.0-0-rhel9.6-amd64
     - sha256:fafe2844b8fb624b5a491155438e2b05702eb4a1fae2ccd0dfbd71468a43081c
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel9.4-arm64
       | doca3.4.0-26.04-0.8.6.0-0-rhel9.6-arm64
     - sha256:c74dc21c84d7b611dbd921e1984d026427b2c6b13ad5340876382dcb98745544

----
SLES
----

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-sles15.7-amd64
     - sha256:77da9eb69d1947ae01d224b70d6430d057dee18f0a5b208e1e0cab9ed0f344f0
   * -
       | doca3.4.0-26.04-0.8.6.0-0-sles15.7-arm64
     - sha256:ae1886acc2b84ad11984d444ee25bcdfee408ff12d8d96554c2f143e6a45bc1a


=====================================================
STIG FIPS Compliant DOCA-OFED Driver Container Images
=====================================================

.. list-table::
   :header-rows: 1

   * - Repository
     - Image Name
     - Version
   * - nvcr.io/nvidia/mellanox
     - doca-driver-stig-fips
     - doca3.4.0-26.04-0.8.6.0-0

The followings tags are available for the above STIG FIPS Compliant DOCA-OFED Driver container version:

------
Ubuntu
------

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-ubuntu24.04-amd64
     - sha256:2a6a33224dc407daa3f82f05d4fbbb73880f0f9dd6c55992ae4f6808c1c7c7d8

----
RHEL
----

.. list-table::
   :header-rows: 1

   * - Tags
     - Digest
   * -
       | doca3.4.0-26.04-0.8.6.0-0-rhel9.6-amd64
     - sha256:ed63f58a1ba140df351b732575c76831cccf09032224d53bf12376b39103b2bb