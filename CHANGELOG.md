# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.15.0] - 2022-11-09

### Changed

- Update external-dns to v2.16.0. This version uses workload-identity as an authentication method

## [0.14.3] - 2022-10-18

### Changed

- Bumped Cilium to 0.5.0

## [0.14.2] - 2022-10-14

### Fixed

- Bumped Cilium to 0.4.2

## [0.14.1] - 2022-10-14

### Changed

- Bumped Cilium to 0.4.1

## [0.14.0] - 2022-10-10

## [0.13.2] - 2022-10-05

### Changed

- Update workload-identity-operator-gcp version version to 0.4.3.
- Update gcp-compute-persistent-disk-csi-driver-app version to 0.5.0.
- Explicitly define Apps configmaps so we can use helm values when defining the config map content.

## [0.13.1] - 2022-09-27

### Changed

- Update workload-identity-operator-gcp to 0.4.2 to add flag to enable the cluster reconciler.

## [0.13.0] - 2022-08-25

### Changed

- Change cilium configuration to delegate pods IPAM to controller manager.

## [0.12.0] - 2022-08-19

### Changed

- Update kube-state-metrics to 1.11.0 to fix team label for monitoring purposes.
- Update workload-identity-operator-gcp to 0.3.1

## [0.11.0] - 2022-07-20

### Added

- Add workload-identity-operator-gcp admission controller.

## [0.10.1] - 2022-07-14

### Fixed

- Fix version of the gcp-compute-persistent-disk-csi-driver-app app.

## [0.10.0] - 2022-07-14

### Added

- Add gcp-compute-persistent-disk-csi-driver-app app.

## [0.9.1] - 2022-07-06

### Fixed

- Bumped VPA version to latest with PDB fix

## [0.9.0] - 2022-06-29

### Added

- Added userConfig to apps

## [0.8.0] - 2022-06-29

### Changed

- Bumped cilium to 0.2.4

## [0.7.2] - 2022-06-22

### Added

- Support for custom app values
- Enabled Cilium default policies

## [0.7.1] - 2022-06-17

### Changed

- Bumped coredns to 1.10.1

## [0.7.0] - 2022-06-17

### Changed

- Upgrade coredns to 1.10.0.

## [0.6.0] - 2022-06-16

### Changed

- Bumped all apps to latest version

## [0.5.0] - 2022-05-26

### Changed

- Change `cert-manager-app` name to `cert-manager` so that we use the same name that when installing from collection.

## [0.4.0] - 2022-05-13

## [0.3.0] - 2022-05-12

### Changed

- Change `cert-manager` name to `cert-manager-app` so that we use the same name that when installing from collection.

## [0.2.0] - 2022-05-04

### Added

- Add cert-manager and external-dns as default apps.

### Changed

- Add team label to helm resources.

## [0.1.5] - 2022-04-07

### Added

- Added coredns app

### Changed

- Updated Cilium to include PSPs

## [0.1.4] - 2022-03-29

- Update cilium to `v0.1.0.`

## [0.1.3] - 2022-03-25

- Fix cilium app.


[Unreleased]: https://github.com/giantswarm/default-apps-gcp/compare/v0.15.0...HEAD
[0.15.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.14.3...v0.15.0
[0.14.3]: https://github.com/giantswarm/default-apps-gcp/compare/v0.14.2...v0.14.3
[0.14.2]: https://github.com/giantswarm/default-apps-gcp/compare/v0.14.1...v0.14.2
[0.14.1]: https://github.com/giantswarm/default-apps-gcp/compare/v0.14.0...v0.14.1
[0.14.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.13.2...v0.14.0
[0.13.2]: https://github.com/giantswarm/default-apps-gcp/compare/v0.13.1...v0.13.2
[0.13.1]: https://github.com/giantswarm/default-apps-gcp/compare/v0.13.0...v0.13.1
[0.13.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.12.0...v0.13.0
[0.12.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.11.0...v0.12.0
[0.11.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.10.1...v0.11.0
[0.10.1]: https://github.com/giantswarm/default-apps-gcp/compare/v0.10.0...v0.10.1
[0.10.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.9.1...v0.10.0
[0.9.1]: https://github.com/giantswarm/default-apps-gcp/compare/v0.9.0...v0.9.1
[0.9.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.8.0...v0.9.0
[0.8.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.7.2...v0.8.0
[0.7.2]: https://github.com/giantswarm/default-apps-gcp/compare/v0.7.1...v0.7.2
[0.7.1]: https://github.com/giantswarm/default-apps-gcp/compare/v0.7.0...v0.7.1
[0.7.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.6.0...v0.7.0
[0.6.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.5.0...v0.6.0
[0.5.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.3.0...v0.4.0
[0.3.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/giantswarm/default-apps-gcp/compare/v0.1.5...v0.2.0
[0.1.5]: https://github.com/giantswarm/default-apps-gcp/compare/v0.1.4...v0.1.5
[0.1.4]: https://github.com/giantswarm/default-apps-gcp/compare/v0.1.3...v0.1.4
[0.1.3]: https://github.com/giantswarm/default-apps-gcp/compare/v0.1.2...v0.1.3
