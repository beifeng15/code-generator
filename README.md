### 使用步骤

1. 拉取代码

```
git clone https://github.com/beifeng15/code-generator.git
```

1. 设计数据表，并在application.properties 中配置好数据库连接信息
2. 运行Code Generator

```
run com.cenyol.mybatisplus.CodeGenerator.main();
```

1. 配置 mapper interface 路径

```
com.cenyol.mybatisplus.common.config.MybatisPlusConfig
@MapperScan
```

1. 运行 spring boot，打开 postman 查看运行效果

### 使用建议

1. 在运行 coder generator 之前，修改包名为你自己的，可以通过 idea 来一键修改，手动修改也行，没几个文件。

```
com.cenyol.mybatisplus -> com.yours.domain
```

原来Git项目地址

https://github.com/Cenyol/SpringMVC

