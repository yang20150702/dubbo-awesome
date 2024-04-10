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
# Warmup Iteration   1: 1.318 ops/ms
Iteration   1: 5.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.973 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.776 ops/ms
Iteration   1: 13.517 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.517 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.760 ops/ms
Iteration   1: 12.404 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.404 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ops/ms
Iteration   1: 7.506 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.506 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.084 ms/op
Iteration   1: 2.322 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.322 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.237 ±(99.9%) 0.059 ms/op
Iteration   1: 2.061 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.061 ms/op


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
# Warmup Iteration   1: 3.544 ±(99.9%) 0.076 ms/op
Iteration   1: 2.017 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.017 ms/op


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
# Warmup Iteration   1: 5.263 ±(99.9%) 0.130 ms/op
Iteration   1: 3.979 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.979 ms/op


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
# Warmup Iteration   1: 4.316 ±(99.9%) 0.124 ms/op
Iteration   1: 2.649 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   2.413 ms/op
                 createUser·p0.90:   3.380 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   7.056 ms/op
                 createUser·p0.999:  13.795 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12068
  mean =      2.649 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 6754 
    [ 2.500,  3.750) = 4455 
    [ 3.750,  5.000) = 581 
    [ 5.000,  6.250) = 85 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.413 ms/op
     p(90.0000) =      3.380 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      7.056 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     14.025 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.091 ms/op
Iteration   1: 1.836 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.220 ms/op
                 existUser·p0.95:   2.407 ms/op
                 existUser·p0.99:   3.234 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 22.540 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17424
  mean =      1.836 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16757 
    [ 2.500,  5.000) = 542 
    [ 5.000,  7.500) = 60 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.220 ms/op
     p(95.0000) =      2.407 ms/op
     p(99.0000) =      3.234 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     22.540 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 3.401 ±(99.9%) 0.091 ms/op
Iteration   1: 2.148 ±(99.9%) 0.066 ms/op
                 getUser·p0.00:   0.583 ms/op
                 getUser·p0.50:   1.888 ms/op
                 getUser·p0.90:   2.560 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   7.799 ms/op
                 getUser·p0.999:  54.665 ms/op
                 getUser·p0.9999: 59.624 ms/op
                 getUser·p1.00:   60.424 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14883
  mean =      2.148 ±(99.9%) 0.066 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14646 
    [ 5.000, 10.000) = 122 
    [10.000, 15.000) = 70 
    [15.000, 20.000) = 2 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 4 
    [55.000, 60.000) = 12 
    [60.000, 65.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     54.665 ms/op
     p(99.9900) =     59.624 ms/op
     p(99.9990) =     60.424 ms/op
     p(99.9999) =     60.424 ms/op
    p(100.0000) =     60.424 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.187 ms/op
Iteration   1: 3.571 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.447 ms/op
                 listUser·p0.95:   5.299 ms/op
                 listUser·p0.99:   6.868 ms/op
                 listUser·p0.999:  8.176 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8961
  mean =      3.571 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 66 
    [ 2.000,  3.000) = 2694 
    [ 3.000,  4.000) = 3873 
    [ 4.000,  5.000) = 1785 
    [ 5.000,  6.000) = 307 
    [ 6.000,  7.000) = 156 
    [ 7.000,  8.000) = 51 
    [ 8.000,  9.000) = 24 
    [ 9.000, 10.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.447 ms/op
     p(95.0000) =      5.299 ms/op
     p(99.0000) =      6.868 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     10.781 ms/op
     p(99.9999) =     10.781 ms/op
    p(100.0000) =     10.781 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.973          ops/ms
ClientSimple.existUser                       thrpt         13.517          ops/ms
ClientSimple.getUser                         thrpt         12.404          ops/ms
ClientSimple.listUser                        thrpt          7.506          ops/ms
ClientSimple.createUser                       avgt          2.322           ms/op
ClientSimple.existUser                        avgt          2.061           ms/op
ClientSimple.getUser                          avgt          2.017           ms/op
ClientSimple.listUser                         avgt          3.979           ms/op
ClientSimple.createUser                     sample  12068   2.649 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.707           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.413           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.380           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.030           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.056           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.795           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.025           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.025           ms/op
ClientSimple.existUser                      sample  17424   1.836 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.634           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.735           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.220           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.407           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.234           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.611           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.540           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.905           ms/op
ClientSimple.getUser                        sample  14883   2.148 ± 0.066   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.583           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.888           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.560           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          7.799           ms/op
ClientSimple.getUser:getUser·p0.999         sample         54.665           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         59.624           ms/op
ClientSimple.getUser:getUser·p1.00          sample         60.424           ms/op
ClientSimple.listUser                       sample   8961   3.571 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.915           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.447           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.299           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.868           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.176           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.781           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.781           ms/op

Benchmark result is saved to 1712772704718.json
