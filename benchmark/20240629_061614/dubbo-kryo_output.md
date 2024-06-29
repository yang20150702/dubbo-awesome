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
# Warmup Iteration   1: 1.873 ops/ms
Iteration   1: 6.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.270 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.541 ops/ms
Iteration   1: 12.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.478 ops/ms


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
# Warmup Iteration   1: 5.241 ops/ms
Iteration   1: 12.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.687 ops/ms


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
# Warmup Iteration   1: 5.029 ops/ms
Iteration   1: 9.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.410 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.817 ±(99.9%) 0.072 ms/op
Iteration   1: 2.237 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.237 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.046 ±(99.9%) 0.043 ms/op
Iteration   1: 1.970 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.970 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.239 ±(99.9%) 0.062 ms/op
Iteration   1: 2.237 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.237 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.245 ±(99.9%) 0.081 ms/op
Iteration   1: 3.257 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.257 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.417 ±(99.9%) 0.081 ms/op
Iteration   1: 2.397 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.842 ms/op
                 createUser·p0.50:   2.232 ms/op
                 createUser·p0.90:   2.720 ms/op
                 createUser·p0.95:   3.043 ms/op
                 createUser·p0.99:   5.742 ms/op
                 createUser·p0.999:  38.666 ms/op
                 createUser·p0.9999: 39.037 ms/op
                 createUser·p1.00:   39.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13351
  mean =      2.397 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10294 
    [ 2.500,  5.000) = 2882 
    [ 5.000,  7.500) = 111 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      2.232 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      3.043 ms/op
     p(99.0000) =      5.742 ms/op
     p(99.9000) =     38.666 ms/op
     p(99.9900) =     39.037 ms/op
     p(99.9990) =     39.059 ms/op
     p(99.9999) =     39.059 ms/op
    p(100.0000) =     39.059 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.935 ±(99.9%) 0.076 ms/op
Iteration   1: 1.851 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  38.339 ms/op
                 existUser·p0.9999: 38.749 ms/op
                 existUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17372
  mean =      1.851 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16627 
    [ 2.500,  5.000) = 648 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     38.339 ms/op
     p(99.9900) =     38.749 ms/op
     p(99.9990) =     38.797 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.079 ms/op
Iteration   1: 1.819 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   1.747 ms/op
                 getUser·p0.90:   2.200 ms/op
                 getUser·p0.95:   2.408 ms/op
                 getUser·p0.99:   2.870 ms/op
                 getUser·p0.999:  5.358 ms/op
                 getUser·p0.9999: 5.646 ms/op
                 getUser·p1.00:   6.177 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17627
  mean =      1.819 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 42 
    [1.000, 1.500) = 1413 
    [1.500, 2.000) = 12711 
    [2.000, 2.500) = 2925 
    [2.500, 3.000) = 392 
    [3.000, 3.500) = 43 
    [3.500, 4.000) = 10 
    [4.000, 4.500) = 7 
    [4.500, 5.000) = 41 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.408 ms/op
     p(99.0000) =      2.870 ms/op
     p(99.9000) =      5.358 ms/op
     p(99.9900) =      5.646 ms/op
     p(99.9990) =      6.177 ms/op
     p(99.9999) =      6.177 ms/op
    p(100.0000) =      6.177 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.129 ms/op
Iteration   1: 3.111 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   2.843 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.154 ms/op
                 listUser·p0.999:  16.232 ms/op
                 listUser·p0.9999: 22.815 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10283
  mean =      3.111 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1250 
    [ 2.500,  5.000) = 8850 
    [ 5.000,  7.500) = 147 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      2.843 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.154 ms/op
     p(99.9000) =     16.232 ms/op
     p(99.9900) =     22.815 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.270          ops/ms
ClientSimple.existUser                       thrpt         12.478          ops/ms
ClientSimple.getUser                         thrpt         12.687          ops/ms
ClientSimple.listUser                        thrpt          9.410          ops/ms
ClientSimple.createUser                       avgt          2.237           ms/op
ClientSimple.existUser                        avgt          1.970           ms/op
ClientSimple.getUser                          avgt          2.237           ms/op
ClientSimple.listUser                         avgt          3.257           ms/op
ClientSimple.createUser                     sample  13351   2.397 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.842           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.232           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.742           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.666           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         39.037           ms/op
ClientSimple.createUser:createUser·p1.00    sample         39.059           ms/op
ClientSimple.existUser                      sample  17372   1.851 ± 0.044   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.587           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.696           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.293           ms/op
ClientSimple.existUser:existUser·p0.999     sample         38.339           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         38.749           ms/op
ClientSimple.existUser:existUser·p1.00      sample         38.797           ms/op
ClientSimple.getUser                        sample  17627   1.819 ± 0.009   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.702           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.747           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.200           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.408           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.870           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.358           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          5.646           ms/op
ClientSimple.getUser:getUser·p1.00          sample          6.177           ms/op
ClientSimple.listUser                       sample  10283   3.111 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.233           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.843           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.154           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.232           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.815           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.872           ms/op

Benchmark result is saved to 1719641521574.json
