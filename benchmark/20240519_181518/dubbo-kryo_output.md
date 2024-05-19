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
# Warmup Iteration   1: 2.006 ops/ms
Iteration   1: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.183 ops/ms


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
# Warmup Iteration   1: 5.614 ops/ms
Iteration   1: 12.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.253 ops/ms


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
# Warmup Iteration   1: 6.181 ops/ms
Iteration   1: 14.846 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.846 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.818 ops/ms
Iteration   1: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.096 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ±(99.9%) 0.071 ms/op
Iteration   1: 2.331 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.331 ms/op


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
# Warmup Iteration   1: 2.890 ±(99.9%) 0.049 ms/op
Iteration   1: 1.787 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.787 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.058 ms/op
Iteration   1: 2.036 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.036 ms/op


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
# Warmup Iteration   1: 4.374 ±(99.9%) 0.074 ms/op
Iteration   1: 3.402 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.402 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.077 ms/op
Iteration   1: 2.118 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   1.837 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   7.692 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 17.102 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15081
  mean =      2.118 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 242 
    [ 1.250,  2.500) = 12393 
    [ 2.500,  3.750) = 1999 
    [ 3.750,  5.000) = 95 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      1.837 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     17.102 ms/op
     p(99.9990) =     17.269 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.801 ±(99.9%) 0.060 ms/op
Iteration   1: 1.945 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  18.252 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16543
  mean =      1.945 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 624 
    [ 1.250,  2.500) = 14815 
    [ 2.500,  3.750) = 869 
    [ 3.750,  5.000) = 89 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     18.252 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ±(99.9%) 0.078 ms/op
Iteration   1: 2.097 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.638 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.795 ms/op
                 getUser·p0.999:  12.829 ms/op
                 getUser·p0.9999: 13.351 ms/op
                 getUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15267
  mean =      2.097 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 310 
    [ 1.250,  2.500) = 12524 
    [ 2.500,  3.750) = 2277 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 1 
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
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.795 ms/op
     p(99.9000) =     12.829 ms/op
     p(99.9900) =     13.351 ms/op
     p(99.9990) =     13.386 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.139 ms/op
Iteration   1: 3.892 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   6.483 ms/op
                 listUser·p0.999:  8.010 ms/op
                 listUser·p0.9999: 8.421 ms/op
                 listUser·p1.00:   8.421 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8226
  mean =      3.892 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 31 
    [2.000, 2.500) = 157 
    [2.500, 3.000) = 552 
    [3.000, 3.500) = 964 
    [3.500, 4.000) = 3144 
    [4.000, 4.500) = 2518 
    [4.500, 5.000) = 514 
    [5.000, 5.500) = 126 
    [5.500, 6.000) = 78 
    [6.000, 6.500) = 53 
    [6.500, 7.000) = 40 
    [7.000, 7.500) = 31 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.483 ms/op
     p(99.9000) =      8.010 ms/op
     p(99.9900) =      8.421 ms/op
     p(99.9990) =      8.421 ms/op
     p(99.9999) =      8.421 ms/op
    p(100.0000) =      8.421 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.183          ops/ms
ClientSimple.existUser                       thrpt         12.253          ops/ms
ClientSimple.getUser                         thrpt         14.846          ops/ms
ClientSimple.listUser                        thrpt          9.096          ops/ms
ClientSimple.createUser                       avgt          2.331           ms/op
ClientSimple.existUser                        avgt          1.787           ms/op
ClientSimple.getUser                          avgt          2.036           ms/op
ClientSimple.listUser                         avgt          3.402           ms/op
ClientSimple.createUser                     sample  15081   2.118 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.607           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.837           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.113           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.692           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.777           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.102           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.269           ms/op
ClientSimple.existUser                      sample  16543   1.945 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.628           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.481           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.252           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.366           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.366           ms/op
ClientSimple.getUser                        sample  15267   2.097 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.518           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.638           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.795           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.829           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.351           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.386           ms/op
ClientSimple.listUser                       sample   8226   3.892 ± 0.025   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.845           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.899           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.858           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.483           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.010           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.421           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.421           ms/op

Benchmark result is saved to 1716142259418.json
