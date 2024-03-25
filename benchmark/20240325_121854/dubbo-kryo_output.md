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
# Warmup Iteration   1: 1.824 ops/ms
Iteration   1: 7.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.088 ops/ms


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
# Warmup Iteration   1: 6.282 ops/ms
Iteration   1: 13.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.105 ops/ms


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
# Warmup Iteration   1: 5.914 ops/ms
Iteration   1: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.790 ops/ms


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
# Warmup Iteration   1: 4.595 ops/ms
Iteration   1: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.457 ops/ms


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
# Warmup Iteration   1: 3.839 ±(99.9%) 0.077 ms/op
Iteration   1: 2.102 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.102 ms/op


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
# Warmup Iteration   1: 3.336 ±(99.9%) 0.068 ms/op
Iteration   1: 1.971 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.971 ms/op


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.095 ms/op
Iteration   1: 1.869 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.869 ms/op


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
# Warmup Iteration   1: 5.143 ±(99.9%) 0.126 ms/op
Iteration   1: 3.638 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.638 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.079 ms/op
Iteration   1: 1.995 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.492 ms/op
                 createUser·p0.50:   1.761 ms/op
                 createUser·p0.90:   2.524 ms/op
                 createUser·p0.95:   2.802 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 18.454 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 16068
  mean =      1.995 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 14319 
    [ 2.500,  3.750) = 1437 
    [ 3.750,  5.000) = 48 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      1.761 ms/op
     p(90.0000) =      2.524 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     17.760 ms/op
     p(99.9900) =     18.454 ms/op
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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.078 ms/op
Iteration   1: 2.139 ±(99.9%) 0.037 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.007 ms/op
                 existUser·p0.90:   2.732 ms/op
                 existUser·p0.95:   2.929 ms/op
                 existUser·p0.99:   3.401 ms/op
                 existUser·p0.999:  21.627 ms/op
                 existUser·p0.9999: 22.038 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14953
  mean =      2.139 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12160 
    [ 2.500,  5.000) = 2702 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      2.929 ms/op
     p(99.0000) =      3.401 ms/op
     p(99.9000) =     21.627 ms/op
     p(99.9900) =     22.038 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.083 ms/op
Iteration   1: 1.920 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   1.837 ms/op
                 getUser·p0.90:   2.216 ms/op
                 getUser·p0.95:   2.454 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  10.770 ms/op
                 getUser·p0.9999: 12.490 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16677
  mean =      1.920 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 89 
    [ 1.250,  2.500) = 15875 
    [ 2.500,  3.750) = 551 
    [ 3.750,  5.000) = 84 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =     10.770 ms/op
     p(99.9900) =     12.490 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.199 ms/op
Iteration   1: 3.502 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   6.815 ms/op
                 listUser·p0.999:  19.286 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9142
  mean =      3.502 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1383 
    [ 2.500,  5.000) = 7385 
    [ 5.000,  7.500) = 308 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.815 ms/op
     p(99.9000) =     19.286 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.088          ops/ms
ClientSimple.existUser                       thrpt         13.105          ops/ms
ClientSimple.getUser                         thrpt         12.790          ops/ms
ClientSimple.listUser                        thrpt          8.457          ops/ms
ClientSimple.createUser                       avgt          2.102           ms/op
ClientSimple.existUser                        avgt          1.971           ms/op
ClientSimple.getUser                          avgt          1.869           ms/op
ClientSimple.listUser                         avgt          3.638           ms/op
ClientSimple.createUser                     sample  16068   1.995 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.492           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.761           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.524           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.802           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.145           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.760           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.454           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  14953   2.139 ± 0.037   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.519           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.007           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.732           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.929           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.401           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.627           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.038           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.151           ms/op
ClientSimple.getUser                        sample  16677   1.920 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.656           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.837           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.216           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.454           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.695           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.770           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.490           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.501           ms/op
ClientSimple.listUser                       sample   9142   3.502 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.167           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.815           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.286           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.414           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.414           ms/op

Benchmark result is saved to 1711368868093.json
