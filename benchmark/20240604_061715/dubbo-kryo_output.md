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
# Warmup Iteration   1: 1.916 ops/ms
Iteration   1: 6.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.859 ops/ms


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
# Warmup Iteration   1: 5.110 ops/ms
Iteration   1: 14.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.381 ops/ms


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
# Warmup Iteration   1: 5.471 ops/ms
Iteration   1: 11.969 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.969 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ops/ms
Iteration   1: 8.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.028 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.409 ±(99.9%) 0.066 ms/op
Iteration   1: 2.059 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.059 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.058 ms/op
Iteration   1: 1.935 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.935 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.063 ms/op
Iteration   1: 1.917 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.917 ms/op


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
# Warmup Iteration   1: 5.062 ±(99.9%) 0.099 ms/op
Iteration   1: 3.616 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.616 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.076 ms/op
Iteration   1: 2.432 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.871 ms/op
                 createUser·p0.95:   3.323 ms/op
                 createUser·p0.99:   8.518 ms/op
                 createUser·p0.999:  25.511 ms/op
                 createUser·p0.9999: 27.303 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13155
  mean =      2.432 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10188 
    [ 2.500,  5.000) = 2704 
    [ 5.000,  7.500) = 103 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.323 ms/op
     p(99.0000) =      8.518 ms/op
     p(99.9000) =     25.511 ms/op
     p(99.9900) =     27.303 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 2.871 ±(99.9%) 0.060 ms/op
Iteration   1: 1.910 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   1.726 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  12.571 ms/op
                 existUser·p0.9999: 12.958 ms/op
                 existUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16743
  mean =      1.910 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 377 
    [ 1.250,  2.500) = 14946 
    [ 2.500,  3.750) = 1173 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 112 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.726 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =     12.571 ms/op
     p(99.9900) =     12.958 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 3.101 ±(99.9%) 0.070 ms/op
Iteration   1: 2.169 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   2.105 ms/op
                 getUser·p0.90:   2.814 ms/op
                 getUser·p0.95:   3.060 ms/op
                 getUser·p0.99:   5.059 ms/op
                 getUser·p0.999:  19.945 ms/op
                 getUser·p0.9999: 20.137 ms/op
                 getUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14774
  mean =      2.169 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11379 
    [ 2.500,  5.000) = 3245 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.814 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      5.059 ms/op
     p(99.9000) =     19.945 ms/op
     p(99.9900) =     20.137 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 4.435 ±(99.9%) 0.119 ms/op
Iteration   1: 3.499 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.543 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  7.168 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   10.699 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9160
  mean =      3.499 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 151 
    [ 2.000,  3.000) = 2724 
    [ 3.000,  4.000) = 4129 
    [ 4.000,  5.000) = 1898 
    [ 5.000,  6.000) = 92 
    [ 6.000,  7.000) = 129 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 2 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =      7.168 ms/op
     p(99.9900) =     10.699 ms/op
     p(99.9990) =     10.699 ms/op
     p(99.9999) =     10.699 ms/op
    p(100.0000) =     10.699 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.859          ops/ms
ClientSimple.existUser                       thrpt         14.381          ops/ms
ClientSimple.getUser                         thrpt         11.969          ops/ms
ClientSimple.listUser                        thrpt          8.028          ops/ms
ClientSimple.createUser                       avgt          2.059           ms/op
ClientSimple.existUser                        avgt          1.935           ms/op
ClientSimple.getUser                          avgt          1.917           ms/op
ClientSimple.listUser                         avgt          3.616           ms/op
ClientSimple.createUser                     sample  13155   2.432 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.744           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.871           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.323           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.518           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.511           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.303           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.623           ms/op
ClientSimple.existUser                      sample  16743   1.910 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.623           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.726           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.923           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.571           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.958           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.124           ms/op
ClientSimple.getUser                        sample  14774   2.169 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.490           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.105           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.814           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.060           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.059           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.945           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.137           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.152           ms/op
ClientSimple.listUser                       sample   9160   3.499 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.198           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.543           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.375           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.562           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.168           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.699           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.699           ms/op

Benchmark result is saved to 1717481568207.json
