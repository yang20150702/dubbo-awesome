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
# Warmup Iteration   1: 1.561 ops/ms
Iteration   1: 6.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.666 ops/ms


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
# Warmup Iteration   1: 6.021 ops/ms
Iteration   1: 11.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.102 ops/ms


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
# Warmup Iteration   1: 5.375 ops/ms
Iteration   1: 12.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.442 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.407 ops/ms
Iteration   1: 8.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.517 ops/ms


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.099 ms/op
Iteration   1: 2.265 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.265 ms/op


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
# Warmup Iteration   1: 3.631 ±(99.9%) 0.073 ms/op
Iteration   1: 2.105 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.105 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.062 ms/op
Iteration   1: 2.181 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.181 ms/op


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
# Warmup Iteration   1: 4.866 ±(99.9%) 0.102 ms/op
Iteration   1: 3.870 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.870 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.096 ms/op
Iteration   1: 2.210 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   1.913 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   3.044 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  19.038 ms/op
                 createUser·p0.9999: 20.458 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14474
  mean =      2.210 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12897 
    [ 2.500,  5.000) = 1154 
    [ 5.000,  7.500) = 226 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      3.044 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     19.038 ms/op
     p(99.9900) =     20.458 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.066 ms/op
Iteration   1: 2.087 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   1.985 ms/op
                 existUser·p0.90:   2.626 ms/op
                 existUser·p0.95:   2.839 ms/op
                 existUser·p0.99:   4.932 ms/op
                 existUser·p0.999:  10.650 ms/op
                 existUser·p0.9999: 11.564 ms/op
                 existUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15426
  mean =      2.087 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 220 
    [ 1.250,  2.500) = 13037 
    [ 2.500,  3.750) = 1915 
    [ 3.750,  5.000) = 132 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     10.650 ms/op
     p(99.9900) =     11.564 ms/op
     p(99.9990) =     11.600 ms/op
     p(99.9999) =     11.600 ms/op
    p(100.0000) =     11.600 ms/op


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.091 ms/op
Iteration   1: 2.057 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.574 ms/op
                 getUser·p0.50:   1.987 ms/op
                 getUser·p0.90:   2.556 ms/op
                 getUser·p0.95:   2.765 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 19.260 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15546
  mean =      2.057 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 267 
    [ 1.250,  2.500) = 13392 
    [ 2.500,  3.750) = 1741 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     19.260 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.139 ms/op
Iteration   1: 3.907 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.052 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  16.516 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8304
  mean =      3.907 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 457 
    [ 2.500,  3.750) = 2716 
    [ 3.750,  5.000) = 4701 
    [ 5.000,  6.250) = 342 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      3.949 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.052 ms/op
     p(99.0000) =      6.267 ms/op
     p(99.9000) =     16.516 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.666          ops/ms
ClientSimple.existUser                       thrpt         11.102          ops/ms
ClientSimple.getUser                         thrpt         12.442          ops/ms
ClientSimple.listUser                        thrpt          8.517          ops/ms
ClientSimple.createUser                       avgt          2.265           ms/op
ClientSimple.existUser                        avgt          2.105           ms/op
ClientSimple.getUser                          avgt          2.181           ms/op
ClientSimple.listUser                         avgt          3.870           ms/op
ClientSimple.createUser                     sample  14474   2.210 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.913           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.044           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.059           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.038           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.458           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.546           ms/op
ClientSimple.existUser                      sample  15426   2.087 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.473           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.985           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.932           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.650           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.564           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.600           ms/op
ClientSimple.getUser                        sample  15546   2.057 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.574           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.987           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.731           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.547           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.260           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.333           ms/op
ClientSimple.listUser                       sample   8304   3.907 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.190           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.949           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.052           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.267           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.516           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.547           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.547           ms/op

Benchmark result is saved to 1720462455478.json
