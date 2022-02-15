# QE-ParallelElph
Patch to parallelize electron-phonon coupling calculation in Quantum Espresso software (v6.3)

## Applying patch
Go into the 'PHonon/PH' directory in the QE folder and apply the following command
```
patch -u elphon.f90 -i QE6.3_pElph.patch
```

## Disclaimer
There is no guarantee that this patch will work with other versions of QE!
