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
# Warmup Iteration   1: 1.663 ops/ms
Iteration   1: 6.918 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.918 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.063 ops/ms
Iteration   1: 12.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.557 ops/ms


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
# Warmup Iteration   1: 5.293 ops/ms
Iteration   1: 13.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.672 ops/ms


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
# Warmup Iteration   1: 4.593 ops/ms
Iteration   1: 9.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.024 ops/ms


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.085 ms/op
Iteration   1: 2.206 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.206 ms/op


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
# Warmup Iteration   1: 3.050 ±(99.9%) 0.042 ms/op
Iteration   1: 1.893 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 3.386 ±(99.9%) 0.050 ms/op
Iteration   1: 2.020 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.020 ms/op


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
# Warmup Iteration   1: 4.341 ±(99.9%) 0.085 ms/op
Iteration   1: 3.193 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.193 ms/op


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
# Warmup Iteration   1: 3.849 ±(99.9%) 0.099 ms/op
Iteration   1: 2.042 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   1.841 ms/op
                 createUser·p0.90:   2.494 ms/op
                 createUser·p0.95:   2.814 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  15.581 ms/op
                 createUser·p0.9999: 16.073 ms/op
                 createUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15649
  mean =      2.042 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 13904 
    [ 2.500,  3.750) = 1259 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.494 ms/op
     p(95.0000) =      2.814 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 2.779 ±(99.9%) 0.078 ms/op
Iteration   1: 1.712 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   1.634 ms/op
                 existUser·p0.90:   2.083 ms/op
                 existUser·p0.95:   2.249 ms/op
                 existUser·p0.99:   3.151 ms/op
                 existUser·p0.999:  10.306 ms/op
                 existUser·p0.9999: 10.634 ms/op
                 existUser·p1.00:   11.059 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18659
  mean =      1.712 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1163 
    [ 1.250,  2.500) = 17146 
    [ 2.500,  3.750) = 206 
    [ 3.750,  5.000) = 36 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      1.634 ms/op
     p(90.0000) =      2.083 ms/op
     p(95.0000) =      2.249 ms/op
     p(99.0000) =      3.151 ms/op
     p(99.9000) =     10.306 ms/op
     p(99.9900) =     10.634 ms/op
     p(99.9990) =     11.059 ms/op
     p(99.9999) =     11.059 ms/op
    p(100.0000) =     11.059 ms/op


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
# Warmup Iteration   1: 3.187 ±(99.9%) 0.080 ms/op
Iteration   1: 2.255 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.736 ms/op
                 getUser·p0.95:   2.912 ms/op
                 getUser·p0.99:   3.658 ms/op
                 getUser·p0.999:  16.641 ms/op
                 getUser·p0.9999: 17.607 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14155
  mean =      2.255 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 121 
    [ 1.250,  2.500) = 11021 
    [ 2.500,  3.750) = 2876 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =     16.641 ms/op
     p(99.9900) =     17.607 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 5.127 ±(99.9%) 0.150 ms/op
Iteration   1: 3.935 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  14.140 ms/op
                 listUser·p0.9999: 14.451 ms/op
                 listUser·p1.00:   14.451 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8220
  mean =      3.935 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 277 
    [ 2.500,  3.750) = 3123 
    [ 3.750,  5.000) = 4413 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 192 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.140 ms/op
     p(99.9900) =     14.451 ms/op
     p(99.9990) =     14.451 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.918          ops/ms
ClientSimple.existUser                       thrpt         12.557          ops/ms
ClientSimple.getUser                         thrpt         13.672          ops/ms
ClientSimple.listUser                        thrpt          9.024          ops/ms
ClientSimple.createUser                       avgt          2.206           ms/op
ClientSimple.existUser                        avgt          1.893           ms/op
ClientSimple.getUser                          avgt          2.020           ms/op
ClientSimple.listUser                         avgt          3.193           ms/op
ClientSimple.createUser                     sample  15649   2.042 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.528           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.841           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.494           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.814           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.612           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.581           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.073           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.073           ms/op
ClientSimple.existUser                      sample  18659   1.712 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.656           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.634           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.083           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.249           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.151           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.306           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.634           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.059           ms/op
ClientSimple.getUser                        sample  14155   2.255 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.613           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.736           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.912           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.658           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.641           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.607           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.662           ms/op
ClientSimple.listUser                       sample   8220   3.935 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.653           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.997           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.140           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.451           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.451           ms/op

Benchmark result is saved to 1714997732159.json
