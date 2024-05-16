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
# Warmup Iteration   1: 1.382 ops/ms
Iteration   1: 6.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.236 ops/ms


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
# Warmup Iteration   1: 5.655 ops/ms
Iteration   1: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.734 ops/ms


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
# Warmup Iteration   1: 5.073 ops/ms
Iteration   1: 11.999 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.999 ops/ms


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
# Warmup Iteration   1: 4.564 ops/ms
Iteration   1: 8.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.641 ops/ms


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.069 ms/op
Iteration   1: 2.206 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.206 ms/op


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
# Warmup Iteration   1: 3.225 ±(99.9%) 0.049 ms/op
Iteration   1: 1.704 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.704 ms/op


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
# Warmup Iteration   1: 2.860 ±(99.9%) 0.046 ms/op
Iteration   1: 1.996 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.996 ms/op


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
# Warmup Iteration   1: 4.719 ±(99.9%) 0.088 ms/op
Iteration   1: 3.699 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.699 ms/op


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
# Warmup Iteration   1: 3.674 ±(99.9%) 0.083 ms/op
Iteration   1: 2.005 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.482 ms/op
                 createUser·p0.50:   1.749 ms/op
                 createUser·p0.90:   2.335 ms/op
                 createUser·p0.95:   2.540 ms/op
                 createUser·p0.99:   12.858 ms/op
                 createUser·p0.999:  26.413 ms/op
                 createUser·p0.9999: 28.712 ms/op
                 createUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15939
  mean =      2.005 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15017 
    [ 2.500,  5.000) = 730 
    [ 5.000,  7.500) = 32 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.335 ms/op
     p(95.0000) =      2.540 ms/op
     p(99.0000) =     12.858 ms/op
     p(99.9000) =     26.413 ms/op
     p(99.9900) =     28.712 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.770 ms/op
    p(100.0000) =     28.770 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.192 ms/op
Iteration   1: 1.731 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.509 ms/op
                 existUser·p0.50:   1.509 ms/op
                 existUser·p0.90:   2.429 ms/op
                 existUser·p0.95:   2.634 ms/op
                 existUser·p0.99:   3.562 ms/op
                 existUser·p0.999:  11.321 ms/op
                 existUser·p0.9999: 14.355 ms/op
                 existUser·p1.00:   14.369 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18424
  mean =      1.731 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1690 
    [ 1.250,  2.500) = 15267 
    [ 2.500,  3.750) = 1304 
    [ 3.750,  5.000) = 33 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      1.509 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.634 ms/op
     p(99.0000) =      3.562 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     14.355 ms/op
     p(99.9990) =     14.369 ms/op
     p(99.9999) =     14.369 ms/op
    p(100.0000) =     14.369 ms/op


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
# Warmup Iteration   1: 3.881 ±(99.9%) 0.117 ms/op
Iteration   1: 1.962 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   1.765 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  19.923 ms/op
                 getUser·p0.9999: 20.359 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16408
  mean =      1.962 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14499 
    [ 2.500,  5.000) = 1786 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =     19.923 ms/op
     p(99.9900) =     20.359 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.141 ms/op
Iteration   1: 3.761 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.347 ms/op
                 listUser·p0.99:   8.555 ms/op
                 listUser·p0.999:  20.431 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8485
  mean =      3.761 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 169 
    [ 2.500,  5.000) = 7613 
    [ 5.000,  7.500) = 603 
    [ 7.500, 10.000) = 23 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.810 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.347 ms/op
     p(99.0000) =      8.555 ms/op
     p(99.9000) =     20.431 ms/op
     p(99.9900) =     20.644 ms/op
     p(99.9990) =     20.644 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.236          ops/ms
ClientSimple.existUser                       thrpt         10.734          ops/ms
ClientSimple.getUser                         thrpt         11.999          ops/ms
ClientSimple.listUser                        thrpt          8.641          ops/ms
ClientSimple.createUser                       avgt          2.206           ms/op
ClientSimple.existUser                        avgt          1.704           ms/op
ClientSimple.getUser                          avgt          1.996           ms/op
ClientSimple.listUser                         avgt          3.699           ms/op
ClientSimple.createUser                     sample  15939   2.005 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.482           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.749           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.540           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.858           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.413           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.712           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.770           ms/op
ClientSimple.existUser                      sample  18424   1.731 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.509           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.509           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.429           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.634           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.562           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.321           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.355           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.369           ms/op
ClientSimple.getUser                        sample  16408   1.962 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.655           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.765           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.882           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.923           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.359           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.611           ms/op
ClientSimple.listUser                       sample   8485   3.761 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.810           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.792           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.347           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.555           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.431           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.644           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.644           ms/op

Benchmark result is saved to 1715819930222.json
