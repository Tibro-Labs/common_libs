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