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
# Warmup Iteration   1: 1.406 ops/ms
Iteration   1: 6.765 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.765 ops/ms


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
# Warmup Iteration   1: 5.019 ops/ms
Iteration   1: 11.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.398 ops/ms


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
# Warmup Iteration   1: 4.829 ops/ms
Iteration   1: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.740 ops/ms


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
# Warmup Iteration   1: 3.947 ops/ms
Iteration   1: 7.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.760 ops/ms


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
# Warmup Iteration   1: 4.230 ±(99.9%) 0.073 ms/op
Iteration   1: 2.207 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.207 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.056 ms/op
Iteration   1: 2.006 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.006 ms/op


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
# Warmup Iteration   1: 3.100 ±(99.9%) 0.053 ms/op
Iteration   1: 1.985 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.985 ms/op


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
# Warmup Iteration   1: 5.300 ±(99.9%) 0.101 ms/op
Iteration   1: 3.623 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.623 ms/op


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
# Warmup Iteration   1: 4.254 ±(99.9%) 0.210 ms/op
Iteration   1: 2.276 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.175 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.716 ms/op
                 createUser·p0.999:  14.156 ms/op
                 createUser·p0.9999: 14.333 ms/op
                 createUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14036
  mean =      2.276 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 9823 
    [ 2.500,  3.750) = 3804 
    [ 3.750,  5.000) = 189 
    [ 5.000,  6.250) = 60 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.716 ms/op
     p(99.9000) =     14.156 ms/op
     p(99.9900) =     14.333 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.324 ±(99.9%) 0.098 ms/op
Iteration   1: 2.007 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.494 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  10.826 ms/op
                 existUser·p0.9999: 12.131 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15939
  mean =      2.007 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 14201 
    [ 2.500,  3.750) = 1279 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.826 ms/op
     p(99.9900) =     12.131 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


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
# Warmup Iteration   1: 3.426 ±(99.9%) 0.088 ms/op
Iteration   1: 2.203 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   2.079 ms/op
                 getUser·p0.90:   2.723 ms/op
                 getUser·p0.95:   2.961 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  15.254 ms/op
                 getUser·p0.9999: 15.462 ms/op
                 getUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14512
  mean =      2.203 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 11397 
    [ 2.500,  3.750) = 2810 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.079 ms/op
     p(90.0000) =      2.723 ms/op
     p(95.0000) =      2.961 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     15.462 ms/op
     p(99.9990) =     15.499 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.136 ms/op
Iteration   1: 3.873 ±(99.9%) 0.173 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.518 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.863 ms/op
                 listUser·p0.99:   9.463 ms/op
                 listUser·p0.999:  88.707 ms/op
                 listUser·p0.9999: 96.076 ms/op
                 listUser·p1.00:   96.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8246
  mean =      3.873 ±(99.9%) 0.173 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 8192 
    [ 10.000,  20.000) = 4 
    [ 20.000,  30.000) = 6 
    [ 30.000,  40.000) = 7 
    [ 40.000,  50.000) = 5 
    [ 50.000,  60.000) = 6 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 4 
    [ 80.000,  90.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.863 ms/op
     p(99.0000) =      9.463 ms/op
     p(99.9000) =     88.707 ms/op
     p(99.9900) =     96.076 ms/op
     p(99.9990) =     96.076 ms/op
     p(99.9999) =     96.076 ms/op
    p(100.0000) =     96.076 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.765          ops/ms
ClientSimple.existUser                       thrpt         11.398          ops/ms
ClientSimple.getUser                         thrpt         12.740          ops/ms
ClientSimple.listUser                        thrpt          7.760          ops/ms
ClientSimple.createUser                       avgt          2.207           ms/op
ClientSimple.existUser                        avgt          2.006           ms/op
ClientSimple.getUser                          avgt          1.985           ms/op
ClientSimple.listUser                         avgt          3.623           ms/op
ClientSimple.createUser                     sample  14036   2.276 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.546           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.175           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.252           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.716           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.156           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.333           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.352           ms/op
ClientSimple.existUser                      sample  15939   2.007 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.632           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.898           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.440           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.826           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.131           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.141           ms/op
ClientSimple.getUser                        sample  14512   2.203 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.079           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.723           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.961           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.096           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.254           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.462           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.499           ms/op
ClientSimple.listUser                       sample   8246   3.873 ± 0.173   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.210           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.518           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.863           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.463           ms/op
ClientSimple.listUser:listUser·p0.999       sample         88.707           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         96.076           ms/op
ClientSimple.listUser:listUser·p1.00        sample         96.076           ms/op

Benchmark result is saved to 1712729508202.json
