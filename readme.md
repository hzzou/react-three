### 记录

* IntersectionObserver做进入视口监控
* /car 是运动的轿车，ThreeJS框架实现
* /olympic 是react-three-fibers实现冰墩墩
* /star 是react-three-fiber实现运动的轿车
* /lazy-img 原生懒加载图片实现
* /house 是react-three-fiber实现3D看房
* /china 是react-three-fiber实现3D中国地图

### 静态部署配置


* Failed to load module script,是文件路径不对
* 因为gitpages的静态部署文件夹是某分支(比如master分支)下不是root文件夹就是docs文件夹，所以得把打包目录名称改为docs
* 部署到github Pages时，直接修改base配置会影响相关路径的引用，所以可以在打包之后修改index.html里面文件的引用路径(加上仓库绝对路径/react-three-fiber-demo/)
