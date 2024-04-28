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
# Warmup Iteration   1: 1.629 ops/ms
Iteration   1: 6.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.428 ops/ms


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
# Warmup Iteration   1: 6.216 ops/ms
Iteration   1: 13.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.045 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 5.966 ops/ms
Iteration   1: 14.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.000 ops/ms


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
# Warmup Iteration   1: 3.643 ops/ms
Iteration   1: 8.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.550 ops/ms


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
# Warmup Iteration   1: 3.632 ±(99.9%) 0.072 ms/op
Iteration   1: 2.101 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.101 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.064 ms/op
Iteration   1: 1.877 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.877 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.052 ms/op
Iteration   1: 2.095 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.095 ms/op


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
# Warmup Iteration   1: 4.913 ±(99.9%) 0.109 ms/op
Iteration   1: 3.179 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.179 ms/op


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
# Warmup Iteration   1: 3.541 ±(99.9%) 0.090 ms/op
Iteration   1: 2.075 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   0.764 ms/op
                 createUser·p0.50:   1.982 ms/op
                 createUser·p0.90:   2.531 ms/op
                 createUser·p0.95:   2.785 ms/op
                 createUser·p0.99:   4.471 ms/op
                 createUser·p0.999:  16.246 ms/op
                 createUser·p0.9999: 17.579 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15422
  mean =      2.075 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 13635 
    [ 2.500,  3.750) = 1486 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 51 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.471 ms/op
     p(99.9000) =     16.246 ms/op
     p(99.9900) =     17.579 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 2.866 ±(99.9%) 0.061 ms/op
Iteration   1: 1.822 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.300 ms/op
                 existUser·p0.50:   1.810 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  12.206 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17533
  mean =      1.822 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1811 
    [ 1.250,  2.500) = 14881 
    [ 2.500,  3.750) = 614 
    [ 3.750,  5.000) = 129 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.300 ms/op
     p(50.0000) =      1.810 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      4.018 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     12.354 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.091 ms/op
Iteration   1: 2.171 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.048 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.193 ms/op
                 getUser·p0.99:   4.505 ms/op
                 getUser·p0.999:  15.696 ms/op
                 getUser·p0.9999: 16.882 ms/op
                 getUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15007
  mean =      2.171 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 887 
    [ 1.250,  2.500) = 9376 
    [ 2.500,  3.750) = 4525 
    [ 3.750,  5.000) = 120 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.048 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.193 ms/op
     p(99.0000) =      4.505 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     16.882 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.367 ±(99.9%) 0.134 ms/op
Iteration   1: 3.097 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   2.736 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.276 ms/op
                 listUser·p0.999:  18.022 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.579 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10329
  mean =      3.097 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1259 
    [ 2.500,  3.750) = 7195 
    [ 3.750,  5.000) = 1696 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 19 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.736 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     18.022 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     18.579 ms/op
     p(99.9999) =     18.579 ms/op
    p(100.0000) =     18.579 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.428          ops/ms
ClientSimple.existUser                       thrpt         13.045          ops/ms
ClientSimple.getUser                         thrpt         14.000          ops/ms
ClientSimple.listUser                        thrpt          8.550          ops/ms
ClientSimple.createUser                       avgt          2.101           ms/op
ClientSimple.existUser                        avgt          1.877           ms/op
ClientSimple.getUser                          avgt          2.095           ms/op
ClientSimple.listUser                         avgt          3.179           ms/op
ClientSimple.createUser                     sample  15422   2.075 ± 0.023   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.764           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.982           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.531           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.785           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.471           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.246           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.579           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.596           ms/op
ClientSimple.existUser                      sample  17533   1.822 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.300           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.810           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.018           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.206           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.354           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.354           ms/op
ClientSimple.getUser                        sample  15007   2.171 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.586           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.048           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.006           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.193           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.505           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.696           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.882           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.793           ms/op
ClientSimple.listUser                       sample  10329   3.097 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.383           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.276           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.022           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.579           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.579           ms/op

Benchmark result is saved to 1714306495285.json
