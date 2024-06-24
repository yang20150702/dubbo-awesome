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
# Warmup Iteration   1: 1.521 ops/ms
Iteration   1: 7.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.561 ops/ms


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
# Warmup Iteration   1: 5.551 ops/ms
Iteration   1: 12.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.553 ops/ms


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
# Warmup Iteration   1: 5.276 ops/ms
Iteration   1: 11.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.435 ops/ms


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
# Warmup Iteration   1: 5.764 ops/ms
Iteration   1: 8.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.388 ops/ms


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.087 ms/op
Iteration   1: 2.077 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.077 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.280 ±(99.9%) 0.050 ms/op
Iteration   1: 1.984 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.984 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ±(99.9%) 0.073 ms/op
Iteration   1: 2.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.074 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.583 ±(99.9%) 0.118 ms/op
Iteration   1: 3.393 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.393 ms/op


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.129 ms/op
Iteration   1: 2.357 ±(99.9%) 0.065 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   2.130 ms/op
                 createUser·p0.90:   2.658 ms/op
                 createUser·p0.95:   2.901 ms/op
                 createUser·p0.99:   7.881 ms/op
                 createUser·p0.999:  43.463 ms/op
                 createUser·p0.9999: 54.562 ms/op
                 createUser·p1.00:   55.837 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13813
  mean =      2.357 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 13560 
    [ 5.000, 10.000) = 150 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 37 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 27 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.130 ms/op
     p(90.0000) =      2.658 ms/op
     p(95.0000) =      2.901 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     43.463 ms/op
     p(99.9900) =     54.562 ms/op
     p(99.9990) =     55.837 ms/op
     p(99.9999) =     55.837 ms/op
    p(100.0000) =     55.837 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.067 ms/op
Iteration   1: 1.754 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   1.657 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   2.997 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.383 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18229
  mean =      1.754 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 683 
    [ 1.250,  2.500) = 17128 
    [ 2.500,  3.750) = 280 
    [ 3.750,  5.000) = 27 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.657 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      2.997 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.383 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 3.482 ±(99.9%) 0.079 ms/op
Iteration   1: 1.950 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   1.790 ms/op
                 getUser·p0.90:   2.445 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  12.554 ms/op
                 getUser·p0.9999: 14.018 ms/op
                 getUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16395
  mean =      1.950 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 168 
    [ 1.250,  2.500) = 14854 
    [ 2.500,  3.750) = 1184 
    [ 3.750,  5.000) = 76 
    [ 5.000,  6.250) = 78 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.790 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     12.554 ms/op
     p(99.9900) =     14.018 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.136 ms/op
Iteration   1: 3.459 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.607 ms/op
                 listUser·p0.999:  16.318 ms/op
                 listUser·p0.9999: 16.974 ms/op
                 listUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9249
  mean =      3.459 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1603 
    [ 2.500,  3.750) = 4521 
    [ 3.750,  5.000) = 2711 
    [ 5.000,  6.250) = 303 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      6.607 ms/op
     p(99.9000) =     16.318 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.561          ops/ms
ClientSimple.existUser                       thrpt         12.553          ops/ms
ClientSimple.getUser                         thrpt         11.435          ops/ms
ClientSimple.listUser                        thrpt          8.388          ops/ms
ClientSimple.createUser                       avgt          2.077           ms/op
ClientSimple.existUser                        avgt          1.984           ms/op
ClientSimple.getUser                          avgt          2.074           ms/op
ClientSimple.listUser                         avgt          3.393           ms/op
ClientSimple.createUser                     sample  13813   2.357 ± 0.065   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.682           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.130           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.658           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.901           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.881           ms/op
ClientSimple.createUser:createUser·p0.999   sample         43.463           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         54.562           ms/op
ClientSimple.createUser:createUser·p1.00    sample         55.837           ms/op
ClientSimple.existUser                      sample  18229   1.754 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.674           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.657           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.997           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.383           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.383           ms/op
ClientSimple.getUser                        sample  16395   1.950 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.675           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.790           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.194           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.554           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.018           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.123           ms/op
ClientSimple.listUser                       sample   9249   3.459 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.061           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.607           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.318           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.974           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.974           ms/op

Benchmark result is saved to 1719252758761.json
