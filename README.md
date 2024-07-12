# Red Hat Image Builder Blueprints

[![GitHub License](https://img.shields.io/github/license/snapp/image_builder-blueprints)](https://github.com/snapp/image_builder-blueprints/blob/main/LICENSE)
[![CI](https://github.com/snapp/image_builder-blueprints/actions/workflows/main.yml/badge.svg)](https://github.com/snapp/image_builder-blueprints/actions/workflows/main.yml)

This repository provides opinionated [Red Hat Image Builder](https://console.redhat.com/insights/image-builder) blueprints for a variety of [Red Hat Enterprise Linux (RHEL)](https://access.redhat.com/products/discover-red-hat-enterprise-linux) versions.

Some blueprints are for RHEL [Gold Image](https://access.redhat.com/documentation/en-us/subscription_central/1-latest/html-single/red_hat_cloud_access_reference_guide/index#understanding-gold-images_cloud-access) replicas, while others are pre-hardened for specific security profiles and may require you to [Install Image Builder in your environment](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html-single/composing_a_customized_rhel_system_image/index#installing-composer_composing-a-customized-rhel-system-image).

> [!WARNING]
>
> This code is NOT supported by Red Hat and may not work as expected.
>
> Red Hat does not guarantee its correctness, reliability, or performance.
>
> Use at your own risk!

## Reference Documentation
- [Learn about Red Hat Enterprise Linux and Insights image builders](https://access.redhat.com/articles/7076676)
- [Composing a customized RHEL system image](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html-single/composing_a_customized_rhel_system_image/index)
- [Composing, installing, and managing RHEL for Edge images (RPM-OSTree)](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html-single/composing_installing_and_managing_rhel_for_edge_images/index)
- [Creating pre-hardened images with RHEL image builder OpenSCAP integration](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/9/html-single/composing_a_customized_rhel_system_image/index#assembly_creating-pre-hardened-images-with-image-builder-openscap-integration_composing-a-customized-rhel-system-image)
- [Image Builder User Guide](https://osbuild.org/docs/user-guide/introduction)
- [Image Builder Blueprint Reference](https://osbuild.org/docs/user-guide/blueprint-reference)

## Licensing

GNU General Public License v3.0 or later

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
