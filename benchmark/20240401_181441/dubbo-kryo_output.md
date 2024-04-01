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
# Warmup Iteration   1: 1.740 ops/ms
Iteration   1: 6.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.677 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.767 ops/ms
Iteration   1: 12.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.285 ops/ms


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
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 11.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.779 ops/ms


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
# Warmup Iteration   1: 5.538 ops/ms
Iteration   1: 8.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.700 ops/ms


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.065 ms/op
Iteration   1: 2.406 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.406 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.050 ms/op
Iteration   1: 1.746 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.746 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.057 ms/op
Iteration   1: 1.963 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.963 ms/op


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
# Warmup Iteration   1: 4.953 ±(99.9%) 0.114 ms/op
Iteration   1: 3.787 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.787 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.138 ms/op
Iteration   1: 2.298 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   2.052 ms/op
                 createUser·p0.90:   2.679 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   12.040 ms/op
                 createUser·p0.999:  20.421 ms/op
                 createUser·p0.9999: 23.220 ms/op
                 createUser·p1.00:   23.233 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13905
  mean =      2.298 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11620 
    [ 2.500,  5.000) = 1966 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.052 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =     12.040 ms/op
     p(99.9000) =     20.421 ms/op
     p(99.9900) =     23.220 ms/op
     p(99.9990) =     23.233 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.061 ±(99.9%) 0.071 ms/op
Iteration   1: 1.656 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   1.491 ms/op
                 existUser·p0.90:   2.105 ms/op
                 existUser·p0.95:   2.261 ms/op
                 existUser·p0.99:   2.675 ms/op
                 existUser·p0.999:  27.483 ms/op
                 existUser·p0.9999: 27.691 ms/op
                 existUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19295
  mean =      1.656 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19021 
    [ 2.500,  5.000) = 204 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.491 ms/op
     p(90.0000) =      2.105 ms/op
     p(95.0000) =      2.261 ms/op
     p(99.0000) =      2.675 ms/op
     p(99.9000) =     27.483 ms/op
     p(99.9900) =     27.691 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.077 ms/op
Iteration   1: 1.896 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   1.782 ms/op
                 getUser·p0.90:   2.286 ms/op
                 getUser·p0.95:   2.503 ms/op
                 getUser·p0.99:   3.142 ms/op
                 getUser·p0.999:  17.327 ms/op
                 getUser·p0.9999: 18.000 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16903
  mean =      1.896 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 15989 
    [ 2.500,  3.750) = 759 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      3.142 ms/op
     p(99.9000) =     17.327 ms/op
     p(99.9900) =     18.000 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 4.694 ±(99.9%) 0.136 ms/op
Iteration   1: 3.645 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.682 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.648 ms/op
                 listUser·p0.99:   5.430 ms/op
                 listUser·p0.999:  6.337 ms/op
                 listUser·p0.9999: 10.273 ms/op
                 listUser·p1.00:   10.273 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8772
  mean =      3.645 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 170 
    [ 2.000,  3.000) = 1232 
    [ 3.000,  4.000) = 4904 
    [ 4.000,  5.000) = 2211 
    [ 5.000,  6.000) = 228 
    [ 6.000,  7.000) = 23 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.648 ms/op
     p(99.0000) =      5.430 ms/op
     p(99.9000) =      6.337 ms/op
     p(99.9900) =     10.273 ms/op
     p(99.9990) =     10.273 ms/op
     p(99.9999) =     10.273 ms/op
    p(100.0000) =     10.273 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.677          ops/ms
ClientSimple.existUser                       thrpt         12.285          ops/ms
ClientSimple.getUser                         thrpt         11.779          ops/ms
ClientSimple.listUser                        thrpt          8.700          ops/ms
ClientSimple.createUser                       avgt          2.406           ms/op
ClientSimple.existUser                        avgt          1.746           ms/op
ClientSimple.getUser                          avgt          1.963           ms/op
ClientSimple.listUser                         avgt          3.787           ms/op
ClientSimple.createUser                     sample  13905   2.298 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.552           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.052           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.040           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.421           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.220           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.233           ms/op
ClientSimple.existUser                      sample  19295   1.656 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.807           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.491           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.105           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.483           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.691           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.722           ms/op
ClientSimple.getUser                        sample  16903   1.896 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.603           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.782           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.286           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.142           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.327           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.000           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.022           ms/op
ClientSimple.listUser                       sample   8772   3.645 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.682           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.719           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.648           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.430           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.337           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.273           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.273           ms/op

Benchmark result is saved to 1711995026808.json
