## 阿里B版项目目录结构

### alidw-fe

- data                -->菜单数据。
- mock                -->mock数据。
    - auth  --> 安全认证信息
    - campaign  --> 主动营销数据
    - customer-hive --> 客户分群数据
    - dashboard  --> 主页数据
    - event-service  --> 事件关怀数据
    - goods-selector   --> 淘宝商品数据
    - interacts   -->互动中心数据
    - loyalty     -->忠诚度管理数据
    - sms    --> 短信相关数据
    - db.json
- src                 -->项目源码。
- .babelrc            -->Babel的配置文件，来设置转码规则和插件。
- .editorconfig       --> 配置编辑器保持一样的风格
- .eslintignore       -->忽略某些文件或目录
- .eslintrc.yml       -->设置eslint的规则
- .gitignore          -->告诉Git哪些文件不需要添加到版本管理中
- package.json        -->定义了项目的配置信息及所依赖的各种模块，npm install 命令根据这个配置文件，自动下载所需的模块
- package-lock.json   -->npm升级后生成的文件
- server.js            -->配置服务
- webpack-build.config.js      -->配置服务
- webpack-common.config.js     -->配置服务
- webpack-dev.config.js        -->配置服务
  
