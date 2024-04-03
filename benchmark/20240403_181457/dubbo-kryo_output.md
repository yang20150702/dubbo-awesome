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
# Warmup Iteration   1: 1.795 ops/ms
Iteration   1: 7.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.584 ops/ms


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
# Warmup Iteration   1: 5.833 ops/ms
Iteration   1: 12.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.122 ops/ms


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
# Warmup Iteration   1: 6.597 ops/ms
Iteration   1: 13.782 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.782 ops/ms


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
# Warmup Iteration   1: 5.924 ops/ms
Iteration   1: 8.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.947 ops/ms


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.066 ms/op
Iteration   1: 2.259 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.259 ms/op


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
# Warmup Iteration   1: 3.011 ±(99.9%) 0.043 ms/op
Iteration   1: 1.878 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.878 ms/op


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
# Warmup Iteration   1: 2.942 ±(99.9%) 0.057 ms/op
Iteration   1: 1.926 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.926 ms/op


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
# Warmup Iteration   1: 5.355 ±(99.9%) 0.114 ms/op
Iteration   1: 3.468 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.468 ms/op


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
# Warmup Iteration   1: 3.412 ±(99.9%) 0.084 ms/op
Iteration   1: 2.482 ±(99.9%) 0.074 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.288 ms/op
                 createUser·p0.99:   11.698 ms/op
                 createUser·p0.999:  47.383 ms/op
                 createUser·p0.9999: 49.141 ms/op
                 createUser·p1.00:   49.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12882
  mean =      2.482 ±(99.9%) 0.074 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12531 
    [ 5.000, 10.000) = 177 
    [10.000, 15.000) = 107 
    [15.000, 20.000) = 33 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.288 ms/op
     p(99.0000) =     11.698 ms/op
     p(99.9000) =     47.383 ms/op
     p(99.9900) =     49.141 ms/op
     p(99.9990) =     49.349 ms/op
     p(99.9999) =     49.349 ms/op
    p(100.0000) =     49.349 ms/op


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
# Warmup Iteration   1: 2.870 ±(99.9%) 0.062 ms/op
Iteration   1: 1.739 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.399 ms/op
                 existUser·p0.50:   1.618 ms/op
                 existUser·p0.90:   2.023 ms/op
                 existUser·p0.95:   2.235 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  25.985 ms/op
                 existUser·p0.9999: 26.768 ms/op
                 existUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18386
  mean =      1.739 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17857 
    [ 2.500,  5.000) = 405 
    [ 5.000,  7.500) = 55 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      1.618 ms/op
     p(90.0000) =      2.023 ms/op
     p(95.0000) =      2.235 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     25.985 ms/op
     p(99.9900) =     26.768 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.141 ms/op
Iteration   1: 2.228 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   2.154 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   2.941 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 13.362 ms/op
                 getUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14391
  mean =      2.228 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 11150 
    [ 2.500,  3.750) = 2920 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.154 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     13.362 ms/op
     p(99.9990) =     13.369 ms/op
     p(99.9999) =     13.369 ms/op
    p(100.0000) =     13.369 ms/op


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
# Warmup Iteration   1: 4.689 ±(99.9%) 0.140 ms/op
Iteration   1: 3.449 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.157 ms/op
                 listUser·p0.50:   3.490 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  6.570 ms/op
                 listUser·p0.9999: 8.028 ms/op
                 listUser·p1.00:   8.028 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9286
  mean =      3.449 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 9 
    [1.500, 2.000) = 110 
    [2.000, 2.500) = 1100 
    [2.500, 3.000) = 1576 
    [3.000, 3.500) = 1915 
    [3.500, 4.000) = 2722 
    [4.000, 4.500) = 1070 
    [4.500, 5.000) = 404 
    [5.000, 5.500) = 203 
    [5.500, 6.000) = 138 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 5 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.157 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =      6.570 ms/op
     p(99.9900) =      8.028 ms/op
     p(99.9990) =      8.028 ms/op
     p(99.9999) =      8.028 ms/op
    p(100.0000) =      8.028 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.584          ops/ms
ClientSimple.existUser                       thrpt         12.122          ops/ms
ClientSimple.getUser                         thrpt         13.782          ops/ms
ClientSimple.listUser                        thrpt          8.947          ops/ms
ClientSimple.createUser                       avgt          2.259           ms/op
ClientSimple.existUser                        avgt          1.878           ms/op
ClientSimple.getUser                          avgt          1.926           ms/op
ClientSimple.listUser                         avgt          3.468           ms/op
ClientSimple.createUser                     sample  12882   2.482 ± 0.074   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.579           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.288           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.698           ms/op
ClientSimple.createUser:createUser·p0.999   sample         47.383           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         49.141           ms/op
ClientSimple.createUser:createUser·p1.00    sample         49.349           ms/op
ClientSimple.existUser                      sample  18386   1.739 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.399           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.618           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.023           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.235           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.330           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.985           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         26.768           ms/op
ClientSimple.existUser:existUser·p1.00      sample         27.263           ms/op
ClientSimple.getUser                        sample  14391   2.228 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.773           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.154           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.612           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.173           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.362           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.369           ms/op
ClientSimple.listUser                       sample   9286   3.449 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.157           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.490           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.366           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.874           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.759           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.570           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.028           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.028           ms/op

Benchmark result is saved to 1712167840218.json
