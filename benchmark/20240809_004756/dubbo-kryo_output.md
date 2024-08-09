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
# Warmup Iteration   1: 1.740 ops/ms
Iteration   1: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.040 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.750 ops/ms
Iteration   1: 12.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.030 ops/ms


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
# Warmup Iteration   1: 5.603 ops/ms
Iteration   1: 13.799 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.799 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 7.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.842 ops/ms


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
# Warmup Iteration   1: 3.671 ±(99.9%) 0.046 ms/op
Iteration   1: 2.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.172 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.051 ms/op
Iteration   1: 1.852 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.852 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.357 ±(99.9%) 0.061 ms/op
Iteration   1: 2.202 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.202 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.504 ±(99.9%) 0.088 ms/op
Iteration   1: 3.311 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.311 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.404 ±(99.9%) 0.072 ms/op
Iteration   1: 2.158 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.630 ms/op
                 createUser·p0.95:   2.826 ms/op
                 createUser·p0.99:   3.681 ms/op
                 createUser·p0.999:  19.667 ms/op
                 createUser·p0.9999: 20.416 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14819
  mean =      2.158 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12562 
    [ 2.500,  5.000) = 2156 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.826 ms/op
     p(99.0000) =      3.681 ms/op
     p(99.9000) =     19.667 ms/op
     p(99.9900) =     20.416 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.170 ±(99.9%) 0.076 ms/op
Iteration   1: 1.817 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.565 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.433 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   3.220 ms/op
                 existUser·p0.999:  10.748 ms/op
                 existUser·p0.9999: 11.289 ms/op
                 existUser·p1.00:   11.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17593
  mean =      1.817 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3318 
    [ 1.250,  2.500) = 12786 
    [ 2.500,  3.750) = 1340 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 10 
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
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.433 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      3.220 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     11.289 ms/op
     p(99.9990) =     11.551 ms/op
     p(99.9999) =     11.551 ms/op
    p(100.0000) =     11.551 ms/op


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
# Warmup Iteration   1: 3.160 ±(99.9%) 0.078 ms/op
Iteration   1: 1.920 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.602 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.380 ms/op
                 getUser·p0.95:   2.507 ms/op
                 getUser·p0.99:   3.203 ms/op
                 getUser·p0.999:  16.027 ms/op
                 getUser·p0.9999: 16.321 ms/op
                 getUser·p1.00:   16.499 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16795
  mean =      1.920 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 382 
    [ 1.250,  2.500) = 15552 
    [ 2.500,  3.750) = 724 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.203 ms/op
     p(99.9000) =     16.027 ms/op
     p(99.9900) =     16.321 ms/op
     p(99.9990) =     16.499 ms/op
     p(99.9999) =     16.499 ms/op
    p(100.0000) =     16.499 ms/op


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.121 ms/op
Iteration   1: 3.449 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.927 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.344 ms/op
                 listUser·p0.999:  6.217 ms/op
                 listUser·p0.9999: 6.824 ms/op
                 listUser·p1.00:   6.824 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9260
  mean =      3.449 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 35 
    [1.500, 2.000) = 169 
    [2.000, 2.500) = 727 
    [2.500, 3.000) = 1544 
    [3.000, 3.500) = 1719 
    [3.500, 4.000) = 3352 
    [4.000, 4.500) = 1277 
    [4.500, 5.000) = 284 
    [5.000, 5.500) = 100 
    [5.500, 6.000) = 40 
    [6.000, 6.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.927 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.344 ms/op
     p(99.9000) =      6.217 ms/op
     p(99.9900) =      6.824 ms/op
     p(99.9990) =      6.824 ms/op
     p(99.9999) =      6.824 ms/op
    p(100.0000) =      6.824 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.040          ops/ms
ClientSimple.existUser                       thrpt         12.030          ops/ms
ClientSimple.getUser                         thrpt         13.799          ops/ms
ClientSimple.listUser                        thrpt          7.842          ops/ms
ClientSimple.createUser                       avgt          2.172           ms/op
ClientSimple.existUser                        avgt          1.852           ms/op
ClientSimple.getUser                          avgt          2.202           ms/op
ClientSimple.listUser                         avgt          3.311           ms/op
ClientSimple.createUser                     sample  14819   2.158 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.630           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.826           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.681           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.667           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.416           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.447           ms/op
ClientSimple.existUser                      sample  17593   1.817 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.565           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.433           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.220           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.748           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.289           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.551           ms/op
ClientSimple.getUser                        sample  16795   1.920 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.602           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.380           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.507           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.203           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.027           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.321           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.499           ms/op
ClientSimple.listUser                       sample   9260   3.449 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.927           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.344           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.217           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          6.824           ms/op
ClientSimple.listUser:listUser·p1.00        sample          6.824           ms/op

Benchmark result is saved to 1723164229127.json
