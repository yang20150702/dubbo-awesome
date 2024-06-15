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
# Warmup Iteration   1: 1.808 ops/ms
Iteration   1: 6.868 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.868 ops/ms


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
# Warmup Iteration   1: 7.224 ops/ms
Iteration   1: 10.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.905 ops/ms


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
# Warmup Iteration   1: 6.258 ops/ms
Iteration   1: 12.097 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.097 ops/ms


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
# Warmup Iteration   1: 4.761 ops/ms
Iteration   1: 7.950 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.950 ops/ms


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
# Warmup Iteration   1: 3.884 ±(99.9%) 0.080 ms/op
Iteration   1: 2.329 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.329 ms/op


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
# Warmup Iteration   1: 2.919 ±(99.9%) 0.044 ms/op
Iteration   1: 2.116 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.116 ms/op


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
# Warmup Iteration   1: 3.375 ±(99.9%) 0.069 ms/op
Iteration   1: 1.836 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.836 ms/op


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.081 ms/op
Iteration   1: 3.674 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.674 ms/op


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.120 ms/op
Iteration   1: 2.741 ±(99.9%) 0.226 ms/op
                 createUser·p0.00:   0.383 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.834 ms/op
                 createUser·p0.95:   3.531 ms/op
                 createUser·p0.99:   14.061 ms/op
                 createUser·p0.999:  141.033 ms/op
                 createUser·p0.9999: 142.344 ms/op
                 createUser·p1.00:   142.344 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11675
  mean =      2.741 ±(99.9%) 0.226 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 11535 
    [ 12.500,  25.000) = 108 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 0 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 32 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.383 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.834 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =     14.061 ms/op
     p(99.9000) =    141.033 ms/op
     p(99.9900) =    142.344 ms/op
     p(99.9990) =    142.344 ms/op
     p(99.9999) =    142.344 ms/op
    p(100.0000) =    142.344 ms/op


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
# Warmup Iteration   1: 3.092 ±(99.9%) 0.076 ms/op
Iteration   1: 1.973 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.804 ms/op
                 existUser·p0.90:   2.560 ms/op
                 existUser·p0.95:   2.695 ms/op
                 existUser·p0.99:   3.379 ms/op
                 existUser·p0.999:  10.682 ms/op
                 existUser·p0.9999: 12.017 ms/op
                 existUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16316
  mean =      1.973 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 350 
    [ 1.250,  2.500) = 13732 
    [ 2.500,  3.750) = 2183 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.695 ms/op
     p(99.0000) =      3.379 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     12.017 ms/op
     p(99.9990) =     12.255 ms/op
     p(99.9999) =     12.255 ms/op
    p(100.0000) =     12.255 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.102 ms/op
Iteration   1: 2.196 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.565 ms/op
                 getUser·p0.50:   2.075 ms/op
                 getUser·p0.90:   2.732 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  15.638 ms/op
                 getUser·p0.9999: 17.155 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14559
  mean =      2.196 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 230 
    [ 1.250,  2.500) = 11138 
    [ 2.500,  3.750) = 2843 
    [ 3.750,  5.000) = 236 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.732 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =     15.638 ms/op
     p(99.9900) =     17.155 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.130 ms/op
Iteration   1: 3.314 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.011 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  30.573 ms/op
                 listUser·p0.9999: 31.392 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9670
  mean =      3.314 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 908 
    [ 2.500,  5.000) = 8561 
    [ 5.000,  7.500) = 167 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     30.573 ms/op
     p(99.9900) =     31.392 ms/op
     p(99.9990) =     31.392 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.868          ops/ms
ClientSimple.existUser                       thrpt          10.905          ops/ms
ClientSimple.getUser                         thrpt          12.097          ops/ms
ClientSimple.listUser                        thrpt           7.950          ops/ms
ClientSimple.createUser                       avgt           2.329           ms/op
ClientSimple.existUser                        avgt           2.116           ms/op
ClientSimple.getUser                          avgt           1.836           ms/op
ClientSimple.listUser                         avgt           3.674           ms/op
ClientSimple.createUser                     sample  11675    2.741 ± 0.226   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.383           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.834           ms/op
ClientSimple.createUser:createUser·p0.95    sample           3.531           ms/op
ClientSimple.createUser:createUser·p0.99    sample          14.061           ms/op
ClientSimple.createUser:createUser·p0.999   sample         141.033           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         142.344           ms/op
ClientSimple.createUser:createUser·p1.00    sample         142.344           ms/op
ClientSimple.existUser                      sample  16316    1.973 ± 0.015   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.532           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.804           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.560           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.695           ms/op
ClientSimple.existUser:existUser·p0.99      sample           3.379           ms/op
ClientSimple.existUser:existUser·p0.999     sample          10.682           ms/op
ClientSimple.existUser:existUser·p0.9999    sample          12.017           ms/op
ClientSimple.existUser:existUser·p1.00      sample          12.255           ms/op
ClientSimple.getUser                        sample  14559    2.196 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.565           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.075           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.732           ms/op
ClientSimple.getUser:getUser·p0.95          sample           3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample           4.555           ms/op
ClientSimple.getUser:getUser·p0.999         sample          15.638           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          17.155           ms/op
ClientSimple.getUser:getUser·p1.00          sample          18.350           ms/op
ClientSimple.listUser                       sample   9670    3.314 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample           0.919           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.011           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.166           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.661           ms/op
ClientSimple.listUser:listUser·p0.999       sample          30.573           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          31.392           ms/op
ClientSimple.listUser:listUser·p1.00        sample          31.392           ms/op

Benchmark result is saved to 1718431899355.json
