[![build status](https://gitlab.prtech.mk/prtech/common_libs/badges/master/build.svg)](https://gitlab.prtech.mk/prtech/common_libs/commits/master)


![Alt text](https://g.gravizo.com/g?
  digraph G {
    triglav_rest[shape="diamond", style=rounded]
    svarog_reports[shape="box", style=rounded, color="orange"]
    stribog[shape="box", style=rounded, color="orange"]
    afpzrr_sop_triglav_plugin[shape="box", style=rounded, color="blue"]
    afsard_triglav_plugin[shape="box", style=rounded, color="blue"]
    svarog -> svarog_reports[color="green"]
    svarog -> stribog[color="green"]
    svarog -> afpzrr_sop_triglav_plugin[color="green"]
    svarog -> afsard_triglav_plugin[color="green"]
    svarog -> triglav_rest[label="libs", color="red"]
    svarog_reports -> triglav_rest[label="libs", color="red"]
    stribog -> triglav_rest[label="libs", color="red"]
    afpzrr_sop_triglav_plugin -> triglav_rest[label="plugins", color="blue"]
    afsard_triglav_plugin -> triglav_rest[label="plugins", color="blue"]
  }
)