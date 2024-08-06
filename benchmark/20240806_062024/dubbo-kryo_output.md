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
# Warmup Iteration   1: 2.264 ops/ms
Iteration   1: 7.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.177 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.103 ops/ms
Iteration   1: 12.368 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.368 ops/ms


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
# Warmup Iteration   1: 4.987 ops/ms
Iteration   1: 12.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.017 ops/ms


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
# Warmup Iteration   1: 5.797 ops/ms
Iteration   1: 8.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.486 ops/ms


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
# Warmup Iteration   1: 4.176 ±(99.9%) 0.068 ms/op
Iteration   1: 2.332 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.332 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.051 ms/op
Iteration   1: 1.832 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.832 ms/op


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
# Warmup Iteration   1: 3.345 ±(99.9%) 0.064 ms/op
Iteration   1: 2.292 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.292 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.088 ms/op
Iteration   1: 3.364 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.364 ms/op


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
# Warmup Iteration   1: 3.446 ±(99.9%) 0.084 ms/op
Iteration   1: 1.967 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   1.794 ms/op
                 createUser·p0.90:   2.404 ms/op
                 createUser·p0.95:   2.732 ms/op
                 createUser·p0.99:   6.517 ms/op
                 createUser·p0.999:  17.400 ms/op
                 createUser·p0.9999: 18.199 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16240
  mean =      1.967 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 373 
    [ 1.250,  2.500) = 14614 
    [ 2.500,  3.750) = 981 
    [ 3.750,  5.000) = 96 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.794 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      6.517 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     18.199 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.071 ms/op
Iteration   1: 1.917 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.736 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   5.130 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16672
  mean =      1.917 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 15416 
    [ 2.500,  3.750) = 739 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 147 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      5.130 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.165 ms/op
Iteration   1: 2.242 ±(99.9%) 0.126 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   1.917 ms/op
                 getUser·p0.90:   2.481 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  100.864 ms/op
                 getUser·p0.9999: 119.018 ms/op
                 getUser·p1.00:   119.144 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14823
  mean =      2.242 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 14766 
    [ 12.500,  25.000) = 11 
    [ 25.000,  37.500) = 8 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 1 
    [ 62.500,  75.000) = 2 
    [ 75.000,  87.500) = 6 
    [ 87.500, 100.000) = 9 
    [100.000, 112.500) = 9 
    [112.500, 125.000) = 6 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.481 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =    100.864 ms/op
     p(99.9900) =    119.018 ms/op
     p(99.9990) =    119.144 ms/op
     p(99.9999) =    119.144 ms/op
    p(100.0000) =    119.144 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.124 ms/op
Iteration   1: 3.148 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.999 ms/op
                 listUser·p0.999:  17.100 ms/op
                 listUser·p0.9999: 18.087 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10151
  mean =      3.148 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 263 
    [ 2.500,  3.750) = 8384 
    [ 3.750,  5.000) = 1335 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.999 ms/op
     p(99.9000) =     17.100 ms/op
     p(99.9900) =     18.087 ms/op
     p(99.9990) =     18.088 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.177          ops/ms
ClientSimple.existUser                       thrpt          12.368          ops/ms
ClientSimple.getUser                         thrpt          12.017          ops/ms
ClientSimple.listUser                        thrpt           8.486          ops/ms
ClientSimple.createUser                       avgt           2.332           ms/op
ClientSimple.existUser                        avgt           1.832           ms/op
ClientSimple.getUser                          avgt           2.292           ms/op
ClientSimple.listUser                         avgt           3.364           ms/op
ClientSimple.createUser                     sample  16240    1.967 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.428           ms/op
ClientSimple.createUser:createUser·p0.50    sample           1.794           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.404           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.732           ms/op
ClientSimple.createUser:createUser·p0.99    sample           6.517           ms/op
ClientSimple.createUser:createUser·p0.999   sample          17.400           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          18.199           ms/op
ClientSimple.createUser:createUser·p1.00    sample          18.219           ms/op
ClientSimple.existUser                      sample  16672    1.917 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.736           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.281           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample           5.130           ms/op
ClientSimple.existUser:existUser·p0.999     sample          11.256           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          11.452           ms/op
ClientSimple.existUser:existUser·p1.00      sample          11.518           ms/op
ClientSimple.getUser                        sample  14823    2.242 ± 0.126   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.808           ms/op
ClientSimple.getUser:getUser·p0.50          sample           1.917           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.481           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample           5.382           ms/op
ClientSimple.getUser:getUser·p0.999         sample         100.864           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         119.018           ms/op
ClientSimple.getUser:getUser·p1.00          sample         119.144           ms/op
ClientSimple.listUser                       sample  10151    3.148 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.124           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.875           ms/op
ClientSimple.listUser:listUser·p0.90        sample           3.924           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.999           ms/op
ClientSimple.listUser:listUser·p0.999       sample          17.100           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          18.087           ms/op
ClientSimple.listUser:listUser·p1.00        sample          18.088           ms/op

Benchmark result is saved to 1722924904572.json
