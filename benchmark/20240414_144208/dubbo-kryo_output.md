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
# Warmup Iteration   1: 1.878 ops/ms
Iteration   1: 7.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.027 ops/ms


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
# Warmup Iteration   1: 6.431 ops/ms
Iteration   1: 14.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.067 ops/ms


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
# Warmup Iteration   1: 7.026 ops/ms
Iteration   1: 14.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.311 ops/ms


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
# Warmup Iteration   1: 5.346 ops/ms
Iteration   1: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.374 ops/ms


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.083 ms/op
Iteration   1: 2.107 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.107 ms/op


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
# Warmup Iteration   1: 3.290 ±(99.9%) 0.058 ms/op
Iteration   1: 1.811 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.811 ms/op


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.065 ms/op
Iteration   1: 2.249 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.249 ms/op


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
# Warmup Iteration   1: 4.163 ±(99.9%) 0.079 ms/op
Iteration   1: 3.358 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.358 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.082 ms/op
Iteration   1: 2.365 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.253 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.815 ms/op
                 createUser·p0.999:  14.254 ms/op
                 createUser·p0.9999: 14.500 ms/op
                 createUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13513
  mean =      2.365 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 7934 
    [ 2.500,  3.750) = 5134 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.815 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     14.500 ms/op
     p(99.9990) =     14.500 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 3.012 ±(99.9%) 0.074 ms/op
Iteration   1: 1.978 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.344 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   4.558 ms/op
                 existUser·p0.999:  30.179 ms/op
                 existUser·p0.9999: 30.802 ms/op
                 existUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16159
  mean =      1.978 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15207 
    [ 2.500,  5.000) = 818 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      4.558 ms/op
     p(99.9000) =     30.179 ms/op
     p(99.9900) =     30.802 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.069 ms/op
Iteration   1: 2.149 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.447 ms/op
                 getUser·p0.50:   1.976 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   3.023 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  20.938 ms/op
                 getUser·p0.9999: 30.635 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15036
  mean =      2.149 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12561 
    [ 2.500,  5.000) = 2268 
    [ 5.000,  7.500) = 127 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      1.976 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     20.938 ms/op
     p(99.9900) =     30.635 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.154 ms/op
Iteration   1: 3.497 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.281 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.732 ms/op
                 listUser·p0.99:   9.093 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 21.463 ms/op
                 listUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9147
  mean =      3.497 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 546 
    [ 2.500,  5.000) = 8308 
    [ 5.000,  7.500) = 197 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.831 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.732 ms/op
     p(99.0000) =      9.093 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     21.463 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.027          ops/ms
ClientSimple.existUser                       thrpt         14.067          ops/ms
ClientSimple.getUser                         thrpt         14.311          ops/ms
ClientSimple.listUser                        thrpt          8.374          ops/ms
ClientSimple.createUser                       avgt          2.107           ms/op
ClientSimple.existUser                        avgt          1.811           ms/op
ClientSimple.getUser                          avgt          2.249           ms/op
ClientSimple.listUser                         avgt          3.358           ms/op
ClientSimple.createUser                     sample  13513   2.365 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.586           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.253           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.256           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.815           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.254           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.500           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.500           ms/op
ClientSimple.existUser                      sample  16159   1.978 ± 0.038   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.344           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.817           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.351           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.558           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.179           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.802           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.802           ms/op
ClientSimple.getUser                        sample  15036   2.149 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.447           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.976           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.023           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.464           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.938           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.635           ms/op
ClientSimple.getUser:getUser·p1.00          sample         31.097           ms/op
ClientSimple.listUser                       sample   9147   3.497 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.831           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.281           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.424           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.732           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.093           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.299           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.463           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.463           ms/op

Benchmark result is saved to 1713105466242.json
