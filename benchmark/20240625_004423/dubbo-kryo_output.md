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
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 7.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.552 ops/ms


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
# Warmup Iteration   1: 7.448 ops/ms
Iteration   1: 12.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.510 ops/ms


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
# Warmup Iteration   1: 6.891 ops/ms
Iteration   1: 14.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.528 ops/ms


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
# Warmup Iteration   1: 5.346 ops/ms
Iteration   1: 9.438 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.438 ops/ms


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.079 ms/op
Iteration   1: 2.337 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.337 ms/op


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
# Warmup Iteration   1: 3.093 ±(99.9%) 0.042 ms/op
Iteration   1: 1.764 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.764 ms/op


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
# Warmup Iteration   1: 3.428 ±(99.9%) 0.059 ms/op
Iteration   1: 2.136 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.136 ms/op


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.089 ms/op
Iteration   1: 3.608 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.608 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.084 ms/op
Iteration   1: 2.274 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   2.056 ms/op
                 createUser·p0.90:   2.875 ms/op
                 createUser·p0.95:   3.285 ms/op
                 createUser·p0.99:   9.082 ms/op
                 createUser·p0.999:  14.727 ms/op
                 createUser·p0.9999: 15.401 ms/op
                 createUser·p1.00:   15.434 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14032
  mean =      2.274 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 140 
    [ 1.250,  2.500) = 10531 
    [ 2.500,  3.750) = 2814 
    [ 3.750,  5.000) = 201 
    [ 5.000,  6.250) = 93 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.813 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.875 ms/op
     p(95.0000) =      3.285 ms/op
     p(99.0000) =      9.082 ms/op
     p(99.9000) =     14.727 ms/op
     p(99.9900) =     15.401 ms/op
     p(99.9990) =     15.434 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.072 ms/op
Iteration   1: 2.079 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   1.978 ms/op
                 existUser·p0.90:   2.605 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  24.117 ms/op
                 existUser·p0.9999: 24.616 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15378
  mean =      2.079 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13148 
    [ 2.500,  5.000) = 2115 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      1.978 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      3.760 ms/op
     p(99.9000) =     24.117 ms/op
     p(99.9900) =     24.616 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.087 ms/op
Iteration   1: 2.196 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.390 ms/op
                 getUser·p0.50:   2.163 ms/op
                 getUser·p0.90:   2.646 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   4.168 ms/op
                 getUser·p0.999:  11.944 ms/op
                 getUser·p0.9999: 12.362 ms/op
                 getUser·p1.00:   12.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14551
  mean =      2.196 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 207 
    [ 1.250,  2.500) = 11843 
    [ 2.500,  3.750) = 2244 
    [ 3.750,  5.000) = 218 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.390 ms/op
     p(50.0000) =      2.163 ms/op
     p(90.0000) =      2.646 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.168 ms/op
     p(99.9000) =     11.944 ms/op
     p(99.9900) =     12.362 ms/op
     p(99.9990) =     12.370 ms/op
     p(99.9999) =     12.370 ms/op
    p(100.0000) =     12.370 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.168 ms/op
Iteration   1: 3.953 ±(99.9%) 0.226 ms/op
                 listUser·p0.00:   0.542 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   30.612 ms/op
                 listUser·p0.999:  105.616 ms/op
                 listUser·p0.9999: 128.582 ms/op
                 listUser·p1.00:   128.582 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8107
  mean =      3.953 ±(99.9%) 0.226 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 8018 
    [ 12.500,  25.000) = 7 
    [ 25.000,  37.500) = 37 
    [ 37.500,  50.000) = 10 
    [ 50.000,  62.500) = 3 
    [ 62.500,  75.000) = 10 
    [ 75.000,  87.500) = 5 
    [ 87.500, 100.000) = 6 
    [100.000, 112.500) = 8 
    [112.500, 125.000) = 2 
    [125.000, 137.500) = 1 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.542 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =     30.612 ms/op
     p(99.9000) =    105.616 ms/op
     p(99.9900) =    128.582 ms/op
     p(99.9990) =    128.582 ms/op
     p(99.9999) =    128.582 ms/op
    p(100.0000) =    128.582 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.552          ops/ms
ClientSimple.existUser                       thrpt          12.510          ops/ms
ClientSimple.getUser                         thrpt          14.528          ops/ms
ClientSimple.listUser                        thrpt           9.438          ops/ms
ClientSimple.createUser                       avgt           2.337           ms/op
ClientSimple.existUser                        avgt           1.764           ms/op
ClientSimple.getUser                          avgt           2.136           ms/op
ClientSimple.listUser                         avgt           3.608           ms/op
ClientSimple.createUser                     sample  14032    2.274 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.813           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.056           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.875           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.285           ms/op
ClientSimple.createUser:createUser·p0.99    sample           9.082           ms/op
ClientSimple.createUser:createUser·p0.999   sample          14.727           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          15.401           ms/op
ClientSimple.createUser:createUser·p1.00    sample          15.434           ms/op
ClientSimple.existUser                      sample  15378    2.079 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.497           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.978           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.605           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.760           ms/op
ClientSimple.existUser:existUser·p0.999     sample          24.117           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          24.616           ms/op
ClientSimple.existUser:existUser·p1.00      sample          24.740           ms/op
ClientSimple.getUser                        sample  14551    2.196 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.390           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.163           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.646           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.168           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.944           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          12.362           ms/op
ClientSimple.getUser:getUser·p1.00          sample          12.370           ms/op
ClientSimple.listUser                       sample   8107    3.953 ± 0.226   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.542           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.571           ms/op
ClientSimple.listUser:listUser·p0.99        sample          30.612           ms/op
ClientSimple.listUser:listUser·p0.999       sample         105.616           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         128.582           ms/op
ClientSimple.listUser:listUser·p1.00        sample         128.582           ms/op

Benchmark result is saved to 1719276042218.json
