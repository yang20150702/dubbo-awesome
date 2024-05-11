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
# Warmup Iteration   1: 1.828 ops/ms
Iteration   1: 6.614 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.614 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.714 ops/ms
Iteration   1: 11.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.729 ops/ms


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
# Warmup Iteration   1: 5.503 ops/ms
Iteration   1: 11.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.428 ops/ms


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
# Warmup Iteration   1: 5.420 ops/ms
Iteration   1: 8.757 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.757 ops/ms


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
# Warmup Iteration   1: 4.049 ±(99.9%) 0.066 ms/op
Iteration   1: 2.022 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.022 ms/op


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
# Warmup Iteration   1: 3.031 ±(99.9%) 0.048 ms/op
Iteration   1: 2.009 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.009 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.066 ms/op
Iteration   1: 2.185 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.185 ms/op


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
# Warmup Iteration   1: 6.466 ±(99.9%) 0.143 ms/op
Iteration   1: 3.541 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.541 ms/op


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
# Warmup Iteration   1: 3.586 ±(99.9%) 0.098 ms/op
Iteration   1: 2.320 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.378 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.031 ms/op
                 createUser·p0.99:   10.174 ms/op
                 createUser·p0.999:  28.432 ms/op
                 createUser·p0.9999: 38.803 ms/op
                 createUser·p1.00:   38.928 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13827
  mean =      2.320 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10804 
    [ 2.500,  5.000) = 2802 
    [ 5.000,  7.500) = 65 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.031 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     28.432 ms/op
     p(99.9900) =     38.803 ms/op
     p(99.9990) =     38.928 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


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
# Warmup Iteration   1: 2.866 ±(99.9%) 0.066 ms/op
Iteration   1: 1.767 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.279 ms/op
                 existUser·p0.50:   1.716 ms/op
                 existUser·p0.90:   2.122 ms/op
                 existUser·p0.95:   2.273 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 10.554 ms/op
                 existUser·p1.00:   10.584 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 19073
  mean =      1.767 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 535 
    [ 1.250,  2.500) = 18121 
    [ 2.500,  3.750) = 251 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.279 ms/op
     p(50.0000) =      1.716 ms/op
     p(90.0000) =      2.122 ms/op
     p(95.0000) =      2.273 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     10.554 ms/op
     p(99.9990) =     10.584 ms/op
     p(99.9999) =     10.584 ms/op
    p(100.0000) =     10.584 ms/op


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
# Warmup Iteration   1: 3.513 ±(99.9%) 0.128 ms/op
Iteration   1: 2.419 ±(99.9%) 0.127 ms/op
                 getUser·p0.00:   0.451 ms/op
                 getUser·p0.50:   1.954 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.757 ms/op
                 getUser·p0.99:   12.539 ms/op
                 getUser·p0.999:  81.299 ms/op
                 getUser·p0.9999: 92.449 ms/op
                 getUser·p1.00:   92.537 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13368
  mean =      2.419 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 13217 
    [ 10.000,  20.000) = 70 
    [ 20.000,  30.000) = 18 
    [ 30.000,  40.000) = 6 
    [ 40.000,  50.000) = 17 
    [ 50.000,  60.000) = 7 
    [ 60.000,  70.000) = 10 
    [ 70.000,  80.000) = 9 
    [ 80.000,  90.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.954 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =     12.539 ms/op
     p(99.9000) =     81.299 ms/op
     p(99.9900) =     92.449 ms/op
     p(99.9990) =     92.537 ms/op
     p(99.9999) =     92.537 ms/op
    p(100.0000) =     92.537 ms/op


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.133 ms/op
Iteration   1: 3.332 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   3.060 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  18.541 ms/op
                 listUser·p0.9999: 21.332 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9593
  mean =      3.332 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 444 
    [ 2.500,  5.000) = 8935 
    [ 5.000,  7.500) = 150 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     18.541 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.614          ops/ms
ClientSimple.existUser                       thrpt         11.729          ops/ms
ClientSimple.getUser                         thrpt         11.428          ops/ms
ClientSimple.listUser                        thrpt          8.757          ops/ms
ClientSimple.createUser                       avgt          2.022           ms/op
ClientSimple.existUser                        avgt          2.009           ms/op
ClientSimple.getUser                          avgt          2.185           ms/op
ClientSimple.listUser                         avgt          3.541           ms/op
ClientSimple.createUser                     sample  13827   2.320 ± 0.051   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.378           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.031           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.174           ms/op
ClientSimple.createUser:createUser·p0.999   sample         28.432           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.803           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.928           ms/op
ClientSimple.existUser                      sample  19073   1.767 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.279           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.716           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.122           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.674           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.453           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         10.554           ms/op
ClientSimple.existUser:existUser·p1.00      sample         10.584           ms/op
ClientSimple.getUser                        sample  13368   2.419 ± 0.127   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.451           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.954           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.757           ms/op
ClientSimple.getUser:getUser·p0.99          sample         12.539           ms/op
ClientSimple.getUser:getUser·p0.999         sample         81.299           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         92.449           ms/op
ClientSimple.getUser:getUser·p1.00          sample         92.537           ms/op
ClientSimple.listUser                       sample   9593   3.332 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.974           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.060           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.059           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.545           ms/op
ClientSimple.listUser:listUser·p0.999       sample         18.541           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.332           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.332           ms/op

Benchmark result is saved to 1715429655027.json
