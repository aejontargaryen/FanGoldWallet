<h1 align="center"><img title="The Long Night Is Coming" src="https://raw.githubusercontent.com/ZirtysPerzys/DRGL-wallet/master/src/images/splash.png" width="1800" height="500" ><img/></h1>

Binaries are made available by community members. If you are able to compile on your operating system, please consider helping others by adding to the release. Also if your OS is available, please consider donating to the community member who made it possible. 

**1. Clone wallet sources**

```
git clone https://github.com/zirtysperzys/draegonglasswallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`. For example:**

```
ln -s ../DRGL cryptonote
```

Alternative way is to create git submodule:

```
git submodule add https://github.com/zirtysperzys/DRGL.git cryptonote
```

**3. Build**

```
mkdir build && cd build && cmake .. && make
```
