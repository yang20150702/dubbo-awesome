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
# Warmup Iteration   1: 1.469 ops/ms
Iteration   1: 5.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.751 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.401 ops/ms
Iteration   1: 12.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.302 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.053 ops/ms
Iteration   1: 11.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.818 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.695 ops/ms
Iteration   1: 7.470 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.470 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.082 ms/op
Iteration   1: 2.343 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.343 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.059 ms/op
Iteration   1: 1.753 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.753 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ±(99.9%) 0.069 ms/op
Iteration   1: 1.957 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.957 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.737 ±(99.9%) 0.084 ms/op
Iteration   1: 3.343 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.343 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.096 ms/op
Iteration   1: 2.172 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.957 ms/op
                 createUser·p0.50:   2.036 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.867 ms/op
                 createUser·p0.99:   5.725 ms/op
                 createUser·p0.999:  15.319 ms/op
                 createUser·p0.9999: 15.817 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14719
  mean =      2.172 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 13025 
    [ 2.500,  3.750) = 1305 
    [ 3.750,  5.000) = 106 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 60 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.957 ms/op
     p(50.0000) =      2.036 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.867 ms/op
     p(99.0000) =      5.725 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     15.817 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.099 ms/op
Iteration   1: 1.861 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.699 ms/op
                 existUser·p0.99:   4.069 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 14.451 ms/op
                 existUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17169
  mean =      1.861 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 815 
    [ 1.250,  2.500) = 14948 
    [ 2.500,  3.750) = 1200 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      4.069 ms/op
     p(99.9000) =     13.779 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.115 ms/op
Iteration   1: 2.170 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   1.919 ms/op
                 getUser·p0.90:   2.867 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   5.748 ms/op
                 getUser·p0.999:  13.586 ms/op
                 getUser·p0.9999: 13.854 ms/op
                 getUser·p1.00:   13.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14765
  mean =      2.170 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 55 
    [ 1.250,  2.500) = 11679 
    [ 2.500,  3.750) = 2750 
    [ 3.750,  5.000) = 111 
    [ 5.000,  6.250) = 53 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      5.748 ms/op
     p(99.9000) =     13.586 ms/op
     p(99.9900) =     13.854 ms/op
     p(99.9990) =     13.877 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


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
# Warmup Iteration   1: 5.026 ±(99.9%) 0.153 ms/op
Iteration   1: 3.765 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   0.632 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.759 ms/op
                 listUser·p0.999:  20.546 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8493
  mean =      3.765 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 556 
    [ 2.500,  5.000) = 7504 
    [ 5.000,  7.500) = 358 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.759 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     21.365 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.751          ops/ms
ClientSimple.existUser                       thrpt         12.302          ops/ms
ClientSimple.getUser                         thrpt         11.818          ops/ms
ClientSimple.listUser                        thrpt          7.470          ops/ms
ClientSimple.createUser                       avgt          2.343           ms/op
ClientSimple.existUser                        avgt          1.753           ms/op
ClientSimple.getUser                          avgt          1.957           ms/op
ClientSimple.listUser                         avgt          3.343           ms/op
ClientSimple.createUser                     sample  14719   2.172 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.957           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.036           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.725           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.319           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.817           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.056           ms/op
ClientSimple.existUser                      sample  17169   1.861 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.699           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.700           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.699           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.069           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.779           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.991           ms/op
ClientSimple.getUser                        sample  14765   2.170 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.032           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.919           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.867           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.142           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.748           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.586           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.854           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.877           ms/op
ClientSimple.listUser                       sample   8493   3.765 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.632           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.682           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.596           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.038           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.759           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.546           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.365           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.365           ms/op

Benchmark result is saved to 1711087876718.json
