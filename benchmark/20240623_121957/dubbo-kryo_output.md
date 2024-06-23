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
# Warmup Iteration   1: 2.148 ops/ms
Iteration   1: 6.786 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.786 ops/ms


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
# Warmup Iteration   1: 7.564 ops/ms
Iteration   1: 12.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.724 ops/ms


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
# Warmup Iteration   1: 7.043 ops/ms
Iteration   1: 14.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.178 ops/ms


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
# Warmup Iteration   1: 4.681 ops/ms
Iteration   1: 8.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.781 ops/ms


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
# Warmup Iteration   1: 3.846 ±(99.9%) 0.074 ms/op
Iteration   1: 2.018 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.018 ms/op


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
# Warmup Iteration   1: 2.969 ±(99.9%) 0.045 ms/op
Iteration   1: 1.795 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.795 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.351 ±(99.9%) 0.061 ms/op
Iteration   1: 2.158 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.158 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.095 ms/op
Iteration   1: 3.358 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.358 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.423 ±(99.9%) 0.080 ms/op
Iteration   1: 2.371 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.331 ms/op
                 createUser·p0.90:   2.830 ms/op
                 createUser·p0.95:   2.994 ms/op
                 createUser·p0.99:   5.391 ms/op
                 createUser·p0.999:  15.311 ms/op
                 createUser·p0.9999: 16.495 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13496
  mean =      2.371 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 8939 
    [ 2.500,  3.750) = 4310 
    [ 3.750,  5.000) = 34 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.331 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      5.391 ms/op
     p(99.9000) =     15.311 ms/op
     p(99.9900) =     16.495 ms/op
     p(99.9990) =     16.581 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.094 ms/op
Iteration   1: 2.038 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.436 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.408 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  24.445 ms/op
                 existUser·p0.9999: 24.571 ms/op
                 existUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15699
  mean =      2.038 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14534 
    [ 2.500,  5.000) = 1094 
    [ 5.000,  7.500) = 7 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.436 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.408 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =     24.445 ms/op
     p(99.9900) =     24.571 ms/op
     p(99.9990) =     24.609 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


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
# Warmup Iteration   1: 3.025 ±(99.9%) 0.076 ms/op
Iteration   1: 1.947 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.404 ms/op
                 getUser·p0.50:   1.835 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.609 ms/op
                 getUser·p0.99:   3.460 ms/op
                 getUser·p0.999:  12.937 ms/op
                 getUser·p0.9999: 13.074 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16405
  mean =      1.947 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 15069 
    [ 2.500,  3.750) = 959 
    [ 3.750,  5.000) = 55 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      1.835 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.609 ms/op
     p(99.0000) =      3.460 ms/op
     p(99.9000) =     12.937 ms/op
     p(99.9900) =     13.074 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.114 ms/op
Iteration   1: 3.765 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  16.671 ms/op
                 listUser·p0.9999: 16.941 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8488
  mean =      3.765 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 154 
    [ 2.500,  3.750) = 4094 
    [ 3.750,  5.000) = 3888 
    [ 5.000,  6.250) = 206 
    [ 6.250,  7.500) = 81 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.671 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.786          ops/ms
ClientSimple.existUser                       thrpt         12.724          ops/ms
ClientSimple.getUser                         thrpt         14.178          ops/ms
ClientSimple.listUser                        thrpt          8.781          ops/ms
ClientSimple.createUser                       avgt          2.018           ms/op
ClientSimple.existUser                        avgt          1.795           ms/op
ClientSimple.getUser                          avgt          2.158           ms/op
ClientSimple.listUser                         avgt          3.358           ms/op
ClientSimple.createUser                     sample  13496   2.371 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.094           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.331           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.994           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.391           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.311           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.495           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.581           ms/op
ClientSimple.existUser                      sample  15699   2.038 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.436           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.408           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.764           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.445           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.571           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.609           ms/op
ClientSimple.getUser                        sample  16405   1.947 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.404           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.835           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.460           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.937           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.074           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   8488   3.765 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.356           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.748           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.062           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.671           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.941           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.941           ms/op

Benchmark result is saved to 1719144933645.json
