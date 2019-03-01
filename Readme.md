## Startup

### install tools
```text
1. install rust and cargo 
2. cargo install cargo-bullet 
3. cargo bullet install --name=bullet-spring-java 
```

### generate project 
```text
1. cargo bullet create --name=bullet-spring-java
2. cargo bullet build --name=bullet-spring-java -output=.
```

### component
```text
1. spring boot
2. jooq
```

### known problem (HELP WANTED!)
```text
1. do not set group or project as hyphen-style, because it will used as package path
2. default use h2-mem as database, you should setup database when you switch to mysql
```

### basic benchmark
```text
test environment: DELL XPS 13
CPU: Inter i5-8250 @ 1.60GHz
MEM: 8.00GB
DISK: SSD
```
```text
bootstrap time: 14s (just so so)
memory: about 230MB (spring boot is not lightweight any more)
```