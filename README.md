# OHW_in_CDR
The code for this research examines the use and value of open hardware in academic sustainability research, particularly to studies in the areas of carbon capture and carbon dioxide removal (CDR) between 2020 and 2023.

Plots of findings are at this [public Google Drive link](https://docs.google.com/spreadsheets/d/1FXEIRlsCNr_2xBqnUEBjhIrs2sTX_XivQxlx7rRh9p0/edit?usp=sharing).

Code to generate the findings are in the `src` folder in the Jupyter notebook `main.ipynb`.

## Results

Open access journals (OA) are distinguished from non-open access journals (NA) by darker and lighter shades of color, respectively. 

The colors denote whether co-authors on a paper also had written other papers that mentioned open hardware (or open source hardware). Blue distinguishes authors on CDR papers with co-authors that had open hardware associations (OHW). Red signifies those without (NOHW). 

### Open Access and Open Hardware

#### Papers of average impact have better metrics in non-open access journals 

* For all three metrics (impact factor, H-index, and i10-index), the mean and median values are higher in non-open access journals (NA) compared to open access ones (OA).

#### Papers with exceptional impact tend to have co-author connections to open hardware

* For H-index and i10-index, in both cases the maximum impact factors are higher when there was a co-author association with OHW than without, regardless of whether the CDR publication was published open access or not.

#### If one has co-author connections to open hardware, publish open access for higher impact factors. Publishing non-open access is associated with lower impact factors for this set. 

* The CDR-OA-OHW set had the highest maximum impact factor of all sets, over twice that of CDR-NA-OHW. Having an academic association with open hardware through one's co-authors appears to be most beneficial when publishing in an open access journal than not. 

* The maximum impact factor for publications with an OHW association published in a non-open access journal (CDR-NA-OHW) is the lowest of all four sets - lower than publications without an OHW association (CDR-NA-NOHW). 

![Open Hardware and Open Access](/images/OHW_OA.png)

### Open Access Only

CDR publications in open access journals tend to have lower mean and median impact factors, H-index values, and i10-index values than those in non-open access journals. Lower maximum impact factors were also found in open access journals compared to non-open access.

However, a considerably higher maximum impact factor attainable when publishing in an open access journal compared to a non-open access one.

![Open Access Only](/images/OA.png)

### Open Hardware Citations Only

Co-authors of CDR publications who have also cited open hardware (OHW) publications tend to have higher mean, median, and maximum H-index and i10-index values, with the difference being much greater for maximum H-index and i10-index values than for the mean or median of these.

The same trend occurs with impact factor; co-authors with OHW citations also see higher impact factors than those whose co-author associations do not include OHW.

However, mean and median impact factors follow the same trend of being lower among co-authors associated with OHW citations than without as is present for co-authors that have published in open access journals compared to non-open access ones.

![Open Hardware Citations Only](/images/OHW.png)
