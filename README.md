![Alt text](https://g.gravizo.com/g?
  digraph G {
    triglav_rest[shape="diamond", style=rounded]
    svarog_reports[shape="box", style=rounded, color="orange"]
    stribog[shape="box", style=rounded, color="orange"]
    afpzrr_sop_triglav_plugin[shape="box", style=rounded, color="blue"]
    aleph_triglav_plugin[shape="box", style=rounded, color="blue"]
    afsard_triglav_plugin[shape="box", style=rounded, color="blue"]
    svarog_custom_afsard_dp[shape="box", style=rounded, color="brown"]
    svarog_custom_afsard_dp -> svarog[label="custom", color="blue"]
    svarog -> aleph_triglav_plugin[color="green"]
    svarog -> svarog_reports[color="green"]
    svarog -> stribog[color="green"]
    svarog -> afpzrr_sop_triglav_plugin[color="green"]
    svarog -> afsard_triglav_plugin[color="green"]
    svarog -> triglav_rest[label="libs", color="red"]
    svarog_reports -> triglav_rest[label="libs", color="red"]
    stribog -> triglav_rest[label="libs", color="red"]
    aleph_triglav_plugin -> triglav_rest[label="plugins", color="blue"]
    afpzrr_sop_triglav_plugin -> triglav_rest[label="plugins", color="blue"]
    afsard_triglav_plugin -> triglav_rest[label="plugins", color="blue"]
  }
)

|                          | master|staging| dev   |
|--:                       |:-:    |:-:    |:-:    |
|svarog_custom_afsard_dp   |[![build status](https://gitlab.prtech.mk/prtech/svarog_custom_afsard_dp/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/svarog_custom_afsard_dp/commits/master)     | | |
|svarog                    |[![build status](https://gitlab.prtech.mk/prtech/svarog/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/svarog/commits/master)                                       | [![build status](https://gitlab.prtech.mk/prtech/svarog/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/svarog/commits/staging)                                       | [![build status](https://gitlab.prtech.mk/prtech/svarog/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/svarog/commits/dev)                                       |
|svarog_reports            |[![build status](https://gitlab.prtech.mk/prtech/svarog_reports/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/svarog_reports/commits/master)                       | [![build status](https://gitlab.prtech.mk/prtech/svarog_reports/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/svarog_reports/commits/staging)                       | [![build status](https://gitlab.prtech.mk/prtech/svarog_reports/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/svarog_reports/commits/dev)                       |
|stribog                   |[![build status](https://gitlab.prtech.mk/prtech/stribog/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/stribog/commits/master)                                     | [![build status](https://gitlab.prtech.mk/prtech/stribog/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/stribog/commits/staging)                                     | [![build status](https://gitlab.prtech.mk/prtech/stribog/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/stribog/commits/dev)                                     |
|afpzrr_sop_triglav_plugin |[![build status](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/commits/master) | [![build status](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/commits/staging) | [![build status](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/afpzrr_sop_triglav_plugin/commits/dev) |
|aleph_triglav_plugin      |[![build status](https://gitlab.prtech.mk/prtech/aleph_triglav_plugin/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/aleph_triglav_plugin/commits/master)           | | |
|afsard_triglav_plugin     |[![build status](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/commits/master)         | [![build status](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/commits/staging)         | [![build status](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/afsard_triglav_plugin/commits/dev)         |
|triglav_rest              |[![build status](https://gitlab.prtech.mk/prtech/triglav_rest/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/triglav_rest/commits/master)                           | [![build status](https://gitlab.prtech.mk/prtech/triglav_rest/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/triglav_rest/commits/staging)                           | [![build status](https://gitlab.prtech.mk/prtech/triglav_rest/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/triglav_rest/commits/dev)                           |
|common_libs               |[![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/master)                             | [![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/staging)                             | [![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/dev)                             |
|gitlab-ci                 |[![build status](https://gitlab.prtech.mk/prtech/gitlab-ci/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/gitlab-ci/commits/master)                                 | | |


###### Buiild status for branch:
 - Master:
   - [![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/master)
 - Staging:
   - [![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/staging/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/staging)
 - Dev:
   - [![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/dev/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/dev)

### Git; Branch and Stability Info
Source control is `Git` exclusive:

* The `master` branch is updated only from the current state of the `staging` branch
* The `staging` branch must only be updated with commits from the `dev` branch
* The `dev` branch contains all the latest additions to the project
* All larger feature updates must be developed in their own branch and later merged into `dev`
