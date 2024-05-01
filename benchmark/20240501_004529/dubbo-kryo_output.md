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
# Warmup Iteration   1: 2.218 ops/ms
Iteration   1: 8.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.018 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.756 ops/ms
Iteration   1: 12.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.756 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.462 ops/ms
Iteration   1: 13.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.626 ops/ms


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
# Warmup Iteration   1: 5.874 ops/ms
Iteration   1: 8.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.935 ops/ms


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.068 ms/op
Iteration   1: 2.027 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.027 ms/op


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
# Warmup Iteration   1: 2.723 ±(99.9%) 0.046 ms/op
Iteration   1: 1.854 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.854 ms/op


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
# Warmup Iteration   1: 3.227 ±(99.9%) 0.060 ms/op
Iteration   1: 1.979 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.979 ms/op


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
# Warmup Iteration   1: 6.080 ±(99.9%) 0.099 ms/op
Iteration   1: 3.670 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.670 ms/op


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.083 ms/op
Iteration   1: 2.535 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.339 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.400 ms/op
                 createUser·p0.99:   10.060 ms/op
                 createUser·p0.999:  13.713 ms/op
                 createUser·p0.9999: 15.761 ms/op
                 createUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12701
  mean =      2.535 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 7393 
    [ 2.500,  3.750) = 4764 
    [ 3.750,  5.000) = 160 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.339 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.400 ms/op
     p(99.0000) =     10.060 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     16.089 ms/op
     p(99.9999) =     16.089 ms/op
    p(100.0000) =     16.089 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.071 ms/op
Iteration   1: 2.058 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.345 ms/op
                 existUser·p0.50:   1.923 ms/op
                 existUser·p0.90:   2.556 ms/op
                 existUser·p0.95:   2.855 ms/op
                 existUser·p0.99:   5.584 ms/op
                 existUser·p0.999:  25.231 ms/op
                 existUser·p0.9999: 26.065 ms/op
                 existUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15540
  mean =      2.058 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13674 
    [ 2.500,  5.000) = 1668 
    [ 5.000,  7.500) = 134 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      1.923 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.584 ms/op
     p(99.9000) =     25.231 ms/op
     p(99.9900) =     26.065 ms/op
     p(99.9990) =     26.083 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 3.195 ±(99.9%) 0.086 ms/op
Iteration   1: 1.821 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   1.735 ms/op
                 getUser·p0.90:   2.208 ms/op
                 getUser·p0.95:   2.388 ms/op
                 getUser·p0.99:   2.879 ms/op
                 getUser·p0.999:  14.442 ms/op
                 getUser·p0.9999: 14.696 ms/op
                 getUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17559
  mean =      1.821 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 392 
    [ 1.250,  2.500) = 16627 
    [ 2.500,  3.750) = 469 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 11 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      2.879 ms/op
     p(99.9000) =     14.442 ms/op
     p(99.9900) =     14.696 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.148 ms/op
Iteration   1: 3.169 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.423 ms/op
                 listUser·p0.999:  5.980 ms/op
                 listUser·p0.9999: 6.562 ms/op
                 listUser·p1.00:   6.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10097
  mean =      3.169 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 134 
    [2.000, 2.500) = 863 
    [2.500, 3.000) = 4229 
    [3.000, 3.500) = 1783 
    [3.500, 4.000) = 1860 
    [4.000, 4.500) = 896 
    [4.500, 5.000) = 132 
    [5.000, 5.500) = 96 
    [5.500, 6.000) = 80 
    [6.000, 6.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      5.980 ms/op
     p(99.9900) =      6.562 ms/op
     p(99.9990) =      6.562 ms/op
     p(99.9999) =      6.562 ms/op
    p(100.0000) =      6.562 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.018          ops/ms
ClientSimple.existUser                       thrpt         12.756          ops/ms
ClientSimple.getUser                         thrpt         13.626          ops/ms
ClientSimple.listUser                        thrpt          8.935          ops/ms
ClientSimple.createUser                       avgt          2.027           ms/op
ClientSimple.existUser                        avgt          1.854           ms/op
ClientSimple.getUser                          avgt          1.979           ms/op
ClientSimple.listUser                         avgt          3.670           ms/op
ClientSimple.createUser                     sample  12701   2.535 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.829           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.339           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.400           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.060           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.713           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.761           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.089           ms/op
ClientSimple.existUser                      sample  15540   2.058 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.345           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.923           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.556           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.584           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.231           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.065           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.083           ms/op
ClientSimple.getUser                        sample  17559   1.821 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.720           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.735           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.208           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.388           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.879           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.442           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.696           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.696           ms/op
ClientSimple.listUser                       sample  10097   3.169 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.051           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.423           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.980           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.562           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.562           ms/op

Benchmark result is saved to 1714524078896.json
