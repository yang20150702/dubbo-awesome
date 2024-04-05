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
# Warmup Iteration   1: 1.755 ops/ms
Iteration   1: 6.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.339 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ops/ms
Iteration   1: 12.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.290 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.345 ops/ms
Iteration   1: 13.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.584 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 8.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.786 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.106 ms/op
Iteration   1: 2.324 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.324 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.145 ±(99.9%) 0.048 ms/op
Iteration   1: 1.674 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.674 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.354 ±(99.9%) 0.057 ms/op
Iteration   1: 2.116 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.116 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.683 ±(99.9%) 0.148 ms/op
Iteration   1: 3.722 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.722 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.074 ±(99.9%) 0.126 ms/op
Iteration   1: 2.038 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   1.851 ms/op
                 createUser·p0.90:   2.466 ms/op
                 createUser·p0.95:   2.679 ms/op
                 createUser·p0.99:   11.198 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15716
  mean =      2.038 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 777 
    [ 1.250,  2.500) = 13544 
    [ 2.500,  3.750) = 1042 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      1.851 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =     11.198 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.118 ±(99.9%) 0.076 ms/op
Iteration   1: 2.065 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.407 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.527 ms/op
                 existUser·p0.95:   2.658 ms/op
                 existUser·p0.99:   3.848 ms/op
                 existUser·p0.999:  27.329 ms/op
                 existUser·p0.9999: 27.748 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15480
  mean =      2.065 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13627 
    [ 2.500,  5.000) = 1750 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.407 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      3.848 ms/op
     p(99.9000) =     27.329 ms/op
     p(99.9900) =     27.748 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.091 ms/op
Iteration   1: 2.091 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.774 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.519 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   4.677 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 11.460 ms/op
                 getUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15412
  mean =      2.091 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 176 
    [ 1.250,  2.500) = 13558 
    [ 2.500,  3.750) = 1428 
    [ 3.750,  5.000) = 144 
    [ 5.000,  6.250) = 25 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      4.677 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     11.460 ms/op
     p(99.9990) =     11.469 ms/op
     p(99.9999) =     11.469 ms/op
    p(100.0000) =     11.469 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.128 ms/op
Iteration   1: 3.155 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   0.736 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.186 ms/op
                 listUser·p0.99:   5.179 ms/op
                 listUser·p0.999:  6.363 ms/op
                 listUser·p0.9999: 8.825 ms/op
                 listUser·p1.00:   8.847 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10175
  mean =      3.155 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 2 
    [1.500, 2.000) = 71 
    [2.000, 2.500) = 482 
    [2.500, 3.000) = 4527 
    [3.000, 3.500) = 2895 
    [3.500, 4.000) = 1420 
    [4.000, 4.500) = 567 
    [4.500, 5.000) = 74 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 43 
    [6.000, 6.500) = 25 
    [6.500, 7.000) = 3 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.736 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.186 ms/op
     p(99.0000) =      5.179 ms/op
     p(99.9000) =      6.363 ms/op
     p(99.9900) =      8.825 ms/op
     p(99.9990) =      8.847 ms/op
     p(99.9999) =      8.847 ms/op
    p(100.0000) =      8.847 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.339          ops/ms
ClientSimple.existUser                       thrpt         12.290          ops/ms
ClientSimple.getUser                         thrpt         13.584          ops/ms
ClientSimple.listUser                        thrpt          8.786          ops/ms
ClientSimple.createUser                       avgt          2.324           ms/op
ClientSimple.existUser                        avgt          1.674           ms/op
ClientSimple.getUser                          avgt          2.116           ms/op
ClientSimple.listUser                         avgt          3.722           ms/op
ClientSimple.createUser                     sample  15716   2.038 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.572           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.851           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.679           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.198           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.892           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.843           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.843           ms/op
ClientSimple.existUser                      sample  15480   2.065 ± 0.035   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.407           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.527           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.658           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.848           ms/op
ClientSimple.existUser:existUser·p0.999     sample         27.329           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         27.748           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.820           ms/op
ClientSimple.getUser                        sample  15412   2.091 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.774           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.519           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.677           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.460           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.469           ms/op
ClientSimple.listUser                       sample  10175   3.155 ± 0.018   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.736           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.002           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.912           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.179           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.363           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.825           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.847           ms/op

Benchmark result is saved to 1712319278948.json
