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
# Warmup Iteration   1: 1.709 ops/ms
Iteration   1: 6.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.565 ops/ms


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
# Warmup Iteration   1: 6.484 ops/ms
Iteration   1: 13.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.512 ops/ms


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
# Warmup Iteration   1: 6.158 ops/ms
Iteration   1: 12.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.302 ops/ms


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
# Warmup Iteration   1: 4.621 ops/ms
Iteration   1: 8.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.858 ops/ms


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.062 ms/op
Iteration   1: 2.085 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.085 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.115 ±(99.9%) 0.048 ms/op
Iteration   1: 1.796 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.796 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.071 ms/op
Iteration   1: 2.004 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.004 ms/op


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.100 ms/op
Iteration   1: 3.781 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.781 ms/op


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
# Warmup Iteration   1: 3.246 ±(99.9%) 0.081 ms/op
Iteration   1: 2.054 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.384 ms/op
                 createUser·p0.95:   2.777 ms/op
                 createUser·p0.99:   7.357 ms/op
                 createUser·p0.999:  48.366 ms/op
                 createUser·p0.9999: 53.694 ms/op
                 createUser·p1.00:   54.460 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15571
  mean =      2.054 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15387 
    [ 5.000, 10.000) = 60 
    [10.000, 15.000) = 92 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 28 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      7.357 ms/op
     p(99.9000) =     48.366 ms/op
     p(99.9900) =     53.694 ms/op
     p(99.9990) =     54.460 ms/op
     p(99.9999) =     54.460 ms/op
    p(100.0000) =     54.460 ms/op


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
# Warmup Iteration   1: 3.020 ±(99.9%) 0.064 ms/op
Iteration   1: 1.673 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.486 ms/op
                 existUser·p0.50:   1.573 ms/op
                 existUser·p0.90:   1.853 ms/op
                 existUser·p0.95:   2.046 ms/op
                 existUser·p0.99:   3.106 ms/op
                 existUser·p0.999:  15.659 ms/op
                 existUser·p0.9999: 16.042 ms/op
                 existUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19229
  mean =      1.673 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 463 
    [ 1.250,  2.500) = 18353 
    [ 2.500,  3.750) = 236 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 64 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      1.573 ms/op
     p(90.0000) =      1.853 ms/op
     p(95.0000) =      2.046 ms/op
     p(99.0000) =      3.106 ms/op
     p(99.9000) =     15.659 ms/op
     p(99.9900) =     16.042 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.092 ms/op
Iteration   1: 2.109 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.909 ms/op
                 getUser·p0.90:   2.724 ms/op
                 getUser·p0.95:   2.990 ms/op
                 getUser·p0.99:   3.855 ms/op
                 getUser·p0.999:  14.303 ms/op
                 getUser·p0.9999: 14.811 ms/op
                 getUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15118
  mean =      2.109 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 12611 
    [ 2.500,  3.750) = 2218 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.724 ms/op
     p(95.0000) =      2.990 ms/op
     p(99.0000) =      3.855 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.149 ms/op
Iteration   1: 3.519 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.164 ms/op
                 listUser·p0.95:   4.508 ms/op
                 listUser·p0.99:   6.005 ms/op
                 listUser·p0.999:  6.405 ms/op
                 listUser·p0.9999: 7.201 ms/op
                 listUser·p1.00:   7.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9113
  mean =      3.519 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 13 
    [1.500, 2.000) = 69 
    [2.000, 2.500) = 268 
    [2.500, 3.000) = 1321 
    [3.000, 3.500) = 2633 
    [3.500, 4.000) = 3389 
    [4.000, 4.500) = 958 
    [4.500, 5.000) = 228 
    [5.000, 5.500) = 94 
    [5.500, 6.000) = 48 
    [6.000, 6.500) = 88 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.164 ms/op
     p(95.0000) =      4.508 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =      6.405 ms/op
     p(99.9900) =      7.201 ms/op
     p(99.9990) =      7.201 ms/op
     p(99.9999) =      7.201 ms/op
    p(100.0000) =      7.201 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.565          ops/ms
ClientSimple.existUser                       thrpt         13.512          ops/ms
ClientSimple.getUser                         thrpt         12.302          ops/ms
ClientSimple.listUser                        thrpt          8.858          ops/ms
ClientSimple.createUser                       avgt          2.085           ms/op
ClientSimple.existUser                        avgt          1.796           ms/op
ClientSimple.getUser                          avgt          2.004           ms/op
ClientSimple.listUser                         avgt          3.781           ms/op
ClientSimple.createUser                     sample  15571   2.054 ± 0.061   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.477           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.384           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.357           ms/op
ClientSimple.createUser:createUser·p0.999   sample         48.366           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         53.694           ms/op
ClientSimple.createUser:createUser·p1.00    sample         54.460           ms/op
ClientSimple.existUser                      sample  19229   1.673 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.486           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.573           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.853           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.046           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.106           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.659           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.042           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.073           ms/op
ClientSimple.getUser                        sample  15118   2.109 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.909           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.990           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.855           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.303           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.811           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.811           ms/op
ClientSimple.listUser                       sample   9113   3.519 ± 0.022   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.063           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.164           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.508           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.005           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.405           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.201           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.201           ms/op

Benchmark result is saved to 1723313494002.json
