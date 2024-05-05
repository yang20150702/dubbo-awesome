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
# Warmup Iteration   1: 1.828 ops/ms
Iteration   1: 6.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.987 ops/ms


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
# Warmup Iteration   1: 6.273 ops/ms
Iteration   1: 13.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.138 ops/ms


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
# Warmup Iteration   1: 4.861 ops/ms
Iteration   1: 12.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.012 ops/ms


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
# Warmup Iteration   1: 5.043 ops/ms
Iteration   1: 8.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.475 ops/ms


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.113 ms/op
Iteration   1: 2.116 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.116 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.051 ms/op
Iteration   1: 1.669 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.669 ms/op


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
# Warmup Iteration   1: 3.419 ±(99.9%) 0.056 ms/op
Iteration   1: 2.063 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.063 ms/op


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.066 ms/op
Iteration   1: 3.199 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.199 ms/op


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
# Warmup Iteration   1: 3.472 ±(99.9%) 0.082 ms/op
Iteration   1: 2.062 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.594 ms/op
                 createUser·p0.50:   1.823 ms/op
                 createUser·p0.90:   2.396 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   9.215 ms/op
                 createUser·p0.999:  25.542 ms/op
                 createUser·p0.9999: 29.285 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15757
  mean =      2.062 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14505 
    [ 2.500,  5.000) = 1049 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      1.823 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      9.215 ms/op
     p(99.9000) =     25.542 ms/op
     p(99.9900) =     29.285 ms/op
     p(99.9990) =     29.360 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 2.958 ±(99.9%) 0.071 ms/op
Iteration   1: 1.751 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   1.978 ms/op
                 existUser·p0.95:   2.191 ms/op
                 existUser·p0.99:   3.101 ms/op
                 existUser·p0.999:  10.535 ms/op
                 existUser·p0.9999: 10.783 ms/op
                 existUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18741
  mean =      1.751 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 18 
    [ 1.000,  2.000) = 16953 
    [ 2.000,  3.000) = 1571 
    [ 3.000,  4.000) = 106 
    [ 4.000,  5.000) = 28 
    [ 5.000,  6.000) = 33 
    [ 6.000,  7.000) = 0 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.871 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      1.978 ms/op
     p(95.0000) =      2.191 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     10.535 ms/op
     p(99.9900) =     10.783 ms/op
     p(99.9990) =     10.797 ms/op
     p(99.9999) =     10.797 ms/op
    p(100.0000) =     10.797 ms/op


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
# Warmup Iteration   1: 3.509 ±(99.9%) 0.080 ms/op
Iteration   1: 2.142 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   2.040 ms/op
                 getUser·p0.90:   2.601 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  12.042 ms/op
                 getUser·p0.9999: 12.404 ms/op
                 getUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14923
  mean =      2.142 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 12918 
    [ 2.500,  3.750) = 1621 
    [ 3.750,  5.000) = 167 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     12.042 ms/op
     p(99.9900) =     12.404 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.126 ms/op
Iteration   1: 3.484 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   4.851 ms/op
                 listUser·p0.999:  5.897 ms/op
                 listUser·p0.9999: 6.709 ms/op
                 listUser·p1.00:   6.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9187
  mean =      3.484 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 92 
    [2.000, 2.500) = 489 
    [2.500, 3.000) = 1750 
    [3.000, 3.500) = 1903 
    [3.500, 4.000) = 3067 
    [4.000, 4.500) = 1558 
    [4.500, 5.000) = 234 
    [5.000, 5.500) = 37 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      4.851 ms/op
     p(99.9000) =      5.897 ms/op
     p(99.9900) =      6.709 ms/op
     p(99.9990) =      6.709 ms/op
     p(99.9999) =      6.709 ms/op
    p(100.0000) =      6.709 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.987          ops/ms
ClientSimple.existUser                       thrpt         13.138          ops/ms
ClientSimple.getUser                         thrpt         12.012          ops/ms
ClientSimple.listUser                        thrpt          8.475          ops/ms
ClientSimple.createUser                       avgt          2.116           ms/op
ClientSimple.existUser                        avgt          1.669           ms/op
ClientSimple.getUser                          avgt          2.063           ms/op
ClientSimple.listUser                         avgt          3.199           ms/op
ClientSimple.createUser                     sample  15757   2.062 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.594           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.823           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.396           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.215           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.542           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         29.285           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.360           ms/op
ClientSimple.existUser                      sample  18741   1.751 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.871           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.679           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.978           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.101           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.535           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.783           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.797           ms/op
ClientSimple.getUser                        sample  14923   2.142 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.591           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.040           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.375           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.042           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.404           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.485           ms/op
ClientSimple.listUser                       sample   9187   3.484 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.157           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.851           ms/op
ClientSimple.listUser:listUser·p0.999       sample          5.897           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.709           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.709           ms/op

Benchmark result is saved to 1714869665053.json
