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
# Warmup Iteration   1: 0.667 ops/ms
Iteration   1: 5.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.949 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.563 ops/ms
Iteration   1: 11.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.357 ops/ms


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
# Warmup Iteration   1: 6.043 ops/ms
Iteration   1: 11.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.413 ops/ms


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
# Warmup Iteration   1: 3.873 ops/ms
Iteration   1: 9.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.066 ops/ms


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.074 ms/op
Iteration   1: 2.325 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.325 ms/op


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
# Warmup Iteration   1: 3.053 ±(99.9%) 0.052 ms/op
Iteration   1: 2.002 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.002 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.058 ms/op
Iteration   1: 2.117 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.117 ms/op


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.100 ms/op
Iteration   1: 3.563 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.563 ms/op


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
# Warmup Iteration   1: 3.300 ±(99.9%) 0.079 ms/op
Iteration   1: 2.107 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   1.905 ms/op
                 createUser·p0.90:   2.515 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   5.918 ms/op
                 createUser·p0.999:  26.247 ms/op
                 createUser·p0.9999: 28.978 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15179
  mean =      2.107 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13589 
    [ 2.500,  5.000) = 1339 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 24 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 50 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.905 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      5.918 ms/op
     p(99.9000) =     26.247 ms/op
     p(99.9900) =     28.978 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.078 ms/op
Iteration   1: 1.911 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  17.995 ms/op
                 existUser·p0.9999: 18.164 ms/op
                 existUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16846
  mean =      1.911 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 565 
    [ 1.250,  2.500) = 14925 
    [ 2.500,  3.750) = 1124 
    [ 3.750,  5.000) = 155 
    [ 5.000,  6.250) = 47 
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
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     17.995 ms/op
     p(99.9900) =     18.164 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.186 ms/op
    p(100.0000) =     18.186 ms/op


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
# Warmup Iteration   1: 3.620 ±(99.9%) 0.113 ms/op
Iteration   1: 2.140 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.916 ms/op
                 getUser·p0.50:   2.011 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.957 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  10.599 ms/op
                 getUser·p0.9999: 10.976 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15039
  mean =      2.140 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 12511 
    [ 2.500,  3.750) = 2126 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 18 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      2.011 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.957 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =     10.599 ms/op
     p(99.9900) =     10.976 ms/op
     p(99.9990) =     11.092 ms/op
     p(99.9999) =     11.092 ms/op
    p(100.0000) =     11.092 ms/op


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
# Warmup Iteration   1: 4.406 ±(99.9%) 0.128 ms/op
Iteration   1: 3.616 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.070 ms/op
                 listUser·p0.999:  29.688 ms/op
                 listUser·p0.9999: 29.819 ms/op
                 listUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8860
  mean =      3.616 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 529 
    [ 2.500,  5.000) = 8168 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     29.688 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     29.819 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.949          ops/ms
ClientSimple.existUser                       thrpt         11.357          ops/ms
ClientSimple.getUser                         thrpt         11.413          ops/ms
ClientSimple.listUser                        thrpt          9.066          ops/ms
ClientSimple.createUser                       avgt          2.325           ms/op
ClientSimple.existUser                        avgt          2.002           ms/op
ClientSimple.getUser                          avgt          2.117           ms/op
ClientSimple.listUser                         avgt          3.563           ms/op
ClientSimple.createUser                     sample  15179   2.107 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.589           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.905           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.918           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.247           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.978           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.131           ms/op
ClientSimple.existUser                      sample  16846   1.911 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.418           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.481           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.995           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.164           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.186           ms/op
ClientSimple.getUser                        sample  15039   2.140 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.916           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.011           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.957           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.440           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.599           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.976           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.092           ms/op
ClientSimple.listUser                       sample   8860   3.616 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.040           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.070           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.688           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.819           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.819           ms/op

Benchmark result is saved to 1712081495947.json
