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
# Warmup Iteration   1: 0.924 ops/ms
Iteration   1: 5.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.284 ops/ms


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
# Warmup Iteration   1: 5.158 ops/ms
Iteration   1: 10.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.874 ops/ms


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
# Warmup Iteration   1: 4.811 ops/ms
Iteration   1: 11.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.903 ops/ms


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
# Warmup Iteration   1: 4.841 ops/ms
Iteration   1: 8.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.801 ops/ms


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.060 ms/op
Iteration   1: 2.070 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.070 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.054 ms/op
Iteration   1: 2.163 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.163 ms/op


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.073 ms/op
Iteration   1: 2.200 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.200 ms/op


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
# Warmup Iteration   1: 4.585 ±(99.9%) 0.107 ms/op
Iteration   1: 3.366 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.366 ms/op


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
# Warmup Iteration   1: 3.940 ±(99.9%) 0.090 ms/op
Iteration   1: 2.677 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   2.466 ms/op
                 createUser·p0.90:   3.260 ms/op
                 createUser·p0.95:   3.589 ms/op
                 createUser·p0.99:   9.234 ms/op
                 createUser·p0.999:  25.004 ms/op
                 createUser·p0.9999: 25.915 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11937
  mean =      2.677 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6265 
    [ 2.500,  5.000) = 5338 
    [ 5.000,  7.500) = 174 
    [ 7.500, 10.000) = 53 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.589 ms/op
     p(99.0000) =      9.234 ms/op
     p(99.9000) =     25.004 ms/op
     p(99.9900) =     25.915 ms/op
     p(99.9990) =     25.985 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.080 ms/op
Iteration   1: 2.015 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   2.009 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.650 ms/op
                 existUser·p0.99:   3.569 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 12.568 ms/op
                 existUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15868
  mean =      2.015 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 636 
    [ 1.250,  2.500) = 13869 
    [ 2.500,  3.750) = 1291 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      2.009 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      3.569 ms/op
     p(99.9000) =     11.223 ms/op
     p(99.9900) =     12.568 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.083 ms/op
Iteration   1: 1.817 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.462 ms/op
                 getUser·p0.50:   1.640 ms/op
                 getUser·p0.90:   2.189 ms/op
                 getUser·p0.95:   2.470 ms/op
                 getUser·p0.99:   4.171 ms/op
                 getUser·p0.999:  30.376 ms/op
                 getUser·p0.9999: 31.161 ms/op
                 getUser·p1.00:   31.261 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17585
  mean =      1.817 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16754 
    [ 2.500,  5.000) = 720 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.189 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      4.171 ms/op
     p(99.9000) =     30.376 ms/op
     p(99.9900) =     31.161 ms/op
     p(99.9990) =     31.261 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.138 ms/op
Iteration   1: 3.715 ±(99.9%) 0.152 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   6.151 ms/op
                 listUser·p0.999:  80.972 ms/op
                 listUser·p0.9999: 91.619 ms/op
                 listUser·p1.00:   91.619 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8601
  mean =      3.715 ±(99.9%) 0.152 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 8540 
    [ 10.000,  20.000) = 7 
    [ 20.000,  30.000) = 2 
    [ 30.000,  40.000) = 10 
    [ 40.000,  50.000) = 15 
    [ 50.000,  60.000) = 11 
    [ 60.000,  70.000) = 6 
    [ 70.000,  80.000) = 1 
    [ 80.000,  90.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.151 ms/op
     p(99.9000) =     80.972 ms/op
     p(99.9900) =     91.619 ms/op
     p(99.9990) =     91.619 ms/op
     p(99.9999) =     91.619 ms/op
    p(100.0000) =     91.619 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.284          ops/ms
ClientSimple.existUser                       thrpt         10.874          ops/ms
ClientSimple.getUser                         thrpt         11.903          ops/ms
ClientSimple.listUser                        thrpt          8.801          ops/ms
ClientSimple.createUser                       avgt          2.070           ms/op
ClientSimple.existUser                        avgt          2.163           ms/op
ClientSimple.getUser                          avgt          2.200           ms/op
ClientSimple.listUser                         avgt          3.366           ms/op
ClientSimple.createUser                     sample  11937   2.677 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.660           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.466           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.260           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.589           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.234           ms/op
ClientSimple.createUser:createUser·p0.999   sample         25.004           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.915           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.985           ms/op
ClientSimple.existUser                      sample  15868   2.015 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.724           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.009           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.569           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.223           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.568           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.616           ms/op
ClientSimple.getUser                        sample  17585   1.817 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.462           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.640           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.189           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.171           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.376           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         31.161           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.261           ms/op
ClientSimple.listUser                       sample   8601   3.715 ± 0.152   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.169           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.355           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.151           ms/op
ClientSimple.listUser:listUser·p0.999       sample         80.972           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         91.619           ms/op
ClientSimple.listUser:listUser·p1.00        sample         91.619           ms/op

Benchmark result is saved to 1710981482647.json
