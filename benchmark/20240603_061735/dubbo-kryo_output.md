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
# Warmup Iteration   1: 1.999 ops/ms
Iteration   1: 6.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.406 ops/ms


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
# Warmup Iteration   1: 5.900 ops/ms
Iteration   1: 11.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.103 ops/ms


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
# Warmup Iteration   1: 5.035 ops/ms
Iteration   1: 13.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.176 ops/ms


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
# Warmup Iteration   1: 4.970 ops/ms
Iteration   1: 8.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.632 ops/ms


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
# Warmup Iteration   1: 3.488 ±(99.9%) 0.076 ms/op
Iteration   1: 2.513 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.513 ms/op


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
# Warmup Iteration   1: 3.063 ±(99.9%) 0.060 ms/op
Iteration   1: 1.876 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


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
# Warmup Iteration   1: 3.308 ±(99.9%) 0.063 ms/op
Iteration   1: 2.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.173 ms/op


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
# Warmup Iteration   1: 5.313 ±(99.9%) 0.116 ms/op
Iteration   1: 3.376 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.376 ms/op


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
# Warmup Iteration   1: 3.483 ±(99.9%) 0.101 ms/op
Iteration   1: 2.115 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.502 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.829 ms/op
                 createUser·p0.99:   8.876 ms/op
                 createUser·p0.999:  20.201 ms/op
                 createUser·p0.9999: 21.265 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15126
  mean =      2.115 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13439 
    [ 2.500,  5.000) = 1410 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.829 ms/op
     p(99.0000) =      8.876 ms/op
     p(99.9000) =     20.201 ms/op
     p(99.9900) =     21.265 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.066 ms/op
Iteration   1: 2.189 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   2.060 ms/op
                 existUser·p0.90:   2.879 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  19.045 ms/op
                 existUser·p0.9999: 19.827 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14594
  mean =      2.189 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 549 
    [ 1.250,  2.500) = 9526 
    [ 2.500,  3.750) = 4324 
    [ 3.750,  5.000) = 62 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      4.096 ms/op
     p(99.9000) =     19.045 ms/op
     p(99.9900) =     19.827 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.804 ±(99.9%) 0.190 ms/op
Iteration   1: 2.027 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.863 ms/op
                 getUser·p0.99:   3.991 ms/op
                 getUser·p0.999:  13.353 ms/op
                 getUser·p0.9999: 13.530 ms/op
                 getUser·p1.00:   13.550 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15824
  mean =      2.027 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 181 
    [ 1.250,  2.500) = 13961 
    [ 2.500,  3.750) = 1479 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 50 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      3.991 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     13.530 ms/op
     p(99.9990) =     13.550 ms/op
     p(99.9999) =     13.550 ms/op
    p(100.0000) =     13.550 ms/op


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
# Warmup Iteration   1: 4.580 ±(99.9%) 0.125 ms/op
Iteration   1: 3.292 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   3.303 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.590 ms/op
                 listUser·p0.99:   7.632 ms/op
                 listUser·p0.999:  20.185 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9632
  mean =      3.292 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2720 
    [ 2.500,  5.000) = 6554 
    [ 5.000,  7.500) = 256 
    [ 7.500, 10.000) = 50 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      3.303 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.590 ms/op
     p(99.0000) =      7.632 ms/op
     p(99.9000) =     20.185 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.406          ops/ms
ClientSimple.existUser                       thrpt         11.103          ops/ms
ClientSimple.getUser                         thrpt         13.176          ops/ms
ClientSimple.listUser                        thrpt          8.632          ops/ms
ClientSimple.createUser                       avgt          2.513           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          2.173           ms/op
ClientSimple.listUser                         avgt          3.376           ms/op
ClientSimple.createUser                     sample  15126   2.115 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.502           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.829           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.876           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.201           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.265           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  14594   2.189 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.060           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.879           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.146           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.096           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.045           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.827           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.857           ms/op
ClientSimple.getUser                        sample  15824   2.027 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.863           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.991           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.353           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.530           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.550           ms/op
ClientSimple.listUser                       sample   9632   3.292 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.929           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.303           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.194           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.590           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.632           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.185           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.396           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.396           ms/op

Benchmark result is saved to 1717395180473.json
