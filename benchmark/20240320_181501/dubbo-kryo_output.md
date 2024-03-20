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
# Warmup Iteration   1: 1.499 ops/ms
Iteration   1: 7.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.136 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.393 ops/ms
Iteration   1: 11.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.795 ops/ms


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
# Warmup Iteration   1: 4.531 ops/ms
Iteration   1: 10.507 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.507 ops/ms


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
# Warmup Iteration   1: 5.185 ops/ms
Iteration   1: 8.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.697 ops/ms


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
# Warmup Iteration   1: 4.322 ±(99.9%) 0.086 ms/op
Iteration   1: 2.267 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.267 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.064 ms/op
Iteration   1: 1.942 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.942 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.079 ms/op
Iteration   1: 2.042 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 5.163 ±(99.9%) 0.220 ms/op
Iteration   1: 3.757 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.757 ms/op


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
# Warmup Iteration   1: 3.568 ±(99.9%) 0.087 ms/op
Iteration   1: 2.195 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.530 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   3.367 ms/op
                 createUser·p0.99:   7.071 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 19.958 ms/op
                 createUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14576
  mean =      2.195 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 240 
    [ 1.250,  2.500) = 11846 
    [ 2.500,  3.750) = 1896 
    [ 3.750,  5.000) = 199 
    [ 5.000,  6.250) = 171 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.367 ms/op
     p(99.0000) =      7.071 ms/op
     p(99.9000) =     19.464 ms/op
     p(99.9900) =     19.958 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 2.856 ±(99.9%) 0.070 ms/op
Iteration   1: 2.028 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.359 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   4.231 ms/op
                 existUser·p0.999:  32.571 ms/op
                 existUser·p0.9999: 33.738 ms/op
                 existUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15909
  mean =      2.028 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13998 
    [ 2.500,  5.000) = 1778 
    [ 5.000,  7.500) = 69 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      4.231 ms/op
     p(99.9000) =     32.571 ms/op
     p(99.9900) =     33.738 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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
# Warmup Iteration   1: 3.683 ±(99.9%) 0.099 ms/op
Iteration   1: 2.071 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.435 ms/op
                 getUser·p0.50:   1.985 ms/op
                 getUser·p0.90:   2.494 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   3.760 ms/op
                 getUser·p0.999:  11.411 ms/op
                 getUser·p0.9999: 12.639 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15506
  mean =      2.071 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 13919 
    [ 2.500,  3.750) = 1354 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.435 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =     11.411 ms/op
     p(99.9900) =     12.639 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.124 ms/op
Iteration   1: 3.926 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  15.661 ms/op
                 listUser·p0.9999: 15.745 ms/op
                 listUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8159
  mean =      3.926 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 297 
    [ 2.500,  3.750) = 2921 
    [ 3.750,  5.000) = 4438 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.136 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     15.661 ms/op
     p(99.9900) =     15.745 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.136          ops/ms
ClientSimple.existUser                       thrpt         11.795          ops/ms
ClientSimple.getUser                         thrpt         10.507          ops/ms
ClientSimple.listUser                        thrpt          8.697          ops/ms
ClientSimple.createUser                       avgt          2.267           ms/op
ClientSimple.existUser                        avgt          1.942           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.757           ms/op
ClientSimple.createUser                     sample  14576   2.195 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.530           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.367           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.071           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.464           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.958           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.988           ms/op
ClientSimple.existUser                      sample  15909   2.028 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.359           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.231           ms/op
ClientSimple.existUser:existUser·p0.999     sample         32.571           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         33.738           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.144           ms/op
ClientSimple.getUser                        sample  15506   2.071 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.435           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.985           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.494           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.760           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.411           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.639           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.648           ms/op
ClientSimple.listUser                       sample   8159   3.926 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.167           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.903           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.136           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.422           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.661           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.745           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.745           ms/op

Benchmark result is saved to 1710958240329.json
