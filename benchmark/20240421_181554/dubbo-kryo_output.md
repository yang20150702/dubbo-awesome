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
# Warmup Iteration   1: 1.743 ops/ms
Iteration   1: 7.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.317 ops/ms


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
# Warmup Iteration   1: 4.739 ops/ms
Iteration   1: 11.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.761 ops/ms


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
# Warmup Iteration   1: 5.140 ops/ms
Iteration   1: 11.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.894 ops/ms


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
# Warmup Iteration   1: 3.424 ops/ms
Iteration   1: 8.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.861 ops/ms


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.086 ms/op
Iteration   1: 2.167 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.167 ms/op


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
# Warmup Iteration   1: 3.235 ±(99.9%) 0.050 ms/op
Iteration   1: 1.961 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


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
# Warmup Iteration   1: 3.353 ±(99.9%) 0.077 ms/op
Iteration   1: 2.092 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.092 ms/op


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.100 ms/op
Iteration   1: 3.341 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.341 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.095 ms/op
Iteration   1: 1.953 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   1.834 ms/op
                 createUser·p0.90:   2.310 ms/op
                 createUser·p0.95:   2.526 ms/op
                 createUser·p0.99:   4.644 ms/op
                 createUser·p0.999:  16.318 ms/op
                 createUser·p0.9999: 18.514 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16404
  mean =      1.953 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 288 
    [ 1.250,  2.500) = 15253 
    [ 2.500,  3.750) = 632 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 67 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.834 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.526 ms/op
     p(99.0000) =      4.644 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.075 ms/op
Iteration   1: 1.824 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   1.757 ms/op
                 existUser·p0.90:   2.079 ms/op
                 existUser·p0.95:   2.236 ms/op
                 existUser·p0.99:   2.872 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 12.210 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17518
  mean =      1.824 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 107 
    [ 1.250,  2.500) = 17046 
    [ 2.500,  3.750) = 290 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      1.757 ms/op
     p(90.0000) =      2.079 ms/op
     p(95.0000) =      2.236 ms/op
     p(99.0000) =      2.872 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     12.210 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.102 ms/op
Iteration   1: 2.080 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   2.019 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.720 ms/op
                 getUser·p0.99:   3.166 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 11.400 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15367
  mean =      2.080 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1617 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     11.400 ms/op
     p(99.9990) =     11.567 ms/op
     p(99.9999) =     11.567 ms/op
    p(100.0000) =     11.567 ms/op


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
# Warmup Iteration   1: 4.324 ±(99.9%) 0.121 ms/op
Iteration   1: 3.260 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.809 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  22.255 ms/op
                 listUser·p0.9999: 24.936 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9845
  mean =      3.260 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1757 
    [ 2.500,  5.000) = 7794 
    [ 5.000,  7.500) = 249 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     22.255 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.317          ops/ms
ClientSimple.existUser                       thrpt         11.761          ops/ms
ClientSimple.getUser                         thrpt         11.894          ops/ms
ClientSimple.listUser                        thrpt          8.861          ops/ms
ClientSimple.createUser                       avgt          2.167           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          2.092           ms/op
ClientSimple.listUser                         avgt          3.341           ms/op
ClientSimple.createUser                     sample  16404   1.953 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.655           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.834           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.310           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.526           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.644           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.318           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.514           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  17518   1.824 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.740           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.757           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.079           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.236           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.872           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.895           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.210           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.222           ms/op
ClientSimple.getUser                        sample  15367   2.080 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.552           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.019           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.166           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.584           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.400           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.567           ms/op
ClientSimple.listUser                       sample   9845   3.260 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.954           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.505           ms/op
ClientSimple.listUser:listUser·p0.999       sample         22.255           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.936           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.936           ms/op

Benchmark result is saved to 1713723106239.json
