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
# Warmup Iteration   1: 1.714 ops/ms
Iteration   1: 7.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.437 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.582 ops/ms
Iteration   1: 12.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.340 ops/ms


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
# Warmup Iteration   1: 6.636 ops/ms
Iteration   1: 14.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.339 ops/ms


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
# Warmup Iteration   1: 3.870 ops/ms
Iteration   1: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.016 ops/ms


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.088 ms/op
Iteration   1: 2.342 ±(99.9%) 0.042 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.342 ms/op


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
# Warmup Iteration   1: 3.309 ±(99.9%) 0.050 ms/op
Iteration   1: 1.888 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.888 ms/op


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
# Warmup Iteration   1: 3.363 ±(99.9%) 0.060 ms/op
Iteration   1: 2.228 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.228 ms/op


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.126 ms/op
Iteration   1: 3.585 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.585 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.101 ms/op
Iteration   1: 2.320 ±(99.9%) 0.056 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   2.671 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   6.873 ms/op
                 createUser·p0.999:  34.617 ms/op
                 createUser·p0.9999: 35.650 ms/op
                 createUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13783
  mean =      2.320 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11734 
    [ 2.500,  5.000) = 1764 
    [ 5.000,  7.500) = 183 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.671 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     34.617 ms/op
     p(99.9900) =     35.650 ms/op
     p(99.9990) =     35.848 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 2.920 ±(99.9%) 0.068 ms/op
Iteration   1: 2.005 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.609 ms/op
                 existUser·p0.50:   1.855 ms/op
                 existUser·p0.90:   2.548 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.787 ms/op
                 existUser·p0.999:  13.747 ms/op
                 existUser·p0.9999: 14.057 ms/op
                 existUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15951
  mean =      2.005 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 13918 
    [ 2.500,  3.750) = 1698 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      1.855 ms/op
     p(90.0000) =      2.548 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.787 ms/op
     p(99.9000) =     13.747 ms/op
     p(99.9900) =     14.057 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.083 ms/op
Iteration   1: 2.009 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.600 ms/op
                 getUser·p0.50:   1.862 ms/op
                 getUser·p0.90:   2.503 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   3.758 ms/op
                 getUser·p0.999:  16.744 ms/op
                 getUser·p0.9999: 17.001 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15920
  mean =      2.009 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 151 
    [ 1.250,  2.500) = 14153 
    [ 2.500,  3.750) = 1457 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.600 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.503 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.758 ms/op
     p(99.9000) =     16.744 ms/op
     p(99.9900) =     17.001 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.137 ms/op
Iteration   1: 3.852 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.916 ms/op
                 listUser·p0.99:   7.068 ms/op
                 listUser·p0.999:  8.962 ms/op
                 listUser·p0.9999: 9.060 ms/op
                 listUser·p1.00:   9.060 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8317
  mean =      3.852 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 2 
    [ 1.500,  2.000) = 17 
    [ 2.000,  2.500) = 257 
    [ 2.500,  3.000) = 474 
    [ 3.000,  3.500) = 1362 
    [ 3.500,  4.000) = 3323 
    [ 4.000,  4.500) = 2042 
    [ 4.500,  5.000) = 452 
    [ 5.000,  5.500) = 185 
    [ 5.500,  6.000) = 43 
    [ 6.000,  6.500) = 50 
    [ 6.500,  7.000) = 11 
    [ 7.000,  7.500) = 65 
    [ 7.500,  8.000) = 2 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 28 
    [ 9.000,  9.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.916 ms/op
     p(99.0000) =      7.068 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =      9.060 ms/op
     p(99.9990) =      9.060 ms/op
     p(99.9999) =      9.060 ms/op
    p(100.0000) =      9.060 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.437          ops/ms
ClientSimple.existUser                       thrpt         12.340          ops/ms
ClientSimple.getUser                         thrpt         14.339          ops/ms
ClientSimple.listUser                        thrpt          8.016          ops/ms
ClientSimple.createUser                       avgt          2.342           ms/op
ClientSimple.existUser                        avgt          1.888           ms/op
ClientSimple.getUser                          avgt          2.228           ms/op
ClientSimple.listUser                         avgt          3.585           ms/op
ClientSimple.createUser                     sample  13783   2.320 ± 0.056   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.785           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.215           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.873           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.617           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.650           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.848           ms/op
ClientSimple.existUser                      sample  15951   2.005 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.609           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.855           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.548           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.787           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.747           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.057           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.057           ms/op
ClientSimple.getUser                        sample  15920   2.009 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.600           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.862           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.503           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.758           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.744           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.001           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.039           ms/op
ClientSimple.listUser                       sample   8317   3.852 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.096           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.813           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.916           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.068           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.962           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.060           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.060           ms/op

Benchmark result is saved to 1716617557344.json
