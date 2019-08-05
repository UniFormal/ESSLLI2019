This was caused by the MMT setup cloning the `master` branch of the repository `urtheories`, which defines the meta-logic we are using.
We needed the `devel` branch instead.

Fresh installs do not have the problem anymore.

To fix old installs, simply do the following
```
cd MMT-content/MMT/urtheories
git checkout devel
```
