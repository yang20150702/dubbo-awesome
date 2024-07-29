# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.607 ops/ms
Iteration   1: 6.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.437 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.820 ops/ms
Iteration   1: 11.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.294 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 7.007 ops/ms
Iteration   1: 14.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.031 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.263 ops/ms
Iteration   1: 8.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.448 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ±(99.9%) 0.070 ms/op
Iteration   1: 2.146 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.146 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.929 ±(99.9%) 0.046 ms/op
Iteration   1: 1.850 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.850 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.178 ±(99.9%) 0.050 ms/op
Iteration   1: 2.270 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.270 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.270 ±(99.9%) 0.088 ms/op
Iteration   1: 3.696 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.115 ms/op
Iteration   1: 2.195 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.056 ms/op
                 createUser·p0.90:   2.642 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  32.866 ms/op
                 createUser·p0.9999: 34.275 ms/op
                 createUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14579
  mean =      2.195 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12097 
    [ 2.500,  5.000) = 2348 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.768 ms/op
     p(99.9000) =     32.866 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.960 ±(99.9%) 0.067 ms/op
Iteration   1: 1.770 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.494 ms/op
                 existUser·p0.99:   2.922 ms/op
                 existUser·p0.999:  13.648 ms/op
                 existUser·p0.9999: 15.240 ms/op
                 existUser·p1.00:   15.319 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18053
  mean =      1.770 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 817 
    [ 1.250,  2.500) = 16359 
    [ 2.500,  3.750) = 804 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.494 ms/op
     p(99.0000) =      2.922 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     15.240 ms/op
     p(99.9990) =     15.319 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.106 ms/op
Iteration   1: 2.139 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   1.872 ms/op
                 getUser·p0.90:   2.908 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.458 ms/op
                 getUser·p0.999:  14.058 ms/op
                 getUser·p0.9999: 16.468 ms/op
                 getUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14993
  mean =      2.139 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 11525 
    [ 2.500,  3.750) = 3068 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 28 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      4.458 ms/op
     p(99.9000) =     14.058 ms/op
     p(99.9900) =     16.468 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.410 ±(99.9%) 0.131 ms/op
Iteration   1: 3.358 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.252 ms/op
                 listUser·p0.90:   4.143 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   7.715 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 14.680 ms/op
                 listUser·p1.00:   14.680 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9524
  mean =      3.358 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1375 
    [ 2.500,  3.750) = 5570 
    [ 3.750,  5.000) = 2263 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      4.143 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.715 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     14.680 ms/op
     p(99.9990) =     14.680 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.437          ops/ms
ClientSimple.existUser                       thrpt         11.294          ops/ms
ClientSimple.getUser                         thrpt         14.031          ops/ms
ClientSimple.listUser                        thrpt          8.448          ops/ms
ClientSimple.createUser                       avgt          2.146           ms/op
ClientSimple.existUser                        avgt          1.850           ms/op
ClientSimple.getUser                          avgt          2.270           ms/op
ClientSimple.listUser                         avgt          3.696           ms/op
ClientSimple.createUser                     sample  14579   2.195 ± 0.044   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.723           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.056           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.642           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.768           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.866           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         34.275           ms/op
ClientSimple.createUser:createUser·p1.00    sample         34.275           ms/op
ClientSimple.existUser                      sample  18053   1.770 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.455           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.620           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.494           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.922           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.648           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.240           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.319           ms/op
ClientSimple.getUser                        sample  14993   2.139 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.589           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.872           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.458           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.058           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.468           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.383           ms/op
ClientSimple.listUser                       sample   9524   3.358 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.252           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.143           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.481           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.715           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.139           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.680           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.680           ms/op

Benchmark result is saved to 1722233649506.json
