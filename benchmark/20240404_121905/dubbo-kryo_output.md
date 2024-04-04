# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 7.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.769 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.376 ops/ms
Iteration   1: 12.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.558 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.813 ops/ms
Iteration   1: 13.828 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.828 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.504 ops/ms
Iteration   1: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.924 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.777 ±(99.9%) 0.075 ms/op
Iteration   1: 2.049 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.049 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ±(99.9%) 0.044 ms/op
Iteration   1: 1.910 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ±(99.9%) 0.054 ms/op
Iteration   1: 2.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.600 ±(99.9%) 0.084 ms/op
Iteration   1: 3.637 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.637 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.597 ±(99.9%) 0.105 ms/op
Iteration   1: 2.299 ±(99.9%) 0.052 ms/op
                 createUser·p0.00:   0.449 ms/op
                 createUser·p0.50:   2.046 ms/op
                 createUser·p0.90:   2.619 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  26.512 ms/op
                 createUser·p0.9999: 38.655 ms/op
                 createUser·p1.00:   38.732 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13905
  mean =      2.299 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11920 
    [ 2.500,  5.000) = 1502 
    [ 5.000,  7.500) = 195 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 15 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.449 ms/op
     p(50.0000) =      2.046 ms/op
     p(90.0000) =      2.619 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =     10.912 ms/op
     p(99.9000) =     26.512 ms/op
     p(99.9900) =     38.655 ms/op
     p(99.9990) =     38.732 ms/op
     p(99.9999) =     38.732 ms/op
    p(100.0000) =     38.732 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.959 ±(99.9%) 0.069 ms/op
Iteration   1: 1.711 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   1.591 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.339 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  14.389 ms/op
                 existUser·p0.9999: 15.022 ms/op
                 existUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18748
  mean =      1.711 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1273 
    [ 1.250,  2.500) = 16902 
    [ 2.500,  3.750) = 395 
    [ 3.750,  5.000) = 68 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.591 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.339 ms/op
     p(99.0000) =      3.502 ms/op
     p(99.9000) =     14.389 ms/op
     p(99.9900) =     15.022 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.365 ±(99.9%) 0.084 ms/op
Iteration   1: 2.173 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.005 ms/op
                 getUser·p0.90:   2.847 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   4.138 ms/op
                 getUser·p0.999:  18.809 ms/op
                 getUser·p0.9999: 18.995 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14722
  mean =      2.173 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 11388 
    [ 2.500,  3.750) = 3110 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.847 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      4.138 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     18.995 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.412 ±(99.9%) 0.133 ms/op
Iteration   1: 3.277 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.039 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  6.504 ms/op
                 listUser·p0.9999: 8.765 ms/op
                 listUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9749
  mean =      3.277 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 30 
    [2.000, 2.500) = 799 
    [2.500, 3.000) = 3080 
    [3.000, 3.500) = 2203 
    [3.500, 4.000) = 2537 
    [4.000, 4.500) = 734 
    [4.500, 5.000) = 111 
    [5.000, 5.500) = 74 
    [5.500, 6.000) = 64 
    [6.000, 6.500) = 97 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =      8.765 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.769          ops/ms
ClientSimple.existUser                       thrpt         12.558          ops/ms
ClientSimple.getUser                         thrpt         13.828          ops/ms
ClientSimple.listUser                        thrpt          8.924          ops/ms
ClientSimple.createUser                       avgt          2.049           ms/op
ClientSimple.existUser                        avgt          1.910           ms/op
ClientSimple.getUser                          avgt          2.034           ms/op
ClientSimple.listUser                         avgt          3.637           ms/op
ClientSimple.createUser                     sample  13905   2.299 ± 0.052   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.449           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.046           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.619           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.912           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.512           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.655           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.732           ms/op
ClientSimple.existUser                      sample  18748   1.711 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.562           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.591           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.502           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.389           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.022           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.237           ms/op
ClientSimple.getUser                        sample  14722   2.173 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.727           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.005           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.847           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.138           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.809           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.995           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.104           ms/op
ClientSimple.listUser                       sample   9749   3.277 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.180           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.039           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.243           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.504           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.765           ms/op

Benchmark result is saved to 1712232916075.json
