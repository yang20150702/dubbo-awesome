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
# Warmup Iteration   1: 1.731 ops/ms
Iteration   1: 6.305 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.305 ops/ms


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
# Warmup Iteration   1: 6.340 ops/ms
Iteration   1: 13.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.696 ops/ms


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
# Warmup Iteration   1: 5.597 ops/ms
Iteration   1: 12.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.651 ops/ms


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
# Warmup Iteration   1: 5.689 ops/ms
Iteration   1: 8.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.836 ops/ms


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.070 ms/op
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
# Warmup Iteration   1: 3.531 ±(99.9%) 0.060 ms/op
Iteration   1: 1.964 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.964 ms/op


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
# Warmup Iteration   1: 3.367 ±(99.9%) 0.061 ms/op
Iteration   1: 1.868 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.868 ms/op


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
# Warmup Iteration   1: 4.310 ±(99.9%) 0.089 ms/op
Iteration   1: 3.261 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.261 ms/op


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.090 ms/op
Iteration   1: 2.379 ±(99.9%) 0.059 ms/op
                 createUser·p0.00:   0.424 ms/op
                 createUser·p0.50:   2.167 ms/op
                 createUser·p0.90:   2.687 ms/op
                 createUser·p0.95:   2.896 ms/op
                 createUser·p0.99:   10.001 ms/op
                 createUser·p0.999:  32.801 ms/op
                 createUser·p0.9999: 34.207 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13457
  mean =      2.379 ±(99.9%) 0.059 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10920 
    [ 2.500,  5.000) = 2322 
    [ 5.000,  7.500) = 25 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.167 ms/op
     p(90.0000) =      2.687 ms/op
     p(95.0000) =      2.896 ms/op
     p(99.0000) =     10.001 ms/op
     p(99.9000) =     32.801 ms/op
     p(99.9900) =     34.207 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 2.983 ±(99.9%) 0.072 ms/op
Iteration   1: 2.114 ±(99.9%) 0.145 ms/op
                 existUser·p0.00:   0.276 ms/op
                 existUser·p0.50:   1.718 ms/op
                 existUser·p0.90:   2.310 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   4.648 ms/op
                 existUser·p0.999:  118.468 ms/op
                 existUser·p0.9999: 133.562 ms/op
                 existUser·p1.00:   133.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15161
  mean =      2.114 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15103 
    [ 12.500,  25.000) = 17 
    [ 25.000,  37.500) = 6 
    [ 37.500,  50.000) = 3 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 1 
    [ 87.500, 100.000) = 3 
    [100.000, 112.500) = 9 
    [112.500, 125.000) = 9 
    [125.000, 137.500) = 10 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.276 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.310 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.648 ms/op
     p(99.9000) =    118.468 ms/op
     p(99.9900) =    133.562 ms/op
     p(99.9990) =    133.562 ms/op
     p(99.9999) =    133.562 ms/op
    p(100.0000) =    133.562 ms/op


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
# Warmup Iteration   1: 3.170 ±(99.9%) 0.081 ms/op
Iteration   1: 2.275 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.828 ms/op
                 getUser·p0.50:   2.236 ms/op
                 getUser·p0.90:   2.753 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   3.540 ms/op
                 getUser·p0.999:  11.514 ms/op
                 getUser·p0.9999: 11.806 ms/op
                 getUser·p1.00:   11.813 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14265
  mean =      2.275 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 10442 
    [ 2.500,  3.750) = 3548 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.828 ms/op
     p(50.0000) =      2.236 ms/op
     p(90.0000) =      2.753 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.540 ms/op
     p(99.9000) =     11.514 ms/op
     p(99.9900) =     11.806 ms/op
     p(99.9990) =     11.813 ms/op
     p(99.9999) =     11.813 ms/op
    p(100.0000) =     11.813 ms/op


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.131 ms/op
Iteration   1: 3.794 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.414 ms/op
                 listUser·p0.999:  8.471 ms/op
                 listUser·p0.9999: 8.765 ms/op
                 listUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8432
  mean =      3.794 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 23 
    [1.500, 2.000) = 95 
    [2.000, 2.500) = 587 
    [2.500, 3.000) = 531 
    [3.000, 3.500) = 1240 
    [3.500, 4.000) = 2823 
    [4.000, 4.500) = 1938 
    [4.500, 5.000) = 807 
    [5.000, 5.500) = 147 
    [5.500, 6.000) = 76 
    [6.000, 6.500) = 101 
    [6.500, 7.000) = 24 
    [7.000, 7.500) = 2 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =      8.471 ms/op
     p(99.9900) =      8.765 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           6.305          ops/ms
ClientSimple.existUser                       thrpt          13.696          ops/ms
ClientSimple.getUser                         thrpt          12.651          ops/ms
ClientSimple.listUser                        thrpt           8.836          ops/ms
ClientSimple.createUser                       avgt           2.077           ms/op
ClientSimple.existUser                        avgt           1.964           ms/op
ClientSimple.getUser                          avgt           1.868           ms/op
ClientSimple.listUser                         avgt           3.261           ms/op
ClientSimple.createUser                     sample  13457    2.379 ± 0.059   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.424           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.167           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.687           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.896           ms/op
ClientSimple.createUser:createUser·p0.99    sample          10.001           ms/op
ClientSimple.createUser:createUser·p0.999   sample          32.801           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          34.207           ms/op
ClientSimple.createUser:createUser·p1.00    sample          34.275           ms/op
ClientSimple.existUser                      sample  15161    2.114 ± 0.145   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.276           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.718           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.310           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.648           ms/op
ClientSimple.existUser:existUser·p0.999     sample         118.468           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         133.562           ms/op
ClientSimple.existUser:existUser·p1.00      sample         133.562           ms/op
ClientSimple.getUser                        sample  14265    2.275 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.828           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.236           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.753           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.540           ms/op
ClientSimple.getUser:getUser·p0.999         sample          11.514           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          11.806           ms/op
ClientSimple.getUser:getUser·p1.00          sample          11.813           ms/op
ClientSimple.listUser                       sample   8432    3.794 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.014           ms/op
ClientSimple.listUser:listUser·p0.50        sample           3.809           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.702           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.964           ms/op
ClientSimple.listUser:listUser·p0.99        sample           6.414           ms/op
ClientSimple.listUser:listUser·p0.999       sample           8.471           ms/op
ClientSimple.listUser:listUser·p0.9999      sample           8.765           ms/op
ClientSimple.listUser:listUser·p1.00        sample           8.765           ms/op

Benchmark result is saved to 1716833514077.json
