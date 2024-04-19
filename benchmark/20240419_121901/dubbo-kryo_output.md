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
# Warmup Iteration   1: 1.769 ops/ms
Iteration   1: 6.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.442 ops/ms


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
# Warmup Iteration   1: 5.920 ops/ms
Iteration   1: 11.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.698 ops/ms


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
# Warmup Iteration   1: 5.926 ops/ms
Iteration   1: 14.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.108 ops/ms


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
# Warmup Iteration   1: 4.427 ops/ms
Iteration   1: 9.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.226 ops/ms


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.065 ms/op
Iteration   1: 2.269 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.269 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.048 ms/op
Iteration   1: 2.031 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.031 ms/op


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
# Warmup Iteration   1: 3.303 ±(99.9%) 0.062 ms/op
Iteration   1: 1.891 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.891 ms/op


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.106 ms/op
Iteration   1: 3.254 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.254 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.169 ms/op
Iteration   1: 2.423 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   2.286 ms/op
                 createUser·p0.90:   2.839 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   6.216 ms/op
                 createUser·p0.999:  20.244 ms/op
                 createUser·p0.9999: 20.678 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13202
  mean =      2.423 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9140 
    [ 2.500,  5.000) = 3878 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.795 ms/op
     p(50.0000) =      2.286 ms/op
     p(90.0000) =      2.839 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      6.216 ms/op
     p(99.9000) =     20.244 ms/op
     p(99.9900) =     20.678 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.121 ±(99.9%) 0.065 ms/op
Iteration   1: 2.152 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   1.997 ms/op
                 existUser·p0.90:   2.780 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   5.074 ms/op
                 existUser·p0.999:  17.339 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14861
  mean =      2.152 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 438 
    [ 1.250,  2.500) = 11344 
    [ 2.500,  3.750) = 2881 
    [ 3.750,  5.000) = 39 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.780 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      5.074 ms/op
     p(99.9000) =     17.339 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.096 ms/op
Iteration   1: 1.927 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   1.776 ms/op
                 getUser·p0.90:   2.400 ms/op
                 getUser·p0.95:   2.658 ms/op
                 getUser·p0.99:   4.032 ms/op
                 getUser·p0.999:  16.350 ms/op
                 getUser·p0.9999: 17.568 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16761
  mean =      1.927 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 15396 
    [ 2.500,  3.750) = 1071 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 19 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      1.776 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.658 ms/op
     p(99.0000) =      4.032 ms/op
     p(99.9000) =     16.350 ms/op
     p(99.9900) =     17.568 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 4.415 ±(99.9%) 0.124 ms/op
Iteration   1: 3.789 ±(99.9%) 0.056 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.236 ms/op
                 listUser·p0.999:  26.308 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8426
  mean =      3.789 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 593 
    [ 2.500,  5.000) = 7490 
    [ 5.000,  7.500) = 277 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.938 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.236 ms/op
     p(99.9000) =     26.308 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.442          ops/ms
ClientSimple.existUser                       thrpt         11.698          ops/ms
ClientSimple.getUser                         thrpt         14.108          ops/ms
ClientSimple.listUser                        thrpt          9.226          ops/ms
ClientSimple.createUser                       avgt          2.269           ms/op
ClientSimple.existUser                        avgt          2.031           ms/op
ClientSimple.getUser                          avgt          1.891           ms/op
ClientSimple.listUser                         avgt          3.254           ms/op
ClientSimple.createUser                     sample  13202   2.423 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.795           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.286           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.839           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.216           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.244           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.678           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.709           ms/op
ClientSimple.existUser                      sample  14861   2.152 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.644           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.997           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.780           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.047           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.074           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.339           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.531           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.531           ms/op
ClientSimple.getUser                        sample  16761   1.927 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.709           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.776           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.400           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.658           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.032           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.350           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.568           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.055           ms/op
ClientSimple.listUser                       sample   8426   3.789 ± 0.056   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.938           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.236           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.308           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.804           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.804           ms/op

Benchmark result is saved to 1713528899476.json
