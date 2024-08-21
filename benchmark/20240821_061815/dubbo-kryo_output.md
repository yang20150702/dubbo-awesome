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
# Warmup Iteration   1: 2.180 ops/ms
Iteration   1: 6.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.892 ops/ms


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
# Warmup Iteration   1: 5.675 ops/ms
Iteration   1: 11.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.399 ops/ms


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
# Warmup Iteration   1: 6.138 ops/ms
Iteration   1: 13.475 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.475 ops/ms


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
# Warmup Iteration   1: 4.176 ops/ms
Iteration   1: 8.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.818 ops/ms


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.066 ms/op
Iteration   1: 2.032 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.032 ms/op


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
Iteration   1: 1.709 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.709 ms/op


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
# Warmup Iteration   1: 3.157 ±(99.9%) 0.062 ms/op
Iteration   1: 2.189 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.189 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.085 ms/op
Iteration   1: 3.238 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.238 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.106 ms/op
Iteration   1: 2.244 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.879 ms/op
                 createUser·p0.99:   8.880 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 17.724 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14240
  mean =      2.244 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 12043 
    [ 2.500,  3.750) = 1845 
    [ 3.750,  5.000) = 63 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.879 ms/op
     p(99.0000) =      8.880 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     17.724 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.765 ±(99.9%) 0.058 ms/op
Iteration   1: 1.949 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.445 ms/op
                 existUser·p0.95:   2.712 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  15.319 ms/op
                 existUser·p0.9999: 15.871 ms/op
                 existUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16404
  mean =      1.949 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 580 
    [ 1.250,  2.500) = 14368 
    [ 2.500,  3.750) = 1201 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     15.871 ms/op
     p(99.9990) =     15.892 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 3.447 ±(99.9%) 0.074 ms/op
Iteration   1: 2.057 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   1.950 ms/op
                 getUser·p0.90:   2.740 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   3.398 ms/op
                 getUser·p0.999:  12.811 ms/op
                 getUser·p0.9999: 14.130 ms/op
                 getUser·p1.00:   14.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15534
  mean =      2.057 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 599 
    [ 1.250,  2.500) = 11206 
    [ 2.500,  3.750) = 3671 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.398 ms/op
     p(99.9000) =     12.811 ms/op
     p(99.9900) =     14.130 ms/op
     p(99.9990) =     14.139 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.128 ms/op
Iteration   1: 3.422 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.112 ms/op
                 listUser·p0.50:   3.367 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.054 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 16.548 ms/op
                 listUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9343
  mean =      3.422 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 941 
    [ 2.500,  3.750) = 5543 
    [ 3.750,  5.000) = 2538 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     16.548 ms/op
     p(99.9990) =     16.548 ms/op
     p(99.9999) =     16.548 ms/op
    p(100.0000) =     16.548 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.892          ops/ms
ClientSimple.existUser                       thrpt         11.399          ops/ms
ClientSimple.getUser                         thrpt         13.475          ops/ms
ClientSimple.listUser                        thrpt          8.818          ops/ms
ClientSimple.createUser                       avgt          2.032           ms/op
ClientSimple.existUser                        avgt          1.709           ms/op
ClientSimple.getUser                          avgt          2.189           ms/op
ClientSimple.listUser                         avgt          3.238           ms/op
ClientSimple.createUser                     sample  14240   2.244 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.771           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.880           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.941           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.724           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.793           ms/op
ClientSimple.existUser                      sample  16404   1.949 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.731           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.806           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.712           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.319           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.871           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.892           ms/op
ClientSimple.getUser                        sample  15534   2.057 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.518           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.950           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.740           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.398           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.811           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.130           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.139           ms/op
ClientSimple.listUser                       sample   9343   3.422 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.112           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.367           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.054           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.073           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.548           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.548           ms/op

Benchmark result is saved to 1724220821058.json
