# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.755 ops/ms
Iteration   1: 7.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.096 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.147 ops/ms
Iteration   1: 12.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.740 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.334 ops/ms
Iteration   1: 15.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.446 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.336 ops/ms
Iteration   1: 7.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.412 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.251 ±(99.9%) 0.098 ms/op
Iteration   1: 2.200 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.454 ±(99.9%) 0.057 ms/op
Iteration   1: 1.952 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.952 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.338 ±(99.9%) 0.059 ms/op
Iteration   1: 1.936 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.936 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ±(99.9%) 0.108 ms/op
Iteration   1: 3.466 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ±(99.9%) 0.084 ms/op
Iteration   1: 2.425 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.557 ms/op
                 createUser·p0.50:   2.331 ms/op
                 createUser·p0.90:   3.252 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  14.189 ms/op
                 createUser·p0.9999: 14.287 ms/op
                 createUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13182
  mean =      2.425 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 8387 
    [ 2.500,  3.750) = 4324 
    [ 3.750,  5.000) = 265 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.331 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     14.287 ms/op
     p(99.9990) =     14.287 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.030 ±(99.9%) 0.073 ms/op
Iteration   1: 1.756 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   1.640 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.417 ms/op
                 existUser·p0.99:   3.685 ms/op
                 existUser·p0.999:  20.840 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18383
  mean =      1.756 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17805 
    [ 2.500,  5.000) = 443 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      1.640 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.417 ms/op
     p(99.0000) =      3.685 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.037 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.227 ±(99.9%) 0.075 ms/op
Iteration   1: 1.890 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.481 ms/op
                 getUser·p0.50:   1.792 ms/op
                 getUser·p0.90:   2.413 ms/op
                 getUser·p0.95:   2.636 ms/op
                 getUser·p0.99:   3.063 ms/op
                 getUser·p0.999:  12.698 ms/op
                 getUser·p0.9999: 16.656 ms/op
                 getUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16907
  mean =      1.890 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 85 
    [ 1.250,  2.500) = 15463 
    [ 2.500,  3.750) = 1312 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.481 ms/op
     p(50.0000) =      1.792 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.636 ms/op
     p(99.0000) =      3.063 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     16.656 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.520 ±(99.9%) 0.145 ms/op
Iteration   1: 3.466 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   3.494 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.712 ms/op
                 listUser·p0.999:  12.714 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9236
  mean =      3.466 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1033 
    [ 2.500,  3.750) = 4904 
    [ 3.750,  5.000) = 3098 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.712 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     15.106 ms/op
     p(99.9990) =     15.106 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.096          ops/ms
ClientSimple.existUser                       thrpt         12.740          ops/ms
ClientSimple.getUser                         thrpt         15.446          ops/ms
ClientSimple.listUser                        thrpt          7.412          ops/ms
ClientSimple.createUser                       avgt          2.200           ms/op
ClientSimple.existUser                        avgt          1.952           ms/op
ClientSimple.getUser                          avgt          1.936           ms/op
ClientSimple.listUser                         avgt          3.466           ms/op
ClientSimple.createUser                     sample  13182   2.425 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.557           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.331           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.252           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.518           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.391           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.189           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.287           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.287           ms/op
ClientSimple.existUser                      sample  18383   1.756 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.653           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.640           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.685           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.840           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.037           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.037           ms/op
ClientSimple.getUser                        sample  16907   1.890 ± 0.015   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.481           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.792           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.413           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.636           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.063           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.698           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.656           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.679           ms/op
ClientSimple.listUser                       sample   9236   3.466 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.764           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.494           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.712           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.714           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         15.106           ms/op
ClientSimple.listUser:listUser·p1.00        sample         15.106           ms/op

Benchmark result is saved to 1712363802838.json
