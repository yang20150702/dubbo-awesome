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
# Warmup Iteration   1: 1.840 ops/ms
Iteration   1: 7.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.479 ops/ms


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
# Warmup Iteration   1: 7.344 ops/ms
Iteration   1: 13.256 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.256 ops/ms


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
# Warmup Iteration   1: 6.528 ops/ms
Iteration   1: 13.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.349 ops/ms


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
# Warmup Iteration   1: 5.169 ops/ms
Iteration   1: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.904 ops/ms


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.065 ms/op
Iteration   1: 2.160 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.160 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.050 ms/op
Iteration   1: 2.155 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.155 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.324 ±(99.9%) 0.053 ms/op
Iteration   1: 2.235 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.235 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.076 ms/op
Iteration   1: 3.280 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.280 ms/op


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
# Warmup Iteration   1: 3.598 ±(99.9%) 0.094 ms/op
Iteration   1: 2.093 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   1.985 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.855 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  14.026 ms/op
                 createUser·p0.9999: 15.274 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15277
  mean =      2.093 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 575 
    [ 1.250,  2.500) = 12576 
    [ 2.500,  3.750) = 1892 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      1.985 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.855 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     14.026 ms/op
     p(99.9900) =     15.274 ms/op
     p(99.9990) =     15.352 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.005 ±(99.9%) 0.068 ms/op
Iteration   1: 1.899 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   3.342 ms/op
                 existUser·p0.999:  18.054 ms/op
                 existUser·p0.9999: 18.238 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17026
  mean =      1.899 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 14469 
    [ 2.500,  3.750) = 2217 
    [ 3.750,  5.000) = 49 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      3.342 ms/op
     p(99.9000) =     18.054 ms/op
     p(99.9900) =     18.238 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.085 ms/op
Iteration   1: 1.947 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.507 ms/op
                 getUser·p0.50:   1.827 ms/op
                 getUser·p0.90:   2.572 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 12.412 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16449
  mean =      1.947 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 430 
    [ 1.250,  2.500) = 14006 
    [ 2.500,  3.750) = 1854 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 3 
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
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     12.412 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.534 ±(99.9%) 0.142 ms/op
Iteration   1: 3.366 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.989 ms/op
                 listUser·p0.50:   3.289 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   6.152 ms/op
                 listUser·p0.999:  9.863 ms/op
                 listUser·p0.9999: 10.109 ms/op
                 listUser·p1.00:   10.109 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9510
  mean =      3.366 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 93 
    [ 2.000,  3.000) = 3761 
    [ 3.000,  4.000) = 3671 
    [ 4.000,  5.000) = 1695 
    [ 5.000,  6.000) = 174 
    [ 6.000,  7.000) = 44 
    [ 7.000,  8.000) = 26 
    [ 8.000,  9.000) = 14 
    [ 9.000, 10.000) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.989 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =      9.863 ms/op
     p(99.9900) =     10.109 ms/op
     p(99.9990) =     10.109 ms/op
     p(99.9999) =     10.109 ms/op
    p(100.0000) =     10.109 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.479          ops/ms
ClientSimple.existUser                       thrpt         13.256          ops/ms
ClientSimple.getUser                         thrpt         13.349          ops/ms
ClientSimple.listUser                        thrpt          8.904          ops/ms
ClientSimple.createUser                       avgt          2.160           ms/op
ClientSimple.existUser                        avgt          2.155           ms/op
ClientSimple.getUser                          avgt          2.235           ms/op
ClientSimple.listUser                         avgt          3.280           ms/op
ClientSimple.createUser                     sample  15277   2.093 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.555           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.985           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.251           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.026           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.274           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.352           ms/op
ClientSimple.existUser                      sample  17026   1.899 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.728           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.342           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.054           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.238           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.285           ms/op
ClientSimple.getUser                        sample  16449   1.947 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.507           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.827           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.731           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.977           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.412           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample   9510   3.366 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.989           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.289           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.678           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.152           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.863           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.109           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.109           ms/op

Benchmark result is saved to 1723292184724.json
