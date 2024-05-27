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
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 7.147 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.147 ops/ms


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
# Warmup Iteration   1: 5.931 ops/ms
Iteration   1: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.131 ops/ms


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
# Warmup Iteration   1: 5.721 ops/ms
Iteration   1: 12.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.158 ops/ms


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
# Warmup Iteration   1: 5.099 ops/ms
Iteration   1: 9.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.287 ops/ms


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
# Warmup Iteration   1: 3.973 ±(99.9%) 0.093 ms/op
Iteration   1: 2.330 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.330 ms/op


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
# Warmup Iteration   1: 3.307 ±(99.9%) 0.044 ms/op
Iteration   1: 1.851 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.851 ms/op


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
# Warmup Iteration   1: 3.459 ±(99.9%) 0.075 ms/op
Iteration   1: 2.109 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.109 ms/op


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
# Warmup Iteration   1: 4.517 ±(99.9%) 0.089 ms/op
Iteration   1: 3.438 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.438 ms/op


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
# Warmup Iteration   1: 3.769 ±(99.9%) 0.124 ms/op
Iteration   1: 2.219 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.451 ms/op
                 createUser·p0.50:   1.927 ms/op
                 createUser·p0.90:   2.691 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   7.406 ms/op
                 createUser·p0.999:  38.509 ms/op
                 createUser·p0.9999: 38.637 ms/op
                 createUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14402
  mean =      2.219 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12109 
    [ 2.500,  5.000) = 2116 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     38.509 ms/op
     p(99.9900) =     38.637 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


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
# Warmup Iteration   1: 3.017 ±(99.9%) 0.076 ms/op
Iteration   1: 1.733 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.367 ms/op
                 existUser·p0.99:   3.417 ms/op
                 existUser·p0.999:  13.853 ms/op
                 existUser·p0.9999: 14.341 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18473
  mean =      1.733 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 734 
    [ 1.250,  2.500) = 17088 
    [ 2.500,  3.750) = 504 
    [ 3.750,  5.000) = 56 
    [ 5.000,  6.250) = 56 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.367 ms/op
     p(99.0000) =      3.417 ms/op
     p(99.9000) =     13.853 ms/op
     p(99.9900) =     14.341 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.489 ±(99.9%) 0.096 ms/op
Iteration   1: 1.893 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.672 ms/op
                 getUser·p0.50:   1.782 ms/op
                 getUser·p0.90:   2.318 ms/op
                 getUser·p0.95:   2.478 ms/op
                 getUser·p0.99:   4.063 ms/op
                 getUser·p0.999:  13.533 ms/op
                 getUser·p0.9999: 16.528 ms/op
                 getUser·p1.00:   16.630 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16886
  mean =      1.893 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 232 
    [ 1.250,  2.500) = 15859 
    [ 2.500,  3.750) = 604 
    [ 3.750,  5.000) = 124 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     16.528 ms/op
     p(99.9990) =     16.630 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.538 ±(99.9%) 0.126 ms/op
Iteration   1: 3.686 ±(99.9%) 0.087 ms/op
                 listUser·p0.00:   0.902 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  34.865 ms/op
                 listUser·p0.9999: 35.521 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8692
  mean =      3.686 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1474 
    [ 2.500,  5.000) = 6821 
    [ 5.000,  7.500) = 314 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.940 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     34.865 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     35.521 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.147          ops/ms
ClientSimple.existUser                       thrpt         10.131          ops/ms
ClientSimple.getUser                         thrpt         12.158          ops/ms
ClientSimple.listUser                        thrpt          9.287          ops/ms
ClientSimple.createUser                       avgt          2.330           ms/op
ClientSimple.existUser                        avgt          1.851           ms/op
ClientSimple.getUser                          avgt          2.109           ms/op
ClientSimple.listUser                         avgt          3.438           ms/op
ClientSimple.createUser                     sample  14402   2.219 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.451           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.927           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.691           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.406           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.509           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.637           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.666           ms/op
ClientSimple.existUser                      sample  18473   1.733 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.688           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.130           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.367           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.417           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.853           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.341           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.369           ms/op
ClientSimple.getUser                        sample  16886   1.893 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.672           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.782           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.318           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.533           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.528           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.630           ms/op
ClientSimple.listUser                       sample   8692   3.686 ± 0.087   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.902           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.568           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.571           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.940           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.455           ms/op
ClientSimple.listUser:listUser·p0.999       sample         34.865           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         35.521           ms/op
ClientSimple.listUser:listUser·p1.00        sample         35.521           ms/op

Benchmark result is saved to 1716770435581.json
