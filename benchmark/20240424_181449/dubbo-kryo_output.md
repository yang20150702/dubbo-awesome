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
# Warmup Iteration   1: 1.972 ops/ms
Iteration   1: 7.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.838 ops/ms


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
# Warmup Iteration   1: 6.333 ops/ms
Iteration   1: 13.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.043 ops/ms


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
# Warmup Iteration   1: 6.978 ops/ms
Iteration   1: 15.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.594 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.352 ops/ms
Iteration   1: 8.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.497 ops/ms


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.060 ms/op
Iteration   1: 2.097 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.097 ms/op


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
# Warmup Iteration   1: 2.934 ±(99.9%) 0.045 ms/op
Iteration   1: 1.731 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.731 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.053 ms/op
Iteration   1: 1.884 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.884 ms/op


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
# Warmup Iteration   1: 5.199 ±(99.9%) 0.090 ms/op
Iteration   1: 3.085 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.085 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.080 ms/op
Iteration   1: 2.054 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.570 ms/op
                 createUser·p0.50:   1.884 ms/op
                 createUser·p0.90:   2.441 ms/op
                 createUser·p0.95:   2.691 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  15.424 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15573
  mean =      2.054 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 192 
    [ 1.250,  2.500) = 14054 
    [ 2.500,  3.750) = 1046 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.691 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     15.424 ms/op
     p(99.9900) =     16.286 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.934 ±(99.9%) 0.068 ms/op
Iteration   1: 1.925 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.318 ms/op
                 existUser·p0.50:   1.876 ms/op
                 existUser·p0.90:   2.404 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.116 ms/op
                 existUser·p0.999:  12.414 ms/op
                 existUser·p0.9999: 12.710 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16584
  mean =      1.925 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 404 
    [ 1.250,  2.500) = 15004 
    [ 2.500,  3.750) = 1110 
    [ 3.750,  5.000) = 31 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.404 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.116 ms/op
     p(99.9000) =     12.414 ms/op
     p(99.9900) =     12.710 ms/op
     p(99.9990) =     12.796 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


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
# Warmup Iteration   1: 3.101 ±(99.9%) 0.075 ms/op
Iteration   1: 1.816 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.690 ms/op
                 getUser·p0.50:   1.632 ms/op
                 getUser·p0.90:   2.384 ms/op
                 getUser·p0.95:   2.519 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  15.797 ms/op
                 getUser·p0.9999: 16.108 ms/op
                 getUser·p1.00:   16.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17828
  mean =      1.816 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1323 
    [ 1.250,  2.500) = 15514 
    [ 2.500,  3.750) = 794 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.632 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     15.797 ms/op
     p(99.9900) =     16.108 ms/op
     p(99.9990) =     16.237 ms/op
     p(99.9999) =     16.237 ms/op
    p(100.0000) =     16.237 ms/op


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.125 ms/op
Iteration   1: 3.449 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.351 ms/op
                 listUser·p0.90:   4.416 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.971 ms/op
                 listUser·p0.999:  6.975 ms/op
                 listUser·p0.9999: 7.094 ms/op
                 listUser·p1.00:   7.094 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9308
  mean =      3.449 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 52 
    [2.000, 2.500) = 154 
    [2.500, 3.000) = 3360 
    [3.000, 3.500) = 1654 
    [3.500, 4.000) = 2020 
    [4.000, 4.500) = 1326 
    [4.500, 5.000) = 463 
    [5.000, 5.500) = 124 
    [5.500, 6.000) = 66 
    [6.000, 6.500) = 46 
    [6.500, 7.000) = 29 
    [7.000, 7.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.416 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.971 ms/op
     p(99.9000) =      6.975 ms/op
     p(99.9900) =      7.094 ms/op
     p(99.9990) =      7.094 ms/op
     p(99.9999) =      7.094 ms/op
    p(100.0000) =      7.094 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.838          ops/ms
ClientSimple.existUser                       thrpt         13.043          ops/ms
ClientSimple.getUser                         thrpt         15.594          ops/ms
ClientSimple.listUser                        thrpt          8.497          ops/ms
ClientSimple.createUser                       avgt          2.097           ms/op
ClientSimple.existUser                        avgt          1.731           ms/op
ClientSimple.getUser                          avgt          1.884           ms/op
ClientSimple.listUser                         avgt          3.085           ms/op
ClientSimple.createUser                     sample  15573   2.054 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.570           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.884           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.441           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.389           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.424           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.286           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.286           ms/op
ClientSimple.existUser                      sample  16584   1.925 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.318           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.876           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.116           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.414           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.710           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.796           ms/op
ClientSimple.getUser                        sample  17828   1.816 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.690           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.632           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.384           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.260           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.797           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.108           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.237           ms/op
ClientSimple.listUser                       sample   9308   3.449 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.351           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.416           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.971           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.975           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.094           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.094           ms/op

Benchmark result is saved to 1713982243099.json
