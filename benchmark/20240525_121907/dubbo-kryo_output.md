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
# Warmup Iteration   1: 1.502 ops/ms
Iteration   1: 5.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.961 ops/ms


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
# Warmup Iteration   1: 5.468 ops/ms
Iteration   1: 11.142 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.142 ops/ms


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
# Warmup Iteration   1: 4.170 ops/ms
Iteration   1: 11.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.075 ops/ms


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
# Warmup Iteration   1: 5.012 ops/ms
Iteration   1: 8.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.056 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ±(99.9%) 0.109 ms/op
Iteration   1: 2.354 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.354 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.323 ±(99.9%) 0.060 ms/op
Iteration   1: 1.986 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.986 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 3.725 ±(99.9%) 0.096 ms/op
Iteration   1: 2.284 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.284 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.013 ±(99.9%) 0.128 ms/op
Iteration   1: 3.272 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.272 ms/op


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.162 ms/op
Iteration   1: 2.271 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   1.997 ms/op
                 createUser·p0.90:   2.662 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   9.393 ms/op
                 createUser·p0.999:  23.740 ms/op
                 createUser·p0.9999: 30.395 ms/op
                 createUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14171
  mean =      2.271 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12129 
    [ 2.500,  5.000) = 1684 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 149 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      1.997 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      9.393 ms/op
     p(99.9000) =     23.740 ms/op
     p(99.9900) =     30.395 ms/op
     p(99.9990) =     30.573 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 3.354 ±(99.9%) 0.081 ms/op
Iteration   1: 2.066 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   1.919 ms/op
                 existUser·p0.90:   2.736 ms/op
                 existUser·p0.95:   2.920 ms/op
                 existUser·p0.99:   3.314 ms/op
                 existUser·p0.999:  13.631 ms/op
                 existUser·p0.9999: 14.080 ms/op
                 existUser·p1.00:   14.107 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15503
  mean =      2.066 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 202 
    [ 1.250,  2.500) = 12416 
    [ 2.500,  3.750) = 2779 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.736 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.314 ms/op
     p(99.9000) =     13.631 ms/op
     p(99.9900) =     14.080 ms/op
     p(99.9990) =     14.107 ms/op
     p(99.9999) =     14.107 ms/op
    p(100.0000) =     14.107 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.111 ms/op
Iteration   1: 2.397 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   2.327 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  15.569 ms/op
                 getUser·p0.9999: 16.301 ms/op
                 getUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13358
  mean =      2.397 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 7692 
    [ 2.500,  3.750) = 5239 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      2.327 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.569 ms/op
     p(99.9900) =     16.301 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 6.049 ±(99.9%) 0.190 ms/op
Iteration   1: 3.863 ±(99.9%) 0.044 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.531 ms/op
                 listUser·p0.99:   8.005 ms/op
                 listUser·p0.999:  14.905 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8296
  mean =      3.863 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 389 
    [ 2.500,  3.750) = 3582 
    [ 3.750,  5.000) = 3681 
    [ 5.000,  6.250) = 392 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.348 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.531 ms/op
     p(99.0000) =      8.005 ms/op
     p(99.9000) =     14.905 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.961          ops/ms
ClientSimple.existUser                       thrpt         11.142          ops/ms
ClientSimple.getUser                         thrpt         11.075          ops/ms
ClientSimple.listUser                        thrpt          8.056          ops/ms
ClientSimple.createUser                       avgt          2.354           ms/op
ClientSimple.existUser                        avgt          1.986           ms/op
ClientSimple.getUser                          avgt          2.284           ms/op
ClientSimple.listUser                         avgt          3.272           ms/op
ClientSimple.createUser                     sample  14171   2.271 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.698           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.997           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.662           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.158           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.393           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.740           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.395           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.573           ms/op
ClientSimple.existUser                      sample  15503   2.066 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.751           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.919           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.920           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.314           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.631           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.080           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.107           ms/op
ClientSimple.getUser                        sample  13358   2.397 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.454           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.327           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.031           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.224           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.382           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.569           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.301           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.450           ms/op
ClientSimple.listUser                       sample   8296   3.863 ± 0.044   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.348           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.813           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.531           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.005           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.905           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.400           ms/op

Benchmark result is saved to 1716639317990.json
