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
# Warmup Iteration   1: 1.817 ops/ms
Iteration   1: 6.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.114 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 11.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.545 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.075 ops/ms
Iteration   1: 11.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.824 ops/ms


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
# Warmup Iteration   1: 3.980 ops/ms
Iteration   1: 8.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.801 ops/ms


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
# Warmup Iteration   1: 4.211 ±(99.9%) 0.080 ms/op
Iteration   1: 2.402 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.402 ms/op


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
# Warmup Iteration   1: 3.277 ±(99.9%) 0.050 ms/op
Iteration   1: 2.218 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.218 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.082 ms/op
Iteration   1: 2.041 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.041 ms/op


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
# Warmup Iteration   1: 6.532 ±(99.9%) 0.132 ms/op
Iteration   1: 3.544 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.544 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.093 ms/op
Iteration   1: 2.195 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.252 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.929 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   7.120 ms/op
                 createUser·p0.999:  22.539 ms/op
                 createUser·p0.9999: 23.555 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14539
  mean =      2.195 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11905 
    [ 2.500,  5.000) = 2398 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 27 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.252 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.929 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      7.120 ms/op
     p(99.9000) =     22.539 ms/op
     p(99.9900) =     23.555 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.075 ms/op
Iteration   1: 1.979 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.347 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.449 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   4.464 ms/op
                 existUser·p0.999:  12.993 ms/op
                 existUser·p0.9999: 13.998 ms/op
                 existUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16412
  mean =      1.979 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 14644 
    [ 2.500,  3.750) = 1026 
    [ 3.750,  5.000) = 13 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.347 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.449 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      4.464 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     13.998 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.087 ms/op
Iteration   1: 1.887 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   1.708 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.617 ms/op
                 getUser·p0.99:   4.159 ms/op
                 getUser·p0.999:  19.956 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17072
  mean =      1.887 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15909 
    [ 2.500,  5.000) = 1055 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      4.159 ms/op
     p(99.9000) =     19.956 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.127 ms/op
Iteration   1: 3.595 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  12.601 ms/op
                 listUser·p0.9999: 12.829 ms/op
                 listUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8891
  mean =      3.595 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 563 
    [ 2.500,  3.750) = 5257 
    [ 3.750,  5.000) = 2533 
    [ 5.000,  6.250) = 302 
    [ 6.250,  7.500) = 114 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      7.782 ms/op
     p(99.9000) =     12.601 ms/op
     p(99.9900) =     12.829 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.114          ops/ms
ClientSimple.existUser                       thrpt         11.545          ops/ms
ClientSimple.getUser                         thrpt         11.824          ops/ms
ClientSimple.listUser                        thrpt          8.801          ops/ms
ClientSimple.createUser                       avgt          2.402           ms/op
ClientSimple.existUser                        avgt          2.218           ms/op
ClientSimple.getUser                          avgt          2.041           ms/op
ClientSimple.listUser                         avgt          3.544           ms/op
ClientSimple.createUser                     sample  14539   2.195 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.252           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.929           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.166           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.120           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.539           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.555           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.986           ms/op
ClientSimple.existUser                      sample  16412   1.979 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.347           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.937           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.449           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.464           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.993           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.998           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.008           ms/op
ClientSimple.getUser                        sample  17072   1.887 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.474           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.708           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.159           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.956           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.054           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.054           ms/op
ClientSimple.listUser                       sample   8891   3.595 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.910           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.432           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.782           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.601           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.829           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.829           ms/op

Benchmark result is saved to 1710808600495.json
