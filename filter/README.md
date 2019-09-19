# To filter raw data on Illumina
raw_reads_filter_SE_v0.5.pl # Single-end sequence
raw_reads_filter_v0.5.pl # Pair-end sequence

# usage
perl raw_reads_filter.pl -1 read1.fq -2 read2.fq -a 1.adapter.list.gz -b 2.adapter.list.gz -3 clean_data1.fq -4 clean_data2.fq
