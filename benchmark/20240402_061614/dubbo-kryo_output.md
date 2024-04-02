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
# Warmup Iteration   1: 1.895 ops/ms
Iteration   1: 7.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.042 ops/ms


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
# Warmup Iteration   1: 6.267 ops/ms
Iteration   1: 12.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.382 ops/ms


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
# Warmup Iteration   1: 5.642 ops/ms
Iteration   1: 12.891 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.891 ops/ms


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
# Warmup Iteration   1: 5.588 ops/ms
Iteration   1: 8.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.464 ops/ms


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.072 ms/op
Iteration   1: 2.206 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.206 ms/op


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
# Warmup Iteration   1: 2.971 ±(99.9%) 0.050 ms/op
Iteration   1: 2.091 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.091 ms/op


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.057 ms/op
Iteration   1: 1.802 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.802 ms/op


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
# Warmup Iteration   1: 4.965 ±(99.9%) 0.099 ms/op
Iteration   1: 3.641 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.641 ms/op


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.108 ms/op
Iteration   1: 2.257 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.081 ms/op
                 createUser·p0.90:   2.855 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   5.864 ms/op
                 createUser·p0.999:  19.562 ms/op
                 createUser·p0.9999: 20.532 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14139
  mean =      2.257 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11141 
    [ 2.500,  5.000) = 2782 
    [ 5.000,  7.500) = 115 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.236 ms/op
     p(99.0000) =      5.864 ms/op
     p(99.9000) =     19.562 ms/op
     p(99.9900) =     20.532 ms/op
     p(99.9990) =     20.546 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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
# Warmup Iteration   1: 2.895 ±(99.9%) 0.074 ms/op
Iteration   1: 1.952 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.920 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  11.043 ms/op
                 existUser·p0.9999: 11.278 ms/op
                 existUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16377
  mean =      1.952 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 530 
    [ 1.250,  2.500) = 13658 
    [ 2.500,  3.750) = 2007 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     11.278 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 3.481 ±(99.9%) 0.093 ms/op
Iteration   1: 2.249 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.122 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.999 ms/op
                 getUser·p0.99:   5.644 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14217
  mean =      2.249 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 11836 
    [ 2.500,  3.750) = 1957 
    [ 3.750,  5.000) = 237 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.810 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.999 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 4.520 ±(99.9%) 0.154 ms/op
Iteration   1: 3.679 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.533 ms/op
                 listUser·p0.999:  15.038 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8708
  mean =      3.679 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 428 
    [ 2.500,  3.750) = 4598 
    [ 3.750,  5.000) = 3354 
    [ 5.000,  6.250) = 217 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      6.533 ms/op
     p(99.9000) =     15.038 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.042          ops/ms
ClientSimple.existUser                       thrpt         12.382          ops/ms
ClientSimple.getUser                         thrpt         12.891          ops/ms
ClientSimple.listUser                        thrpt          8.464          ops/ms
ClientSimple.createUser                       avgt          2.206           ms/op
ClientSimple.existUser                        avgt          2.091           ms/op
ClientSimple.getUser                          avgt          1.802           ms/op
ClientSimple.listUser                         avgt          3.641           ms/op
ClientSimple.createUser                     sample  14139   2.257 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.081           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.236           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.864           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.562           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.532           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.546           ms/op
ClientSimple.existUser                      sample  16377   1.952 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.714           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.920           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.838           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.043           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.278           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.518           ms/op
ClientSimple.getUser                        sample  14217   2.249 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.810           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.122           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.999           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.644           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.433           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.760           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.760           ms/op
ClientSimple.listUser                       sample   8708   3.679 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.069           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.613           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.533           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.038           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.760           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.760           ms/op

Benchmark result is saved to 1712038306026.json
