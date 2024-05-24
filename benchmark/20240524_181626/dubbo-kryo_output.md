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
# Warmup Iteration   1: 1.230 ops/ms
Iteration   1: 5.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.671 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.025 ops/ms
Iteration   1: 10.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.455 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.190 ops/ms
Iteration   1: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.498 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.531 ops/ms
Iteration   1: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.607 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.080 ms/op
Iteration   1: 2.597 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.597 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ±(99.9%) 0.054 ms/op
Iteration   1: 2.088 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.088 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.565 ±(99.9%) 0.068 ms/op
Iteration   1: 2.274 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.274 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.862 ±(99.9%) 0.120 ms/op
Iteration   1: 3.904 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.904 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.114 ms/op
Iteration   1: 2.489 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   3.183 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   11.888 ms/op
                 createUser·p0.999:  18.907 ms/op
                 createUser·p0.9999: 20.467 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12921
  mean =      2.489 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8490 
    [ 2.500,  5.000) = 4021 
    [ 5.000,  7.500) = 260 
    [ 7.500, 10.000) = 17 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =     11.888 ms/op
     p(99.9000) =     18.907 ms/op
     p(99.9900) =     20.467 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.153 ±(99.9%) 0.074 ms/op
Iteration   1: 2.029 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.505 ms/op
                 existUser·p0.50:   1.911 ms/op
                 existUser·p0.90:   2.617 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  18.200 ms/op
                 existUser·p0.9999: 19.159 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15795
  mean =      2.029 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 656 
    [ 1.250,  2.500) = 12800 
    [ 2.500,  3.750) = 2117 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     18.200 ms/op
     p(99.9900) =     19.159 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.104 ms/op
Iteration   1: 2.419 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.277 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   6.305 ms/op
                 getUser·p0.999:  12.464 ms/op
                 getUser·p0.9999: 12.971 ms/op
                 getUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13236
  mean =      2.419 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 8688 
    [ 2.500,  3.750) = 4145 
    [ 3.750,  5.000) = 103 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.277 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.269 ms/op
     p(99.0000) =      6.305 ms/op
     p(99.9000) =     12.464 ms/op
     p(99.9900) =     12.971 ms/op
     p(99.9990) =     12.976 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


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
# Warmup Iteration   1: 5.472 ±(99.9%) 0.173 ms/op
Iteration   1: 3.289 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.212 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.495 ms/op
                 listUser·p0.999:  14.588 ms/op
                 listUser·p0.9999: 14.746 ms/op
                 listUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9720
  mean =      3.289 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 829 
    [ 2.500,  3.750) = 6796 
    [ 3.750,  5.000) = 1748 
    [ 5.000,  6.250) = 212 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.495 ms/op
     p(99.9000) =     14.588 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.671          ops/ms
ClientSimple.existUser                       thrpt         10.455          ops/ms
ClientSimple.getUser                         thrpt         10.498          ops/ms
ClientSimple.listUser                        thrpt          8.607          ops/ms
ClientSimple.createUser                       avgt          2.597           ms/op
ClientSimple.existUser                        avgt          2.088           ms/op
ClientSimple.getUser                          avgt          2.274           ms/op
ClientSimple.listUser                         avgt          3.904           ms/op
ClientSimple.createUser                     sample  12921   2.489 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.601           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.183           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.793           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.888           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.907           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.467           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.611           ms/op
ClientSimple.existUser                      sample  15795   2.029 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.505           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.911           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.818           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.407           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.200           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.159           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.235           ms/op
ClientSimple.getUser                        sample  13236   2.419 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.860           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.277           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.986           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.269           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.305           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.464           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.971           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.976           ms/op
ClientSimple.listUser                       sample   9720   3.289 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.212           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.495           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.588           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.746           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.746           ms/op

Benchmark result is saved to 1716574320452.json
