# genome_tools
My genomic scripts

Example usage:

```
echo "name count" > my_file.csv
for fasta in *.fa; do
  count=$( bash count_seq.sh $fasta )
  echo "$fasta, $count"
done >> my_file.csv
```
