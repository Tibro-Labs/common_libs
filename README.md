![Alt text](https://g.gravizo.com/g?
  digraph G {
    triglav_rest[shape="diamond", style=rounded]
    svarog_reports[shape="box", style=rounded]
    stribog[shape="box", style=rounded]
    afpzrr_sop_triglav_plugin[shape="box", style=rounded]
    afsard_triglav_plugin[shape="box", style=rounded]
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