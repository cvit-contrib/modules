# modules

Minor package management on ada

This repository maintains the list of modules files installed by user
contributions.

## Setup

Clone this as a `privatemodules` directory in your home folder.

```
git clone https://github.com/cvit-contrib/modules ~/privatemodules
```

Using:

```
module load use.own
module load <your-module>
```

To check what modules are available

 ```
 module avail
```

Eg:
Loading  fairseq 
```
module load use.own
module load python/3.7.0
module load pytorch/fairseq/0.7.2
```


