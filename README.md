#nTupler

##Source and Installation

First, edit the content of  `mkLinks` according to the Delphes version and its path.

```
ln -s ../Delphes-3.0.10/external/ExRootAnalysis .
ln -s ../Delphes-3.0.10/classes .
ln -s ../Data .
cd Batch
ln -s ../nTupler .
cd -
```

Then run `mkLinks`.

```
./mkLinks
```

After the linking process is complete, compile with

```
make
```

