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
# Warmup Iteration   1: 1.532 ops/ms
Iteration   1: 5.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.931 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ops/ms
Iteration   1: 11.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.456 ops/ms


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
# Warmup Iteration   1: 4.929 ops/ms
Iteration   1: 13.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.164 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.896 ops/ms
Iteration   1: 8.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.281 ops/ms


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.071 ms/op
Iteration   1: 2.412 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.412 ms/op


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
# Warmup Iteration   1: 3.216 ±(99.9%) 0.057 ms/op
Iteration   1: 2.116 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.116 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.068 ms/op
Iteration   1: 2.189 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.189 ms/op


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
# Warmup Iteration   1: 5.144 ±(99.9%) 0.099 ms/op
Iteration   1: 3.249 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.249 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.094 ms/op
Iteration   1: 2.587 ±(99.9%) 0.126 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   2.220 ms/op
                 createUser·p0.90:   2.753 ms/op
                 createUser·p0.95:   3.125 ms/op
                 createUser·p0.99:   12.196 ms/op
                 createUser·p0.999:  87.294 ms/op
                 createUser·p0.9999: 96.540 ms/op
                 createUser·p1.00:   96.993 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12662
  mean =      2.587 ±(99.9%) 0.126 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 12519 
    [ 10.000,  20.000) = 88 
    [ 20.000,  30.000) = 19 
    [ 30.000,  40.000) = 4 
    [ 40.000,  50.000) = 0 
    [ 50.000,  60.000) = 2 
    [ 60.000,  70.000) = 3 
    [ 70.000,  80.000) = 8 
    [ 80.000,  90.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      2.220 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =     12.196 ms/op
     p(99.9000) =     87.294 ms/op
     p(99.9900) =     96.540 ms/op
     p(99.9990) =     96.993 ms/op
     p(99.9999) =     96.993 ms/op
    p(100.0000) =     96.993 ms/op


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
# Warmup Iteration   1: 2.981 ±(99.9%) 0.069 ms/op
Iteration   1: 2.070 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   1.901 ms/op
                 existUser·p0.90:   2.481 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   4.274 ms/op
                 existUser·p0.999:  15.225 ms/op
                 existUser·p0.9999: 17.669 ms/op
                 existUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15432
  mean =      2.070 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 13834 
    [ 2.500,  3.750) = 1222 
    [ 3.750,  5.000) = 136 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.481 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      4.274 ms/op
     p(99.9000) =     15.225 ms/op
     p(99.9900) =     17.669 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.105 ms/op
Iteration   1: 2.116 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.440 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   3.000 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  11.813 ms/op
                 getUser·p0.9999: 13.875 ms/op
                 getUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15091
  mean =      2.116 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 12784 
    [ 2.500,  3.750) = 1632 
    [ 3.750,  5.000) = 227 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      3.000 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     13.875 ms/op
     p(99.9990) =     13.976 ms/op
     p(99.9999) =     13.976 ms/op
    p(100.0000) =     13.976 ms/op


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
# Warmup Iteration   1: 4.635 ±(99.9%) 0.156 ms/op
Iteration   1: 3.726 ±(99.9%) 0.061 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.518 ms/op
                 listUser·p0.95:   5.030 ms/op
                 listUser·p0.99:   9.209 ms/op
                 listUser·p0.999:  24.687 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8614
  mean =      3.726 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 508 
    [ 2.500,  5.000) = 7667 
    [ 5.000,  7.500) = 333 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.311 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.518 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      9.209 ms/op
     p(99.9000) =     24.687 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     25.133 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.931          ops/ms
ClientSimple.existUser                       thrpt         11.456          ops/ms
ClientSimple.getUser                         thrpt         13.164          ops/ms
ClientSimple.listUser                        thrpt          8.281          ops/ms
ClientSimple.createUser                       avgt          2.412           ms/op
ClientSimple.existUser                        avgt          2.116           ms/op
ClientSimple.getUser                          avgt          2.189           ms/op
ClientSimple.listUser                         avgt          3.249           ms/op
ClientSimple.createUser                     sample  12662   2.587 ± 0.126   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.562           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.220           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.753           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.196           ms/op
ClientSimple.createUser:createUser·p0.999   sample         87.294           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         96.540           ms/op
ClientSimple.createUser:createUser·p1.00    sample         96.993           ms/op
ClientSimple.existUser                      sample  15432   2.070 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.714           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.901           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.481           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.274           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.225           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.669           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.530           ms/op
ClientSimple.getUser                        sample  15091   2.116 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.440           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.000           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.489           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.813           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.875           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.976           ms/op
ClientSimple.listUser                       sample   8614   3.726 ± 0.061   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.311           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.621           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.518           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.030           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.209           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.687           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.133           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.133           ms/op

Benchmark result is saved to 1718907191314.json
