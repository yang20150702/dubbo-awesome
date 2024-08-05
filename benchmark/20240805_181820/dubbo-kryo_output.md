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
# Warmup Iteration   1: 1.629 ops/ms
Iteration   1: 6.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.128 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.121 ops/ms
Iteration   1: 12.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.543 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.102 ops/ms
Iteration   1: 9.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.718 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.810 ops/ms
Iteration   1: 7.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.570 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.607 ±(99.9%) 0.090 ms/op
Iteration   1: 2.237 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.237 ms/op


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.068 ms/op
Iteration   1: 2.076 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.076 ms/op


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
# Warmup Iteration   1: 3.619 ±(99.9%) 0.069 ms/op
Iteration   1: 1.931 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.931 ms/op


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
# Warmup Iteration   1: 5.019 ±(99.9%) 0.123 ms/op
Iteration   1: 3.831 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.831 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.077 ms/op
Iteration   1: 2.091 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.621 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.347 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   6.023 ms/op
                 createUser·p0.999:  30.531 ms/op
                 createUser·p0.9999: 31.288 ms/op
                 createUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15278
  mean =      2.091 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14227 
    [ 2.500,  5.000) = 856 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      6.023 ms/op
     p(99.9000) =     30.531 ms/op
     p(99.9900) =     31.288 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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
# Warmup Iteration   1: 2.908 ±(99.9%) 0.064 ms/op
Iteration   1: 1.764 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.465 ms/op
                 existUser·p0.99:   3.359 ms/op
                 existUser·p0.999:  11.050 ms/op
                 existUser·p0.9999: 12.136 ms/op
                 existUser·p1.00:   12.272 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18282
  mean =      1.764 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 384 
    [ 1.250,  2.500) = 17059 
    [ 2.500,  3.750) = 770 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.465 ms/op
     p(99.0000) =      3.359 ms/op
     p(99.9000) =     11.050 ms/op
     p(99.9900) =     12.136 ms/op
     p(99.9990) =     12.272 ms/op
     p(99.9999) =     12.272 ms/op
    p(100.0000) =     12.272 ms/op


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
# Warmup Iteration   1: 3.466 ±(99.9%) 0.087 ms/op
Iteration   1: 1.906 ±(99.9%) 0.036 ms/op
                 getUser·p0.00:   0.590 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.317 ms/op
                 getUser·p0.95:   2.707 ms/op
                 getUser·p0.99:   3.594 ms/op
                 getUser·p0.999:  28.025 ms/op
                 getUser·p0.9999: 29.499 ms/op
                 getUser·p1.00:   29.590 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16872
  mean =      1.906 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15644 
    [ 2.500,  5.000) = 1140 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.317 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      3.594 ms/op
     p(99.9000) =     28.025 ms/op
     p(99.9900) =     29.499 ms/op
     p(99.9990) =     29.590 ms/op
     p(99.9999) =     29.590 ms/op
    p(100.0000) =     29.590 ms/op


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
# Warmup Iteration   1: 4.275 ±(99.9%) 0.114 ms/op
Iteration   1: 3.487 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.416 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.622 ms/op
                 listUser·p0.99:   8.540 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 14.041 ms/op
                 listUser·p1.00:   14.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9175
  mean =      3.487 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 948 
    [ 2.500,  3.750) = 5299 
    [ 3.750,  5.000) = 2582 
    [ 5.000,  6.250) = 124 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.622 ms/op
     p(99.0000) =      8.540 ms/op
     p(99.9000) =     14.008 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.041 ms/op
    p(100.0000) =     14.041 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.128          ops/ms
ClientSimple.existUser                       thrpt         12.543          ops/ms
ClientSimple.getUser                         thrpt          9.718          ops/ms
ClientSimple.listUser                        thrpt          7.570          ops/ms
ClientSimple.createUser                       avgt          2.237           ms/op
ClientSimple.existUser                        avgt          2.076           ms/op
ClientSimple.getUser                          avgt          1.931           ms/op
ClientSimple.listUser                         avgt          3.831           ms/op
ClientSimple.createUser                     sample  15278   2.091 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.621           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.347           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.023           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.531           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.288           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.392           ms/op
ClientSimple.existUser                      sample  18282   1.764 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.737           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.465           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.359           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.050           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.136           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.272           ms/op
ClientSimple.getUser                        sample  16872   1.906 ± 0.036   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.590           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.317           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.594           ms/op
ClientSimple.getUser:getUser·p0.999         sample         28.025           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.499           ms/op
ClientSimple.getUser:getUser·p1.00          sample         29.590           ms/op
ClientSimple.listUser                       sample   9175   3.487 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.075           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.416           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.622           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.540           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.008           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.041           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.041           ms/op

Benchmark result is saved to 1722881617045.json
