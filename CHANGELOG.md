# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0](https://github.com/lotusnoir/ansible-system_apt_sources/compare/1.1.0...2.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`d61ea86`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/d61ea864d7039308699ddc3afa68391214750b75)
- update core, molecule + gitlab-ci [`3d28a8d`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/3d28a8dc523f05e9a8173c897eafbc143b6230b2)
- rebuild role with multiple install possibilities + benchmark [`b5c1bfa`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/b5c1bfa0a94fd1988ecef024d2b4a13ce5d51347)
- fix lint [`983300a`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/983300adb22742c9f0d2e1b32f01f1c186d31f47)
- remove .ansible folder [`56dacc1`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/56dacc18e5a971988e467d15965e5f574fd8749e)
- remove notify to give to choice to update the cache [`036c180`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/036c180ecc10d2f3d68ee319fa352b13608b1119)
- update release change to include more cases [`b09db36`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/b09db369c7231289b12052080f683fea117bc1d8)
- fix molecule paralelism and little updates [`36bab1d`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/36bab1d2613633793311bb52ad04e53b2f9f520a)

## [1.1.0](https://github.com/lotusnoir/ansible-system_apt_sources/compare/1.0.0...1.1.0) - 2025-01-17

### Commits

- add support for ubuntu24 [`d975200`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/d97520066ca48a8df1c10c3d1ac276cb2a41f7ce)
- add periodic auto update option [`81a3a59`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/81a3a595b52e201f1cfc73e8e8b21f1174c365ad)
- add version on molecule play image to maintain support on old release [`19abfdf`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/19abfdf6a1d3fda3f4e521091c75c40b74b906ec)
- remove support for debian10 / ubuntu18 / redhat8 [`2858104`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/2858104a6bb1055834d1cfaa50244410082d348d)
- remove duplicate task [`dd73289`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/dd73289665f49521616fa2cef65538f9b8bb9b1c)
- update molecule [`74362dc`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/74362dcad718449d357911ecd9be0d820bd51954)
- add apt_sources_force_ipv4 option [`34f3a7a`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/34f3a7a462701399b3e2b18c51dd571f99c2122c)
- add retry on update [`a088d38`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/a088d38080897e32b432797ba4e40198029d2f38)
- add redhat 8 to default supported distrib [`5cb8aa6`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/5cb8aa6d07e13b768ffa9ede9f6fae22a9449608)
- sort testing distrib to avoid random changes [`e312ed0`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/e312ed08931440ad29ae333c2b8e243dfea20fcb)

## [1.0.0](https://github.com/lotusnoir/ansible-system_apt_sources/compare/0.1.0...1.0.0) - 2023-09-25

### Commits

- update vars [`425b780`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/425b7808c7d28eaab42bd4301c448a5543ffe2d4)
- update readme + precommit + include vars [`0159296`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/0159296a7b0625899e1197b45a478bd09893224a)
- change import tasks to include in order to support facts on name [`4076070`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/4076070402f1ac63917b115003ff690dad17f6b1)

## 0.1.0 - 2023-06-14

### Commits

- fix lint [`f021aa7`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/f021aa7e63a353515ff3735c098dbeefac891f52)
- sync default to match base ditrib config [`1859f8b`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/1859f8b7c68bc131e2776f0d6266004113af05c8)
- initial commit [`a59e788`](https://github.com/lotusnoir/ansible-system_apt_sources/commit/a59e788878873b33bcb8fbfd25852debb3c93e2c)
