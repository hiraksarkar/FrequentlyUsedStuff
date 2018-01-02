## hisat 2 index building 
```
## Bare minimum no additional information for snp, exon etc
## mkdir <ht2-index-folder>
hisat2-build -p <#threads> <reference-file-in> <ht2-index-folder>/ind
# ind is the prefix
#advanced
```
## Salmon inex building
```
## bare minimum
## folder will be created
salmon index -t <transcript> -i <output folder> 

```

## Salmon mapping phase 
```
salmon qaunt 
```

### Important resources
[SAM parsing in shell](http://www4.ncsu.edu/~rosswhet/BIT815/Overview/Week2/SAMformatAndCLtools.pdf)

### Essential C++ library
1. [spdlog](https://github.com/gabime/spdlog/)
2. [cereal](https://uscilab.github.io/cereal/)
3. [more resources](https://github.com/rigtorp/awesome-modern-cpp)


### Tools 
1. [use fastq-dump smartly](https://edwards.sdsu.edu/research/fastq-dump/)