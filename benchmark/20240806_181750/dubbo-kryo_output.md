# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.179 ops/ms
Iteration   1: 6.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.919 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.914 ops/ms
Iteration   1: 13.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.333 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.805 ops/ms
Iteration   1: 12.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.197 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ops/ms
Iteration   1: 8.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.122 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.099 ms/op
Iteration   1: 2.318 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.318 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ±(99.9%) 0.053 ms/op
Iteration   1: 1.840 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.840 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.405 ±(99.9%) 0.054 ms/op
Iteration   1: 2.434 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.108 ms/op
Iteration   1: 3.449 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.449 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.781 ±(99.9%) 0.117 ms/op
Iteration   1: 2.289 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.481 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.843 ms/op
                 createUser·p0.95:   3.363 ms/op
                 createUser·p0.99:   10.519 ms/op
                 createUser·p0.999:  15.893 ms/op
                 createUser·p0.9999: 15.952 ms/op
                 createUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13962
  mean =      2.289 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 232 
    [ 1.250,  2.500) = 10619 
    [ 2.500,  3.750) = 2563 
    [ 3.750,  5.000) = 150 
    [ 5.000,  6.250) = 135 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.843 ms/op
     p(95.0000) =      3.363 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     15.893 ms/op
     p(99.9900) =     15.952 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.135 ±(99.9%) 0.075 ms/op
Iteration   1: 1.978 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   1.833 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.707 ms/op
                 existUser·p0.99:   3.588 ms/op
                 existUser·p0.999:  18.842 ms/op
                 existUser·p0.9999: 18.952 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16231
  mean =      1.978 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 398 
    [ 1.250,  2.500) = 14297 
    [ 2.500,  3.750) = 1410 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      1.833 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     18.952 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.553 ±(99.9%) 0.101 ms/op
Iteration   1: 2.277 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.418 ms/op
                 getUser·p0.50:   2.298 ms/op
                 getUser·p0.90:   2.855 ms/op
                 getUser·p0.95:   3.035 ms/op
                 getUser·p0.99:   3.906 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 12.098 ms/op
                 getUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14032
  mean =      2.277 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 492 
    [ 1.250,  2.500) = 8988 
    [ 2.500,  3.750) = 4392 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      2.298 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.906 ms/op
     p(99.9000) =     11.354 ms/op
     p(99.9900) =     12.098 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ±(99.9%) 0.136 ms/op
Iteration   1: 3.226 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 15.172 ms/op
                 listUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9868
  mean =      3.226 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1128 
    [ 2.500,  3.750) = 6611 
    [ 3.750,  5.000) = 1915 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     15.172 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.919          ops/ms
ClientSimple.existUser                       thrpt         13.333          ops/ms
ClientSimple.getUser                         thrpt         12.197          ops/ms
ClientSimple.listUser                        thrpt          8.122          ops/ms
ClientSimple.createUser                       avgt          2.318           ms/op
ClientSimple.existUser                        avgt          1.840           ms/op
ClientSimple.getUser                          avgt          2.434           ms/op
ClientSimple.listUser                         avgt          3.449           ms/op
ClientSimple.createUser                     sample  13962   2.289 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.481           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.363           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.519           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.893           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.952           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.958           ms/op
ClientSimple.existUser                      sample  16231   1.978 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.471           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.833           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.486           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.707           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.588           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.842           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.952           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.973           ms/op
ClientSimple.getUser                        sample  14032   2.277 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.418           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.298           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.035           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.906           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.354           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.098           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.124           ms/op
ClientSimple.listUser                       sample   9868   3.226 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.039           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.153           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.358           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.579           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.729           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.172           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.172           ms/op

Benchmark result is saved to 1722968043190.json
