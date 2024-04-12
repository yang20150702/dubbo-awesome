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
# Warmup Iteration   1: 1.442 ops/ms
Iteration   1: 7.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.012 ops/ms


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
# Warmup Iteration   1: 5.856 ops/ms
Iteration   1: 13.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.453 ops/ms


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
# Warmup Iteration   1: 5.427 ops/ms
Iteration   1: 12.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.938 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.144 ops/ms
Iteration   1: 8.531 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.531 ops/ms


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
# Warmup Iteration   1: 3.569 ±(99.9%) 0.058 ms/op
Iteration   1: 2.494 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.494 ms/op


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
# Warmup Iteration   1: 3.082 ±(99.9%) 0.060 ms/op
Iteration   1: 2.102 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 2.989 ±(99.9%) 0.063 ms/op
Iteration   1: 2.137 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.137 ms/op


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
# Warmup Iteration   1: 5.138 ±(99.9%) 0.101 ms/op
Iteration   1: 3.385 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.385 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.097 ms/op
Iteration   1: 2.116 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   1.964 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   2.978 ms/op
                 createUser·p0.99:   5.105 ms/op
                 createUser·p0.999:  22.575 ms/op
                 createUser·p0.9999: 25.157 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15078
  mean =      2.116 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12528 
    [ 2.500,  5.000) = 2391 
    [ 5.000,  7.500) = 94 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      5.105 ms/op
     p(99.9000) =     22.575 ms/op
     p(99.9900) =     25.157 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


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
# Warmup Iteration   1: 2.748 ±(99.9%) 0.073 ms/op
Iteration   1: 2.075 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.384 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   3.137 ms/op
                 existUser·p0.99:   5.230 ms/op
                 existUser·p0.999:  14.927 ms/op
                 existUser·p0.9999: 16.546 ms/op
                 existUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15462
  mean =      2.075 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 13332 
    [ 2.500,  3.750) = 1477 
    [ 3.750,  5.000) = 202 
    [ 5.000,  6.250) = 90 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.384 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      3.137 ms/op
     p(99.0000) =      5.230 ms/op
     p(99.9000) =     14.927 ms/op
     p(99.9900) =     16.546 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.116 ms/op
Iteration   1: 2.264 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.138 ms/op
                 getUser·p0.90:   2.765 ms/op
                 getUser·p0.95:   3.031 ms/op
                 getUser·p0.99:   5.826 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 13.738 ms/op
                 getUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14538
  mean =      2.264 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 11418 
    [ 2.500,  3.750) = 2734 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.138 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =      5.826 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     13.738 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.140 ms/op
Iteration   1: 3.371 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.038 ms/op
                 listUser·p0.999:  21.185 ms/op
                 listUser·p0.9999: 21.594 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9497
  mean =      3.371 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 160 
    [ 2.500,  5.000) = 8990 
    [ 5.000,  7.500) = 313 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     21.185 ms/op
     p(99.9900) =     21.594 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.012          ops/ms
ClientSimple.existUser                       thrpt         13.453          ops/ms
ClientSimple.getUser                         thrpt         12.938          ops/ms
ClientSimple.listUser                        thrpt          8.531          ops/ms
ClientSimple.createUser                       avgt          2.494           ms/op
ClientSimple.existUser                        avgt          2.102           ms/op
ClientSimple.getUser                          avgt          2.137           ms/op
ClientSimple.listUser                         avgt          3.385           ms/op
ClientSimple.createUser                     sample  15078   2.116 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.690           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.964           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.978           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.105           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.575           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.157           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.756           ms/op
ClientSimple.existUser                      sample  15462   2.075 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.384           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.872           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.137           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.230           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.927           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.546           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.663           ms/op
ClientSimple.getUser                        sample  14538   2.264 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.905           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.138           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.765           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.826           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.738           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.106           ms/op
ClientSimple.listUser                       sample   9497   3.371 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.026           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.027           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.190           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.661           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.038           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.185           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.594           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.594           ms/op

Benchmark result is saved to 1712945335560.json
