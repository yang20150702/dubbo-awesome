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
# Warmup Iteration   1: 1.152 ops/ms
Iteration   1: 5.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.612 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.154 ops/ms
Iteration   1: 13.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.823 ops/ms


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
# Warmup Iteration   1: 7.085 ops/ms
Iteration   1: 14.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.108 ops/ms


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
# Warmup Iteration   1: 4.496 ops/ms
Iteration   1: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.877 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.061 ms/op
Iteration   1: 2.292 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.292 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ±(99.9%) 0.057 ms/op
Iteration   1: 1.935 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.935 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.399 ±(99.9%) 0.056 ms/op
Iteration   1: 2.309 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.309 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.114 ms/op
Iteration   1: 3.098 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.098 ms/op


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.148 ms/op
Iteration   1: 2.212 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   2.021 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.961 ms/op
                 createUser·p0.99:   10.889 ms/op
                 createUser·p0.999:  18.103 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14536
  mean =      2.212 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12379 
    [ 2.500,  5.000) = 1834 
    [ 5.000,  7.500) = 128 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.021 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =     10.889 ms/op
     p(99.9000) =     18.103 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.315 ms/op
    p(100.0000) =     22.315 ms/op


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
# Warmup Iteration   1: 3.267 ±(99.9%) 0.079 ms/op
Iteration   1: 1.767 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.517 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   2.896 ms/op
                 existUser·p0.999:  12.909 ms/op
                 existUser·p0.9999: 13.234 ms/op
                 existUser·p1.00:   13.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18102
  mean =      1.767 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 351 
    [ 1.250,  2.500) = 17047 
    [ 2.500,  3.750) = 643 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.517 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      2.896 ms/op
     p(99.9000) =     12.909 ms/op
     p(99.9900) =     13.234 ms/op
     p(99.9990) =     13.287 ms/op
     p(99.9999) =     13.287 ms/op
    p(100.0000) =     13.287 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.086 ms/op
Iteration   1: 2.118 ±(99.9%) 0.062 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   1.942 ms/op
                 getUser·p0.90:   2.567 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   5.033 ms/op
                 getUser·p0.999:  55.181 ms/op
                 getUser·p0.9999: 56.949 ms/op
                 getUser·p1.00:   57.016 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15163
  mean =      2.118 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15004 
    [ 5.000, 10.000) = 83 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.567 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      5.033 ms/op
     p(99.9000) =     55.181 ms/op
     p(99.9900) =     56.949 ms/op
     p(99.9990) =     57.016 ms/op
     p(99.9999) =     57.016 ms/op
    p(100.0000) =     57.016 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.151 ms/op
Iteration   1: 3.343 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.862 ms/op
                 listUser·p0.50:   3.338 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.200 ms/op
                 listUser·p0.999:  11.911 ms/op
                 listUser·p0.9999: 12.009 ms/op
                 listUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9610
  mean =      3.343 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 1396 
    [ 2.500,  3.750) = 5957 
    [ 3.750,  5.000) = 1959 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.200 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     12.009 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.612          ops/ms
ClientSimple.existUser                       thrpt         13.823          ops/ms
ClientSimple.getUser                         thrpt         14.108          ops/ms
ClientSimple.listUser                        thrpt          7.877          ops/ms
ClientSimple.createUser                       avgt          2.292           ms/op
ClientSimple.existUser                        avgt          1.935           ms/op
ClientSimple.getUser                          avgt          2.309           ms/op
ClientSimple.listUser                         avgt          3.098           ms/op
ClientSimple.createUser                     sample  14536   2.212 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.513           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.021           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.961           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.889           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.103           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.315           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.315           ms/op
ClientSimple.existUser                      sample  18102   1.767 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.517           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.896           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.909           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.234           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.287           ms/op
ClientSimple.getUser                        sample  15163   2.118 ± 0.062   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.555           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.942           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.567           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.033           ms/op
ClientSimple.getUser:getUser·p0.999         sample         55.181           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         56.949           ms/op
ClientSimple.getUser:getUser·p1.00          sample         57.016           ms/op
ClientSimple.listUser                       sample   9610   3.343 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.862           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.338           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.096           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.200           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.911           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.009           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.009           ms/op

Benchmark result is saved to 1710549322992.json
