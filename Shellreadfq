#! /bin/bash
ls *.fq >fq.list
for i in $(cat fq.list)
do 
  printf $i "\t" >>fq.reads_num
  .$readfq $i >>fq.reads_num
done
