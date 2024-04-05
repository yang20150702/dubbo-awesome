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
# Warmup Iteration   1: 1.443 ops/ms
Iteration   1: 5.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.935 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ops/ms
Iteration   1: 11.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.100 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 5.726 ops/ms
Iteration   1: 11.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.340 ops/ms


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
# Warmup Iteration   1: 3.337 ops/ms
Iteration   1: 7.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.378 ops/ms


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
# Warmup Iteration   1: 4.466 ±(99.9%) 0.082 ms/op
Iteration   1: 2.252 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.252 ms/op


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
# Warmup Iteration   1: 3.349 ±(99.9%) 0.066 ms/op
Iteration   1: 1.964 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.964 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ±(99.9%) 0.099 ms/op
Iteration   1: 2.238 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.238 ms/op


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
# Warmup Iteration   1: 5.620 ±(99.9%) 0.110 ms/op
Iteration   1: 3.751 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.751 ms/op


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
# Warmup Iteration   1: 4.903 ±(99.9%) 0.137 ms/op
Iteration   1: 2.399 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   2.204 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   6.230 ms/op
                 createUser·p0.999:  14.418 ms/op
                 createUser·p0.9999: 16.968 ms/op
                 createUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13355
  mean =      2.399 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 260 
    [ 1.250,  2.500) = 8916 
    [ 2.500,  3.750) = 3593 
    [ 3.750,  5.000) = 329 
    [ 5.000,  6.250) = 127 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.204 ms/op
     p(90.0000) =      3.281 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      6.230 ms/op
     p(99.9000) =     14.418 ms/op
     p(99.9900) =     16.968 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 3.615 ±(99.9%) 0.095 ms/op
Iteration   1: 1.963 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.474 ms/op
                 existUser·p0.95:   2.777 ms/op
                 existUser·p0.99:   5.226 ms/op
                 existUser·p0.999:  10.715 ms/op
                 existUser·p0.9999: 11.587 ms/op
                 existUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16277
  mean =      1.963 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 352 
    [ 1.250,  2.500) = 14416 
    [ 2.500,  3.750) = 1130 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 46 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.543 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     11.587 ms/op
     p(99.9990) =     11.649 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


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
# Warmup Iteration   1: 3.532 ±(99.9%) 0.093 ms/op
Iteration   1: 2.125 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   1.997 ms/op
                 getUser·p0.90:   2.707 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  14.680 ms/op
                 getUser·p0.9999: 16.145 ms/op
                 getUser·p1.00:   16.318 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15282
  mean =      2.125 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 12131 
    [ 2.500,  3.750) = 2876 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     16.145 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


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
# Warmup Iteration   1: 5.178 ±(99.9%) 0.187 ms/op
Iteration   1: 3.717 ±(99.9%) 0.042 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   3.285 ms/op
                 listUser·p0.90:   5.085 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8592
  mean =      3.717 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 57 
    [ 2.500,  3.750) = 5879 
    [ 3.750,  5.000) = 1724 
    [ 5.000,  6.250) = 720 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      5.085 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.170 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.935          ops/ms
ClientSimple.existUser                       thrpt         11.100          ops/ms
ClientSimple.getUser                         thrpt         11.340          ops/ms
ClientSimple.listUser                        thrpt          7.378          ops/ms
ClientSimple.createUser                       avgt          2.252           ms/op
ClientSimple.existUser                        avgt          1.964           ms/op
ClientSimple.getUser                          avgt          2.238           ms/op
ClientSimple.listUser                         avgt          3.751           ms/op
ClientSimple.createUser                     sample  13355   2.399 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.839           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.204           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.281           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.637           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.230           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.418           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.968           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.826           ms/op
ClientSimple.existUser                      sample  16277   1.963 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.543           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.474           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.777           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.226           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.715           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.587           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.649           ms/op
ClientSimple.getUser                        sample  15282   2.125 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.769           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.997           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.707           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.145           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.680           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.145           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.318           ms/op
ClientSimple.listUser                       sample   8592   3.717 ± 0.042   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.922           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.285           ms/op
ClientSimple.listUser:listUser·p0.90        sample          5.085           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.865           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.356           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.105           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.170           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.170           ms/op

Benchmark result is saved to 1712277467923.json
