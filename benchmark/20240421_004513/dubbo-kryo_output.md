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
# Warmup Iteration   1: 2.077 ops/ms
Iteration   1: 7.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.259 ops/ms


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
# Warmup Iteration   1: 5.951 ops/ms
Iteration   1: 13.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.008 ops/ms


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
# Warmup Iteration   1: 5.714 ops/ms
Iteration   1: 12.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.466 ops/ms


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
# Warmup Iteration   1: 4.435 ops/ms
Iteration   1: 8.324 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.324 ops/ms


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.070 ms/op
Iteration   1: 2.258 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.258 ms/op


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
# Warmup Iteration   1: 3.199 ±(99.9%) 0.054 ms/op
Iteration   1: 1.764 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.764 ms/op


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
# Warmup Iteration   1: 3.131 ±(99.9%) 0.056 ms/op
Iteration   1: 2.015 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.015 ms/op


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
# Warmup Iteration   1: 4.303 ±(99.9%) 0.102 ms/op
Iteration   1: 3.586 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.586 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.075 ms/op
Iteration   1: 2.129 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.302 ms/op
                 createUser·p0.50:   1.911 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   2.597 ms/op
                 createUser·p0.99:   9.269 ms/op
                 createUser·p0.999:  25.297 ms/op
                 createUser·p0.9999: 28.145 ms/op
                 createUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15024
  mean =      2.129 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14109 
    [ 2.500,  5.000) = 623 
    [ 5.000,  7.500) = 61 
    [ 7.500, 10.000) = 101 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      9.269 ms/op
     p(99.9000) =     25.297 ms/op
     p(99.9900) =     28.145 ms/op
     p(99.9990) =     28.705 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 2.989 ±(99.9%) 0.066 ms/op
Iteration   1: 2.058 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   1.966 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.839 ms/op
                 existUser·p0.99:   3.820 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 13.753 ms/op
                 existUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15582
  mean =      2.058 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 248 
    [ 1.250,  2.500) = 13416 
    [ 2.500,  3.750) = 1758 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 15 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.966 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.839 ms/op
     p(99.0000) =      3.820 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     13.753 ms/op
     p(99.9990) =     13.763 ms/op
     p(99.9999) =     13.763 ms/op
    p(100.0000) =     13.763 ms/op


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
# Warmup Iteration   1: 3.399 ±(99.9%) 0.103 ms/op
Iteration   1: 2.262 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.403 ms/op
                 getUser·p0.50:   2.236 ms/op
                 getUser·p0.90:   2.875 ms/op
                 getUser·p0.95:   3.105 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 12.565 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14142
  mean =      2.262 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 343 
    [ 1.250,  2.500) = 9980 
    [ 2.500,  3.750) = 3609 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     12.565 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.116 ms/op
Iteration   1: 3.254 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   4.168 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.946 ms/op
                 listUser·p0.999:  20.256 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9822
  mean =      3.254 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 742 
    [ 2.500,  5.000) = 8784 
    [ 5.000,  7.500) = 263 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      4.168 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.946 ms/op
     p(99.9000) =     20.256 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.259          ops/ms
ClientSimple.existUser                       thrpt         13.008          ops/ms
ClientSimple.getUser                         thrpt         12.466          ops/ms
ClientSimple.listUser                        thrpt          8.324          ops/ms
ClientSimple.createUser                       avgt          2.258           ms/op
ClientSimple.existUser                        avgt          1.764           ms/op
ClientSimple.getUser                          avgt          2.015           ms/op
ClientSimple.listUser                         avgt          3.586           ms/op
ClientSimple.createUser                     sample  15024   2.129 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.302           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.911           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.269           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.297           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.145           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.705           ms/op
ClientSimple.existUser                      sample  15582   2.058 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.667           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.966           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.839           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.820           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.648           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.753           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.763           ms/op
ClientSimple.getUser                        sample  14142   2.262 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.403           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.236           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.105           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.174           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.222           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.565           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.714           ms/op
ClientSimple.listUser                       sample   9822   3.254 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.219           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.168           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.946           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.256           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.692           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.692           ms/op

Benchmark result is saved to 1713660057023.json
