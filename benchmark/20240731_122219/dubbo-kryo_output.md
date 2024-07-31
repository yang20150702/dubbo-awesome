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
# Warmup Iteration   1: 2.048 ops/ms
Iteration   1: 6.464 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.464 ops/ms


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
# Warmup Iteration   1: 5.970 ops/ms
Iteration   1: 13.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.126 ops/ms


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
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 13.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.185 ops/ms


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
# Warmup Iteration   1: 4.781 ops/ms
Iteration   1: 7.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.987 ops/ms


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.068 ms/op
Iteration   1: 2.133 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.133 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.060 ms/op
Iteration   1: 1.833 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.054 ms/op
Iteration   1: 1.954 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.954 ms/op


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
# Warmup Iteration   1: 4.226 ±(99.9%) 0.085 ms/op
Iteration   1: 3.421 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.421 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.086 ms/op
Iteration   1: 2.540 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.421 ms/op
                 createUser·p0.90:   2.949 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  22.808 ms/op
                 createUser·p0.9999: 23.606 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12590
  mean =      2.540 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7141 
    [ 2.500,  5.000) = 5268 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.949 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      9.617 ms/op
     p(99.9000) =     22.808 ms/op
     p(99.9900) =     23.606 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 3.077 ±(99.9%) 0.070 ms/op
Iteration   1: 2.025 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.503 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   3.438 ms/op
                 existUser·p0.999:  12.943 ms/op
                 existUser·p0.9999: 13.341 ms/op
                 existUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15929
  mean =      2.025 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 13549 
    [ 2.500,  3.750) = 1968 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.438 ms/op
     p(99.9000) =     12.943 ms/op
     p(99.9900) =     13.341 ms/op
     p(99.9990) =     13.730 ms/op
     p(99.9999) =     13.730 ms/op
    p(100.0000) =     13.730 ms/op


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
# Warmup Iteration   1: 3.273 ±(99.9%) 0.076 ms/op
Iteration   1: 1.958 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   1.870 ms/op
                 getUser·p0.90:   2.228 ms/op
                 getUser·p0.95:   2.501 ms/op
                 getUser·p0.99:   3.135 ms/op
                 getUser·p0.999:  14.478 ms/op
                 getUser·p0.9999: 15.173 ms/op
                 getUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16328
  mean =      1.958 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 15427 
    [ 2.500,  3.750) = 715 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.228 ms/op
     p(95.0000) =      2.501 ms/op
     p(99.0000) =      3.135 ms/op
     p(99.9000) =     14.478 ms/op
     p(99.9900) =     15.173 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.117 ms/op
Iteration   1: 3.766 ±(99.9%) 0.100 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.591 ms/op
                 listUser·p0.99:   6.600 ms/op
                 listUser·p0.999:  48.230 ms/op
                 listUser·p0.9999: 49.349 ms/op
                 listUser·p1.00:   49.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8531
  mean =      3.766 ±(99.9%) 0.100 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8237 
    [ 5.000, 10.000) = 262 
    [10.000, 15.000) = 0 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.591 ms/op
     p(99.0000) =      6.600 ms/op
     p(99.9000) =     48.230 ms/op
     p(99.9900) =     49.349 ms/op
     p(99.9990) =     49.349 ms/op
     p(99.9999) =     49.349 ms/op
    p(100.0000) =     49.349 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.464          ops/ms
ClientSimple.existUser                       thrpt         13.126          ops/ms
ClientSimple.getUser                         thrpt         13.185          ops/ms
ClientSimple.listUser                        thrpt          7.987          ops/ms
ClientSimple.createUser                       avgt          2.133           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          1.954           ms/op
ClientSimple.listUser                         avgt          3.421           ms/op
ClientSimple.createUser                     sample  12590   2.540 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.640           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.421           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.949           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.121           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.617           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.808           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.606           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.691           ms/op
ClientSimple.existUser                      sample  15929   2.025 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.503           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.438           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.943           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.341           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.730           ms/op
ClientSimple.getUser                        sample  16328   1.958 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.870           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.228           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.501           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.135           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.478           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.173           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.401           ms/op
ClientSimple.listUser                       sample   8531   3.766 ± 0.100   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.887           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.654           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.591           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.600           ms/op
ClientSimple.listUser:listUser·p0.999       sample         48.230           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         49.349           ms/op
ClientSimple.listUser:listUser·p1.00        sample         49.349           ms/op

Benchmark result is saved to 1722428268344.json
