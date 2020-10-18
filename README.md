# Deno Planet CSV Parser

A simple deno program that reads keplar csv data and queries that data for planetary systems that meet a planetary radius above 0.5 and less than 1.5, a stellar radius greater than 0.99 and less than 1.01 with a stellar mass between 0.78 and 1.04.

```
{
  kepler_name: "Kepler-299 b",
  koi_prad: "1.29",
  koi_smass: "0.9030",
  koi_srad: "0.9990",
  koi_count: "4",
  koi_steff: "5616.00"
}
{
  kepler_name: "Kepler-407 b",
  koi_prad: "1.13",
  koi_smass: "0.9770",
  koi_srad: "1.0030",
  koi_count: "1",
  koi_steff: "5475.00"
}
{
  kepler_name: "Kepler-1035 b",
  koi_prad: "1.38",
  koi_smass: "1.0380",
  koi_srad: "0.9920",
  koi_count: "1",
  koi_steff: "5815.00"
}
{
  kepler_name: "Kepler-1156 b",
  koi_prad: "1.33",
  koi_smass: "0.9230",
  koi_srad: "0.9920",
  koi_count: "1",
  koi_steff: "5649.00"
}
{
  kepler_name: "Kepler-387 b",
  koi_prad: "1.01",
  koi_smass: "0.8240",
  koi_srad: "1.0030",
  koi_count: "2",
  koi_steff: "5772.00"
}
{
  kepler_name: "Kepler-387 c",
  koi_prad: "1.00",
  koi_smass: "0.8240",
  koi_srad: "1.0030",
  koi_count: "2",
  koi_steff: "5772.00"
}
{
  kepler_name: "Kepler-1417 b",
  koi_prad: "1.01",
  koi_smass: "0.9420",
  koi_srad: "1.0020",
  koi_count: "1",
  koi_steff: "5952.00"
}
{
  kepler_name: "Kepler-1560 b",
  koi_prad: "0.90",
  koi_smass: "0.9090",
  koi_srad: "0.9930",
  koi_count: "1",
  koi_steff: "5755.00"
}

8 habitable planets found!
```

## Run application

```
deno run --allow-read mod.ts
```
