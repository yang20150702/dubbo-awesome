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
# Warmup Iteration   1: 1.745 ops/ms
Iteration   1: 6.381 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.381 ops/ms


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
# Warmup Iteration   1: 6.480 ops/ms
Iteration   1: 12.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.781 ops/ms


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
# Warmup Iteration   1: 5.277 ops/ms
Iteration   1: 13.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.030 ops/ms


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
# Warmup Iteration   1: 5.439 ops/ms
Iteration   1: 9.344 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.344 ops/ms


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
# Warmup Iteration   1: 3.793 ±(99.9%) 0.060 ms/op
Iteration   1: 2.042 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.042 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.093 ±(99.9%) 0.051 ms/op
Iteration   1: 2.005 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.005 ms/op


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
# Warmup Iteration   1: 3.368 ±(99.9%) 0.047 ms/op
Iteration   1: 2.282 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.282 ms/op


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.081 ms/op
Iteration   1: 3.395 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.395 ms/op


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
# Warmup Iteration   1: 3.495 ±(99.9%) 0.086 ms/op
Iteration   1: 2.147 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   1.982 ms/op
                 createUser·p0.90:   2.982 ms/op
                 createUser·p0.95:   3.244 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  17.735 ms/op
                 createUser·p0.9999: 19.564 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14892
  mean =      2.147 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 11724 
    [ 2.500,  3.750) = 2839 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      3.850 ms/op
     p(99.9000) =     17.735 ms/op
     p(99.9900) =     19.564 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 2.956 ±(99.9%) 0.061 ms/op
Iteration   1: 1.920 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   1.849 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.508 ms/op
                 existUser·p0.99:   3.165 ms/op
                 existUser·p0.999:  10.234 ms/op
                 existUser·p0.9999: 10.393 ms/op
                 existUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16673
  mean =      1.920 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 36 
    [ 1.000,  2.000) = 10495 
    [ 2.000,  3.000) = 5914 
    [ 3.000,  4.000) = 141 
    [ 4.000,  5.000) = 35 
    [ 5.000,  6.000) = 0 
    [ 6.000,  7.000) = 19 
    [ 7.000,  8.000) = 1 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      1.849 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.508 ms/op
     p(99.0000) =      3.165 ms/op
     p(99.9000) =     10.234 ms/op
     p(99.9900) =     10.393 ms/op
     p(99.9990) =     10.404 ms/op
     p(99.9999) =     10.404 ms/op
    p(100.0000) =     10.404 ms/op


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
# Warmup Iteration   1: 3.383 ±(99.9%) 0.083 ms/op
Iteration   1: 2.209 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.502 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.753 ms/op
                 getUser·p0.95:   2.937 ms/op
                 getUser·p0.99:   3.538 ms/op
                 getUser·p0.999:  18.367 ms/op
                 getUser·p0.9999: 18.929 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14477
  mean =      2.209 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 197 
    [ 1.250,  2.500) = 10582 
    [ 2.500,  3.750) = 3566 
    [ 3.750,  5.000) = 90 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.502 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      3.538 ms/op
     p(99.9000) =     18.367 ms/op
     p(99.9900) =     18.929 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ±(99.9%) 0.134 ms/op
Iteration   1: 3.819 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.743 ms/op
                 listUser·p0.99:   5.884 ms/op
                 listUser·p0.999:  14.563 ms/op
                 listUser·p0.9999: 16.417 ms/op
                 listUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8371
  mean =      3.819 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 495 
    [ 2.500,  3.750) = 2839 
    [ 3.750,  5.000) = 4743 
    [ 5.000,  6.250) = 242 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      5.884 ms/op
     p(99.9000) =     14.563 ms/op
     p(99.9900) =     16.417 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.381          ops/ms
ClientSimple.existUser                       thrpt         12.781          ops/ms
ClientSimple.getUser                         thrpt         13.030          ops/ms
ClientSimple.listUser                        thrpt          9.344          ops/ms
ClientSimple.createUser                       avgt          2.042           ms/op
ClientSimple.existUser                        avgt          2.005           ms/op
ClientSimple.getUser                          avgt          2.282           ms/op
ClientSimple.listUser                         avgt          3.395           ms/op
ClientSimple.createUser                     sample  14892   2.147 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.883           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.982           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.244           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.850           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.735           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.564           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.628           ms/op
ClientSimple.existUser                      sample  16673   1.920 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.767           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.849           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.508           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.165           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.234           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.393           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.404           ms/op
ClientSimple.getUser                        sample  14477   2.209 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.502           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.753           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.937           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.367           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.929           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.973           ms/op
ClientSimple.listUser                       sample   8371   3.819 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.871           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.743           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.884           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.563           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.417           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.417           ms/op

Benchmark result is saved to 1714392957011.json
