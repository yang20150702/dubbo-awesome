# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.655 ops/ms
Iteration   1: 6.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.526 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ops/ms
Iteration   1: 10.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.849 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.515 ops/ms
Iteration   1: 11.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.300 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ops/ms
Iteration   1: 9.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.225 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.847 ±(99.9%) 0.069 ms/op
Iteration   1: 2.341 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.256 ±(99.9%) 0.047 ms/op
Iteration   1: 1.905 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.426 ±(99.9%) 0.068 ms/op
Iteration   1: 1.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.917 ±(99.9%) 0.094 ms/op
Iteration   1: 3.674 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.674 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.099 ms/op
Iteration   1: 2.356 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.058 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.957 ms/op
                 createUser·p0.99:   12.485 ms/op
                 createUser·p0.999:  30.704 ms/op
                 createUser·p0.9999: 30.856 ms/op
                 createUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13558
  mean =      2.356 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11417 
    [ 2.500,  5.000) = 1874 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     30.704 ms/op
     p(99.9900) =     30.856 ms/op
     p(99.9990) =     30.867 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ±(99.9%) 0.079 ms/op
Iteration   1: 1.972 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.358 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.779 ms/op
                 existUser·p0.99:   6.717 ms/op
                 existUser·p0.999:  11.846 ms/op
                 existUser·p0.9999: 14.391 ms/op
                 existUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16531
  mean =      1.972 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 387 
    [ 1.250,  2.500) = 14706 
    [ 2.500,  3.750) = 973 
    [ 3.750,  5.000) = 143 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.358 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.779 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     14.391 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.293 ±(99.9%) 0.109 ms/op
Iteration   1: 1.986 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   1.923 ms/op
                 getUser·p0.90:   2.449 ms/op
                 getUser·p0.95:   2.740 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  11.417 ms/op
                 getUser·p0.9999: 12.109 ms/op
                 getUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16150
  mean =      1.986 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 204 
    [ 1.250,  2.500) = 14621 
    [ 2.500,  3.750) = 1057 
    [ 3.750,  5.000) = 172 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =     11.417 ms/op
     p(99.9900) =     12.109 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.652 ±(99.9%) 0.135 ms/op
Iteration   1: 3.496 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.510 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.361 ms/op
                 listUser·p0.999:  23.626 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9151
  mean =      3.496 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1310 
    [ 2.500,  5.000) = 7533 
    [ 5.000,  7.500) = 276 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.361 ms/op
     p(99.9000) =     23.626 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.526          ops/ms
ClientSimple.existUser                       thrpt         10.849          ops/ms
ClientSimple.getUser                         thrpt         11.300          ops/ms
ClientSimple.listUser                        thrpt          9.225          ops/ms
ClientSimple.createUser                       avgt          2.341           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          1.967           ms/op
ClientSimple.listUser                         avgt          3.674           ms/op
ClientSimple.createUser                     sample  13558   2.356 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.041           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.058           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.957           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.485           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.704           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.856           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.867           ms/op
ClientSimple.existUser                      sample  16531   1.972 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.358           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.779           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.717           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.846           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.391           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.402           ms/op
ClientSimple.getUser                        sample  16150   1.986 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.633           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.923           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.449           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.833           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.417           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.109           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.190           ms/op
ClientSimple.listUser                       sample   9151   3.496 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.993           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.510           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.399           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.361           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.626           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.642           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.642           ms/op

Benchmark result is saved to 1720140066123.json
