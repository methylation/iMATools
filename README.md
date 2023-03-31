# iMATools
iMATools(integrated Methylation Analysis Tools) provides a comprehensive analysis for high-throughput DNA methylation data.
iMATools including eight subtools:
* towig: converts methylation level files such as WGBS, TAPS, ONT to standard wig format
* pattern: identifies methylation pattern regions based on the methylation data in wig format
* dmr: identifies differentially methylated regions of two groups based on methylation data in wig format
* refpattern: identifies regions of methylation patterns that occur consistently across multiple samples
* wigtodp: converts wig to the files needed for deeptools visualization
* readvisual: visualizes the methylation status of CpG sites on reads
* bedmethy: calculates a matrix of methylation levels for predefined regions
* bedarray: calculates the methylation level matrix (beta value) of a predefined region


Input command name to get usage for each subtool.
![workflow](https://github.com/methylation/iMATools/blob/main/imgs/iMATools.png "foo")
iMATools provides a exploration of DNA methylation data at different data levels:
![Analysis at different level](https://github.com/methylation/iMATools/blob/main/imgs/diff_level.png "foo")

