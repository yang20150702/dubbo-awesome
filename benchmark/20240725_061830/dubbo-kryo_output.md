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
# Warmup Iteration   1: 0.864 ops/ms
Iteration   1: 5.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.853 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.881 ops/ms
Iteration   1: 11.794 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.794 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.290 ops/ms
Iteration   1: 12.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.508 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.429 ops/ms
Iteration   1: 8.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.442 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.448 ±(99.9%) 0.056 ms/op
Iteration   1: 2.103 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.103 ms/op


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
# Warmup Iteration   1: 2.883 ±(99.9%) 0.046 ms/op
Iteration   1: 1.786 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.786 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.048 ms/op
Iteration   1: 1.764 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.764 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.089 ms/op
Iteration   1: 3.424 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.424 ms/op


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
# Warmup Iteration   1: 3.765 ±(99.9%) 0.110 ms/op
Iteration   1: 2.060 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   1.847 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  14.787 ms/op
                 createUser·p0.9999: 15.860 ms/op
                 createUser·p1.00:   15.860 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15501
  mean =      2.060 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 397 
    [ 1.250,  2.500) = 12711 
    [ 2.500,  3.750) = 2002 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 69 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     14.787 ms/op
     p(99.9900) =     15.860 ms/op
     p(99.9990) =     15.860 ms/op
     p(99.9999) =     15.860 ms/op
    p(100.0000) =     15.860 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.092 ±(99.9%) 0.117 ms/op
Iteration   1: 1.598 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.348 ms/op
                 existUser·p0.50:   1.516 ms/op
                 existUser·p0.90:   1.778 ms/op
                 existUser·p0.95:   2.077 ms/op
                 existUser·p0.99:   2.626 ms/op
                 existUser·p0.999:  16.122 ms/op
                 existUser·p0.9999: 17.039 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 20000
  mean =      1.598 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 796 
    [ 1.250,  2.500) = 18906 
    [ 2.500,  3.750) = 217 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.348 ms/op
     p(50.0000) =      1.516 ms/op
     p(90.0000) =      1.778 ms/op
     p(95.0000) =      2.077 ms/op
     p(99.0000) =      2.626 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     17.039 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.127 ±(99.9%) 0.068 ms/op
Iteration   1: 2.012 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.367 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.544 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.782 ms/op
                 getUser·p0.999:  11.798 ms/op
                 getUser·p0.9999: 11.915 ms/op
                 getUser·p1.00:   11.944 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15932
  mean =      2.012 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 558 
    [ 1.250,  2.500) = 13507 
    [ 2.500,  3.750) = 1697 
    [ 3.750,  5.000) = 70 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.367 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.782 ms/op
     p(99.9000) =     11.798 ms/op
     p(99.9900) =     11.915 ms/op
     p(99.9990) =     11.944 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 5.003 ±(99.9%) 0.144 ms/op
Iteration   1: 3.454 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.355 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 14.238 ms/op
                 listUser·p1.00:   14.238 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9265
  mean =      3.454 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1023 
    [ 2.500,  3.750) = 5490 
    [ 3.750,  5.000) = 2348 
    [ 5.000,  6.250) = 193 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     14.238 ms/op
     p(99.9999) =     14.238 ms/op
    p(100.0000) =     14.238 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.853          ops/ms
ClientSimple.existUser                       thrpt         11.794          ops/ms
ClientSimple.getUser                         thrpt         12.508          ops/ms
ClientSimple.listUser                        thrpt          8.442          ops/ms
ClientSimple.createUser                       avgt          2.103           ms/op
ClientSimple.existUser                        avgt          1.786           ms/op
ClientSimple.getUser                          avgt          1.764           ms/op
ClientSimple.listUser                         avgt          3.424           ms/op
ClientSimple.createUser                     sample  15501   2.060 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.636           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.847           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.242           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.787           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.860           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.860           ms/op
ClientSimple.existUser                      sample  20000   1.598 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.348           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.516           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.077           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.122           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.039           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.269           ms/op
ClientSimple.getUser                        sample  15932   2.012 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.367           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.544           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.782           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.798           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.915           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.944           ms/op
ClientSimple.listUser                       sample   9265   3.454 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.087           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.355           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.152           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.238           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.238           ms/op

Benchmark result is saved to 1721888047560.json
