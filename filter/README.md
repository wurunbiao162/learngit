# 两个脚本都是用于过滤二代测序下机数据
raw_reads_filter_SE_v0.5.pl # 单端测序
raw_reads_filter_v0.5.pl # 双端测序

# 使用案例
perl raw_reads_filter.pl -1 read1.fq -2 read2.fq -a 1.adapter.list.gz -b 2.adapter.list.gz -3 clean_data1.fq -4 clean_data2.fq
