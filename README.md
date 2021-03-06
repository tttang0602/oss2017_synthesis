
## README

### Cloning and updating the repo

```bash
# do this to get the repo, first time only
git clone https://www.github.com/fawda123/oss2017_synthesis.git

# do this every time before you make changes
git pull

# do this after you make changes
git add -A
git commit -m "informative message"
git pull
git push
```
### View info online

Data aggregation: <https://fawda123.github.io/oss2017_synthesis/tbrest>

Final presentation: <https://fawda123.github.io/oss2017_synthesis/presentations/final_pres>

### Repository info

Folders:

* `data` RData files, load with `data(filename)`
* `data-raw` - put raw and intermediate data files here, e.g., .xlsx., .txt., .csv
* `Diagrams` - workflow diagrams
* `Model` - BN model files
* `presentations` presentation files
* `R` - R scripts

RData files (these should be text files?) in `data`, normalized:

* `allchg.RData` All chlorophyll data with habitat, water treatment, and salinity levels, discretized and continuous chl
* `bmpdat.RData` restoration projects for water treatment
* `bmpstat.RData` locations of restoration projects for water treatment
* `chlbar.RData` final data of chlorophyll splits for BN
* `chlchg.RData` All chl data with habitat, water treatment bef/aft projects, discretized and continuous
* `chlchgout.RData` All chl data with habitat, water treatment bef/aft projects, discretized and continuous, intermediate step
* `habdat.RData` restoration projects for habitat
* `habstat.RData` locations of restoration projects for habitat
* `restdat.RData` restoration projects combined
* `reststat.RData` location of restoration projects combined
* `salchg.RData` All salinity data with habitat, water treatment bef/aft projects, discretized and continuous
* `salchgout.RData` All salinity data with habitat, water treatment bef/aft projects, discretized and continuous, intermediate step
* `wqdat.RData` TB water quality data by site, date, var, val
* `wqstat.RData` TB water quality stations as lat/lon
