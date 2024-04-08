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
# Warmup Iteration   1: 0.878 ops/ms
Iteration   1: 5.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.730 ops/ms


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
# Warmup Iteration   1: 6.065 ops/ms
Iteration   1: 13.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.852 ops/ms


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
# Warmup Iteration   1: 7.199 ops/ms
Iteration   1: 13.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.755 ops/ms


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
# Warmup Iteration   1: 4.333 ops/ms
Iteration   1: 7.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.859 ops/ms


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.078 ms/op
Iteration   1: 2.346 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.346 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.086 ms/op
Iteration   1: 1.900 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.900 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.062 ms/op
Iteration   1: 2.089 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.089 ms/op


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
# Warmup Iteration   1: 4.648 ±(99.9%) 0.101 ms/op
Iteration   1: 3.079 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.079 ms/op


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
# Warmup Iteration   1: 3.557 ±(99.9%) 0.103 ms/op
Iteration   1: 1.984 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.701 ms/op
                 createUser·p0.50:   1.784 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   4.956 ms/op
                 createUser·p0.999:  14.187 ms/op
                 createUser·p0.9999: 14.701 ms/op
                 createUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16100
  mean =      1.984 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 14298 
    [ 2.500,  3.750) = 1419 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      4.956 ms/op
     p(99.9000) =     14.187 ms/op
     p(99.9900) =     14.701 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.056 ±(99.9%) 0.067 ms/op
Iteration   1: 1.802 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.617 ms/op
                 existUser·p0.50:   1.671 ms/op
                 existUser·p0.90:   2.245 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   3.427 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 11.076 ms/op
                 existUser·p1.00:   11.076 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17729
  mean =      1.802 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 328 
    [ 1.250,  2.500) = 16765 
    [ 2.500,  3.750) = 480 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      1.671 ms/op
     p(90.0000) =      2.245 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      3.427 ms/op
     p(99.9000) =     10.846 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.076 ms/op
     p(99.9999) =     11.076 ms/op
    p(100.0000) =     11.076 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.085 ms/op
Iteration   1: 2.078 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   1.931 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.843 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  18.416 ms/op
                 getUser·p0.9999: 18.970 ms/op
                 getUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15537
  mean =      2.078 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 12446 
    [ 2.500,  3.750) = 2760 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.931 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     18.970 ms/op
     p(99.9990) =     19.169 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.532 ±(99.9%) 0.147 ms/op
Iteration   1: 3.518 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   0.571 ms/op
                 listUser·p0.50:   3.375 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   10.863 ms/op
                 listUser·p0.999:  15.711 ms/op
                 listUser·p0.9999: 15.991 ms/op
                 listUser·p1.00:   15.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9101
  mean =      3.518 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 731 
    [ 2.500,  3.750) = 5508 
    [ 3.750,  5.000) = 2487 
    [ 5.000,  6.250) = 179 
    [ 6.250,  7.500) = 79 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =     10.863 ms/op
     p(99.9000) =     15.711 ms/op
     p(99.9900) =     15.991 ms/op
     p(99.9990) =     15.991 ms/op
     p(99.9999) =     15.991 ms/op
    p(100.0000) =     15.991 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.730          ops/ms
ClientSimple.existUser                       thrpt         13.852          ops/ms
ClientSimple.getUser                         thrpt         13.755          ops/ms
ClientSimple.listUser                        thrpt          7.859          ops/ms
ClientSimple.createUser                       avgt          2.346           ms/op
ClientSimple.existUser                        avgt          1.900           ms/op
ClientSimple.getUser                          avgt          2.089           ms/op
ClientSimple.listUser                         avgt          3.079           ms/op
ClientSimple.createUser                     sample  16100   1.984 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.701           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.784           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.956           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.187           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.701           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.401           ms/op
ClientSimple.existUser                      sample  17729   1.802 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.617           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.671           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.245           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.427           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.846           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.076           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.076           ms/op
ClientSimple.getUser                        sample  15537   2.078 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.931           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.694           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.416           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.970           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.169           ms/op
ClientSimple.listUser                       sample   9101   3.518 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.571           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.375           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.863           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.711           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.991           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.991           ms/op

Benchmark result is saved to 1712578491881.json
