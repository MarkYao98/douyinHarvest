# V2.0

- 2.0（dubbo版本）
- 本项目是对1.0版本的一次升级,具体升级部分在于检索部分(mysql->es)
- 将1.0的各模块进行了拆分。
  - app-admin模块，主要功能为对数据的管理，crud，其中也包含了分析数据的功能。
  - app-harvest，主要功能为对数据的采集。
  - app-show，展示模块，主要是前端代码。
  - commons，公共模块，包含了一系列公共的pojo,接口等。
