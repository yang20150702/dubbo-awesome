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
# Warmup Iteration   1: 1.774 ops/ms
Iteration   1: 6.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.320 ops/ms


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
# Warmup Iteration   1: 6.349 ops/ms
Iteration   1: 11.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.349 ops/ms


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
# Warmup Iteration   1: 5.519 ops/ms
Iteration   1: 11.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.600 ops/ms


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
# Warmup Iteration   1: 5.181 ops/ms
Iteration   1: 8.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.325 ops/ms


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.067 ms/op
Iteration   1: 2.108 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.108 ms/op


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
# Warmup Iteration   1: 3.286 ±(99.9%) 0.053 ms/op
Iteration   1: 1.947 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.947 ms/op


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
# Warmup Iteration   1: 3.350 ±(99.9%) 0.054 ms/op
Iteration   1: 2.067 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.067 ms/op


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
# Warmup Iteration   1: 4.522 ±(99.9%) 0.097 ms/op
Iteration   1: 3.583 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.583 ms/op


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.125 ms/op
Iteration   1: 2.316 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.744 ms/op
                 createUser·p0.95:   3.064 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  32.342 ms/op
                 createUser·p0.9999: 35.209 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13804
  mean =      2.316 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11337 
    [ 2.500,  5.000) = 2230 
    [ 5.000,  7.500) = 129 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.744 ms/op
     p(95.0000) =      3.064 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     32.342 ms/op
     p(99.9900) =     35.209 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 3.059 ±(99.9%) 0.095 ms/op
Iteration   1: 1.862 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.462 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.499 ms/op
                 existUser·p0.99:   3.536 ms/op
                 existUser·p0.999:  12.714 ms/op
                 existUser·p0.9999: 13.210 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17459
  mean =      1.862 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 900 
    [ 1.250,  2.500) = 15689 
    [ 2.500,  3.750) = 762 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.462 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.499 ms/op
     p(99.0000) =      3.536 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     13.210 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 3.109 ±(99.9%) 0.077 ms/op
Iteration   1: 1.945 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   1.821 ms/op
                 getUser·p0.90:   2.564 ms/op
                 getUser·p0.95:   2.732 ms/op
                 getUser·p0.99:   3.256 ms/op
                 getUser·p0.999:  14.444 ms/op
                 getUser·p0.9999: 15.090 ms/op
                 getUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16419
  mean =      1.945 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 400 
    [ 1.250,  2.500) = 13933 
    [ 2.500,  3.750) = 2036 
    [ 3.750,  5.000) = 16 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.732 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     14.444 ms/op
     p(99.9900) =     15.090 ms/op
     p(99.9990) =     15.090 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.105 ms/op
Iteration   1: 3.890 ±(99.9%) 0.059 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.091 ms/op
                 listUser·p0.99:   9.072 ms/op
                 listUser·p0.999:  23.265 ms/op
                 listUser·p0.9999: 23.364 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8229
  mean =      3.890 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 450 
    [ 2.500,  5.000) = 7293 
    [ 5.000,  7.500) = 355 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.091 ms/op
     p(99.0000) =      9.072 ms/op
     p(99.9000) =     23.265 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.320          ops/ms
ClientSimple.existUser                       thrpt         11.349          ops/ms
ClientSimple.getUser                         thrpt         11.600          ops/ms
ClientSimple.listUser                        thrpt          8.325          ops/ms
ClientSimple.createUser                       avgt          2.108           ms/op
ClientSimple.existUser                        avgt          1.947           ms/op
ClientSimple.getUser                          avgt          2.067           ms/op
ClientSimple.listUser                         avgt          3.583           ms/op
ClientSimple.createUser                     sample  13804   2.316 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.664           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.064           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.882           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.342           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.209           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.783           ms/op
ClientSimple.existUser                      sample  17459   1.862 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.462           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.536           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.714           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.210           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.222           ms/op
ClientSimple.getUser                        sample  16419   1.945 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.821           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.564           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.732           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.256           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.444           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.090           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.090           ms/op
ClientSimple.listUser                       sample   8229   3.890 ± 0.059   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.049           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.091           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.072           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.265           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.364           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.364           ms/op

Benchmark result is saved to 1710850483531.json
