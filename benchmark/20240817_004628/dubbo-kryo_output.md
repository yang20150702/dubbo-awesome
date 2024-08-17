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
# Warmup Iteration   1: 1.242 ops/ms
Iteration   1: 6.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.287 ops/ms


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
# Warmup Iteration   1: 6.361 ops/ms
Iteration   1: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.834 ops/ms


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
# Warmup Iteration   1: 5.519 ops/ms
Iteration   1: 12.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.200 ops/ms


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
# Warmup Iteration   1: 3.526 ops/ms
Iteration   1: 7.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.427 ops/ms


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
# Warmup Iteration   1: 5.275 ±(99.9%) 0.127 ms/op
Iteration   1: 2.546 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.546 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.102 ms/op
Iteration   1: 2.713 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.713 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.475 ±(99.9%) 0.077 ms/op
Iteration   1: 2.000 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.000 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.129 ms/op
Iteration   1: 3.307 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.307 ms/op


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
# Warmup Iteration   1: 4.208 ±(99.9%) 0.137 ms/op
Iteration   1: 2.584 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   2.384 ms/op
                 createUser·p0.90:   3.224 ms/op
                 createUser·p0.95:   4.032 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  23.429 ms/op
                 createUser·p0.9999: 24.994 ms/op
                 createUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12356
  mean =      2.584 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7715 
    [ 2.500,  5.000) = 4414 
    [ 5.000,  7.500) = 160 
    [ 7.500, 10.000) = 28 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      2.384 ms/op
     p(90.0000) =      3.224 ms/op
     p(95.0000) =      4.032 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     24.994 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 3.464 ±(99.9%) 0.095 ms/op
Iteration   1: 1.885 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   1.839 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   4.370 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 12.885 ms/op
                 existUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16962
  mean =      1.885 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1673 
    [ 1.250,  2.500) = 14313 
    [ 2.500,  3.750) = 763 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      4.370 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     12.885 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 3.585 ±(99.9%) 0.101 ms/op
Iteration   1: 2.009 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.927 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.417 ms/op
                 getUser·p0.95:   2.680 ms/op
                 getUser·p0.99:   3.771 ms/op
                 getUser·p0.999:  17.269 ms/op
                 getUser·p0.9999: 17.693 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16112
  mean =      2.009 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 14797 
    [ 2.500,  3.750) = 1128 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.680 ms/op
     p(99.0000) =      3.771 ms/op
     p(99.9000) =     17.269 ms/op
     p(99.9900) =     17.693 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.157 ms/op
Iteration   1: 3.879 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  17.228 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8241
  mean =      3.879 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 180 
    [ 2.500,  3.750) = 3453 
    [ 3.750,  5.000) = 4169 
    [ 5.000,  6.250) = 294 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.290 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.487 ms/op
     p(99.9000) =     17.228 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     18.809 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.287          ops/ms
ClientSimple.existUser                       thrpt         12.834          ops/ms
ClientSimple.getUser                         thrpt         12.200          ops/ms
ClientSimple.listUser                        thrpt          7.427          ops/ms
ClientSimple.createUser                       avgt          2.546           ms/op
ClientSimple.existUser                        avgt          2.713           ms/op
ClientSimple.getUser                          avgt          2.000           ms/op
ClientSimple.listUser                         avgt          3.307           ms/op
ClientSimple.createUser                     sample  12356   2.584 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.085           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.224           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.032           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.463           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.429           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.994           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.002           ms/op
ClientSimple.existUser                      sample  16962   1.885 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.494           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.839           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.370           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.534           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.885           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.976           ms/op
ClientSimple.getUser                        sample  16112   2.009 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.927           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.417           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.680           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.771           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.269           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.693           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.793           ms/op
ClientSimple.listUser                       sample   8241   3.879 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.290           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.842           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.128           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.487           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.228           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.809           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.809           ms/op

Benchmark result is saved to 1723855327013.json
