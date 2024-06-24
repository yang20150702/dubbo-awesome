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
# Warmup Iteration   1: 1.834 ops/ms
Iteration   1: 6.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.984 ops/ms


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
# Warmup Iteration   1: 6.070 ops/ms
Iteration   1: 14.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.745 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.980 ops/ms
Iteration   1: 13.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.831 ops/ms


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
# Warmup Iteration   1: 4.561 ops/ms
Iteration   1: 8.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.242 ops/ms


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
# Warmup Iteration   1: 4.005 ±(99.9%) 0.080 ms/op
Iteration   1: 2.191 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.191 ms/op


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
# Warmup Iteration   1: 3.229 ±(99.9%) 0.056 ms/op
Iteration   1: 1.910 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.910 ms/op


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
# Warmup Iteration   1: 3.469 ±(99.9%) 0.050 ms/op
Iteration   1: 2.091 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.091 ms/op


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.100 ms/op
Iteration   1: 3.398 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.398 ms/op


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
# Warmup Iteration   1: 3.366 ±(99.9%) 0.080 ms/op
Iteration   1: 2.078 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   2.001 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.707 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  17.944 ms/op
                 createUser·p0.9999: 19.746 ms/op
                 createUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15394
  mean =      2.078 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 694 
    [ 1.250,  2.500) = 12993 
    [ 2.500,  3.750) = 1449 
    [ 3.750,  5.000) = 98 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      2.001 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.707 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =     17.944 ms/op
     p(99.9900) =     19.746 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 2.858 ±(99.9%) 0.063 ms/op
Iteration   1: 1.744 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.095 ms/op
                 existUser·p0.95:   2.387 ms/op
                 existUser·p0.99:   2.744 ms/op
                 existUser·p0.999:  18.465 ms/op
                 existUser·p0.9999: 18.889 ms/op
                 existUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18482
  mean =      1.744 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 280 
    [ 1.250,  2.500) = 17591 
    [ 2.500,  3.750) = 535 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.095 ms/op
     p(95.0000) =      2.387 ms/op
     p(99.0000) =      2.744 ms/op
     p(99.9000) =     18.465 ms/op
     p(99.9900) =     18.889 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.085 ms/op
Iteration   1: 1.998 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   1.841 ms/op
                 getUser·p0.90:   2.474 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   3.530 ms/op
                 getUser·p0.999:  11.583 ms/op
                 getUser·p0.9999: 14.129 ms/op
                 getUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16020
  mean =      1.998 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 79 
    [ 1.250,  2.500) = 14487 
    [ 2.500,  3.750) = 1311 
    [ 3.750,  5.000) = 40 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      1.841 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      3.530 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     14.129 ms/op
     p(99.9990) =     14.189 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


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
# Warmup Iteration   1: 4.940 ±(99.9%) 0.163 ms/op
Iteration   1: 3.490 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.845 ms/op
                 listUser·p0.999:  12.466 ms/op
                 listUser·p0.9999: 12.534 ms/op
                 listUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9139
  mean =      3.490 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 728 
    [ 2.500,  3.750) = 5531 
    [ 3.750,  5.000) = 2569 
    [ 5.000,  6.250) = 158 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.845 ms/op
     p(99.9000) =     12.466 ms/op
     p(99.9900) =     12.534 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.984          ops/ms
ClientSimple.existUser                       thrpt         14.745          ops/ms
ClientSimple.getUser                         thrpt         13.831          ops/ms
ClientSimple.listUser                        thrpt          8.242          ops/ms
ClientSimple.createUser                       avgt          2.191           ms/op
ClientSimple.existUser                        avgt          1.910           ms/op
ClientSimple.getUser                          avgt          2.091           ms/op
ClientSimple.listUser                         avgt          3.398           ms/op
ClientSimple.createUser                     sample  15394   2.078 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.457           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.001           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.186           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.944           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.746           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.923           ms/op
ClientSimple.existUser                      sample  18482   1.744 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.702           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.095           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.387           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.465           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.889           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.973           ms/op
ClientSimple.getUser                        sample  16020   1.998 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.623           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.841           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.530           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.583           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.129           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.189           ms/op
ClientSimple.listUser                       sample   9139   3.490 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.153           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.845           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.466           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.534           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.534           ms/op

Benchmark result is saved to 1719231435172.json
