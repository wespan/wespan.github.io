# wespan

## Begin

1.Install hexo

```bash
npm i -g hexo-cli
```

2.clone the project

```bash
git clone git@github.com:wespan/wespan.github.io.git wespan
```

3.init submodules

```bash
cd wespan
git submodule init
git submodule update

# change to themes/wespan,checkout the branch of master
cd themes/wespan
git checkout master
```

4.install the dependencies

```bash
# change to the root
cd ../../
npm i
```

5.preview the site

```bash
hexo s --watch
```

> [http://localhost:4000](http://localhost:4000)