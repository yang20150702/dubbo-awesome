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
# Warmup Iteration   1: 1.814 ops/ms
Iteration   1: 7.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.078 ops/ms


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
# Warmup Iteration   1: 6.255 ops/ms
Iteration   1: 12.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.442 ops/ms


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
# Warmup Iteration   1: 5.649 ops/ms
Iteration   1: 13.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.024 ops/ms


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
# Warmup Iteration   1: 4.873 ops/ms
Iteration   1: 8.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.924 ops/ms


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
# Warmup Iteration   1: 3.835 ±(99.9%) 0.086 ms/op
Iteration   1: 2.097 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.097 ms/op


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
# Warmup Iteration   1: 3.302 ±(99.9%) 0.048 ms/op
Iteration   1: 1.687 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.687 ms/op


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
# Warmup Iteration   1: 3.191 ±(99.9%) 0.052 ms/op
Iteration   1: 1.981 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.981 ms/op


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.108 ms/op
Iteration   1: 3.488 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.488 ms/op


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
# Warmup Iteration   1: 3.747 ±(99.9%) 0.103 ms/op
Iteration   1: 2.245 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.037 ms/op
                 createUser·p0.50:   1.954 ms/op
                 createUser·p0.90:   3.154 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.877 ms/op
                 createUser·p0.999:  16.531 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14229
  mean =      2.245 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 11291 
    [ 2.500,  3.750) = 2113 
    [ 3.750,  5.000) = 564 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      3.154 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.877 ms/op
     p(99.9000) =     16.531 ms/op
     p(99.9900) =     16.679 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


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
# Warmup Iteration   1: 3.134 ±(99.9%) 0.085 ms/op
Iteration   1: 1.767 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   2.048 ms/op
                 existUser·p0.95:   2.298 ms/op
                 existUser·p0.99:   3.051 ms/op
                 existUser·p0.999:  11.026 ms/op
                 existUser·p0.9999: 11.805 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18102
  mean =      1.767 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 17543 
    [ 2.500,  3.750) = 367 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      2.048 ms/op
     p(95.0000) =      2.298 ms/op
     p(99.0000) =      3.051 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     11.805 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.091 ms/op
Iteration   1: 2.012 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   1.878 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.804 ms/op
                 getUser·p0.99:   4.046 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 13.104 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15907
  mean =      2.012 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 14227 
    [ 2.500,  3.750) = 1290 
    [ 3.750,  5.000) = 152 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.804 ms/op
     p(99.0000) =      4.046 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     13.104 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.192 ms/op
Iteration   1: 3.540 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.457 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  19.522 ms/op
                 listUser·p0.9999: 20.054 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9024
  mean =      3.540 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1374 
    [ 2.500,  5.000) = 7337 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     19.522 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.078          ops/ms
ClientSimple.existUser                       thrpt         12.442          ops/ms
ClientSimple.getUser                         thrpt         13.024          ops/ms
ClientSimple.listUser                        thrpt          8.924          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          1.687           ms/op
ClientSimple.getUser                          avgt          1.981           ms/op
ClientSimple.listUser                         avgt          3.488           ms/op
ClientSimple.createUser                     sample  14229   2.245 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.037           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.954           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.154           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.817           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.877           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.531           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.679           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.679           ms/op
ClientSimple.existUser                      sample  18102   1.767 ± 0.012   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.663           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.686           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.048           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.298           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.051           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.026           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.805           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.911           ms/op
ClientSimple.getUser                        sample  15907   2.012 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.649           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.878           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.804           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.046           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.091           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.104           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   9024   3.540 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.884           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.457           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.726           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.522           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.054           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.054           ms/op

Benchmark result is saved to 1711240886575.json
