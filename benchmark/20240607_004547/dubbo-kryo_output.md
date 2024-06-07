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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 6.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.787 ops/ms


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
# Warmup Iteration   1: 6.046 ops/ms
Iteration   1: 13.023 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.023 ops/ms


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
# Warmup Iteration   1: 5.211 ops/ms
Iteration   1: 12.505 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.505 ops/ms


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
# Warmup Iteration   1: 4.946 ops/ms
Iteration   1: 8.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.683 ops/ms


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.071 ms/op
Iteration   1: 1.922 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.922 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.066 ms/op
Iteration   1: 2.042 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ±(99.9%) 0.054 ms/op
Iteration   1: 2.030 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.030 ms/op


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
# Warmup Iteration   1: 4.139 ±(99.9%) 0.097 ms/op
Iteration   1: 3.922 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.922 ms/op


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
# Warmup Iteration   1: 3.434 ±(99.9%) 0.077 ms/op
Iteration   1: 2.111 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   1.952 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   3.494 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  16.758 ms/op
                 createUser·p0.9999: 18.480 ms/op
                 createUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15144
  mean =      2.111 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 426 
    [ 1.250,  2.500) = 13002 
    [ 2.500,  3.750) = 1056 
    [ 3.750,  5.000) = 453 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =     16.758 ms/op
     p(99.9900) =     18.480 ms/op
     p(99.9990) =     18.514 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.090 ±(99.9%) 0.088 ms/op
Iteration   1: 1.997 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   1.870 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  16.122 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15998
  mean =      1.997 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14268 
    [ 2.500,  5.000) = 1601 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      1.870 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 3.411 ±(99.9%) 0.090 ms/op
Iteration   1: 1.914 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   1.782 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.699 ms/op
                 getUser·p0.99:   3.438 ms/op
                 getUser·p0.999:  11.638 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16669
  mean =      1.914 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 525 
    [ 1.250,  2.500) = 14266 
    [ 2.500,  3.750) = 1756 
    [ 3.750,  5.000) = 59 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      1.782 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.699 ms/op
     p(99.0000) =      3.438 ms/op
     p(99.9000) =     11.638 ms/op
     p(99.9900) =     13.009 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 4.556 ±(99.9%) 0.147 ms/op
Iteration   1: 3.109 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.639 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.620 ms/op
                 listUser·p0.999:  14.490 ms/op
                 listUser·p0.9999: 18.471 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10294
  mean =      3.109 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 2099 
    [ 2.500,  3.750) = 6677 
    [ 3.750,  5.000) = 1255 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.620 ms/op
     p(99.9000) =     14.490 ms/op
     p(99.9900) =     18.471 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.787          ops/ms
ClientSimple.existUser                       thrpt         13.023          ops/ms
ClientSimple.getUser                         thrpt         12.505          ops/ms
ClientSimple.listUser                        thrpt          8.683          ops/ms
ClientSimple.createUser                       avgt          1.922           ms/op
ClientSimple.existUser                        avgt          2.042           ms/op
ClientSimple.getUser                          avgt          2.030           ms/op
ClientSimple.listUser                         avgt          3.922           ms/op
ClientSimple.createUser                     sample  15144   2.111 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.853           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.952           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.494           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.554           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.758           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.480           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.514           ms/op
ClientSimple.existUser                      sample  15998   1.997 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.605           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.870           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.519           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.724           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.571           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.122           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.447           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.447           ms/op
ClientSimple.getUser                        sample  16669   1.914 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.490           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.782           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.438           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.638           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.009           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.009           ms/op
ClientSimple.listUser                       sample  10294   3.109 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.639           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.920           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.620           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.490           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.471           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.481           ms/op

Benchmark result is saved to 1717720883652.json
