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
# Warmup Iteration   1: 1.627 ops/ms
Iteration   1: 6.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.557 ops/ms


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
# Warmup Iteration   1: 6.164 ops/ms
Iteration   1: 12.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.364 ops/ms


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
# Warmup Iteration   1: 5.724 ops/ms
Iteration   1: 11.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.920 ops/ms


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
# Warmup Iteration   1: 5.305 ops/ms
Iteration   1: 8.467 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.467 ops/ms


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
# Warmup Iteration   1: 4.493 ±(99.9%) 0.083 ms/op
Iteration   1: 2.107 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.107 ms/op


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
# Warmup Iteration   1: 3.173 ±(99.9%) 0.054 ms/op
Iteration   1: 1.903 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.903 ms/op


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
# Warmup Iteration   1: 3.325 ±(99.9%) 0.060 ms/op
Iteration   1: 2.078 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.078 ms/op


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
# Warmup Iteration   1: 5.261 ±(99.9%) 0.096 ms/op
Iteration   1: 4.430 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.430 ms/op


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
# Warmup Iteration   1: 3.328 ±(99.9%) 0.079 ms/op
Iteration   1: 2.614 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   2.421 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   7.094 ms/op
                 createUser·p0.999:  19.516 ms/op
                 createUser·p0.9999: 20.626 ms/op
                 createUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12205
  mean =      2.614 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6652 
    [ 2.500,  5.000) = 5349 
    [ 5.000,  7.500) = 106 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     19.516 ms/op
     p(99.9900) =     20.626 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.074 ms/op
Iteration   1: 1.962 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   1.855 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.609 ms/op
                 existUser·p0.99:   3.167 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 11.688 ms/op
                 existUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16270
  mean =      1.962 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 535 
    [ 1.250,  2.500) = 14053 
    [ 2.500,  3.750) = 1571 
    [ 3.750,  5.000) = 14 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.167 ms/op
     p(99.9000) =     10.551 ms/op
     p(99.9900) =     11.688 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 3.453 ±(99.9%) 0.080 ms/op
Iteration   1: 2.256 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.134 ms/op
                 getUser·p0.90:   2.834 ms/op
                 getUser·p0.95:   3.056 ms/op
                 getUser·p0.99:   5.682 ms/op
                 getUser·p0.999:  21.430 ms/op
                 getUser·p0.9999: 22.379 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14238
  mean =      2.256 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10654 
    [ 2.500,  5.000) = 3395 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      5.682 ms/op
     p(99.9000) =     21.430 ms/op
     p(99.9900) =     22.379 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.157 ms/op
Iteration   1: 3.634 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.174 ms/op
                 listUser·p0.999:  14.306 ms/op
                 listUser·p0.9999: 14.352 ms/op
                 listUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8829
  mean =      3.634 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 374 
    [ 2.500,  3.750) = 5214 
    [ 3.750,  5.000) = 2801 
    [ 5.000,  6.250) = 321 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.174 ms/op
     p(99.9000) =     14.306 ms/op
     p(99.9900) =     14.352 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.557          ops/ms
ClientSimple.existUser                       thrpt         12.364          ops/ms
ClientSimple.getUser                         thrpt         11.920          ops/ms
ClientSimple.listUser                        thrpt          8.467          ops/ms
ClientSimple.createUser                       avgt          2.107           ms/op
ClientSimple.existUser                        avgt          1.903           ms/op
ClientSimple.getUser                          avgt          2.078           ms/op
ClientSimple.listUser                         avgt          4.430           ms/op
ClientSimple.createUser                     sample  12205   2.614 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.508           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.449           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.764           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.094           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.516           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.626           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.677           ms/op
ClientSimple.existUser                      sample  16270   1.962 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.592           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.855           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.609           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.167           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.551           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.688           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.698           ms/op
ClientSimple.getUser                        sample  14238   2.256 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.714           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.134           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.056           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.682           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.430           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.379           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.643           ms/op
ClientSimple.listUser                       sample   8829   3.634 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.041           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.407           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.174           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.306           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.352           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.352           ms/op

Benchmark result is saved to 1722732419650.json
