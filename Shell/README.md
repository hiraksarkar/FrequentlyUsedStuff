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

```
salmon qaunt 
```

### Important resources
[SAM parsing in shell](http://www4.ncsu.edu/~rosswhet/BIT815/Overview/Week2/SAMformatAndCLtools.pdf)

### Essential C++ library
1. [spdlog](https://github.com/gabime/spdlog/)
2. [more resources](https://github.com/rigtorp/awesome-modern-cpp)