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
# Warmup Iteration   1: 1.528 ops/ms
Iteration   1: 6.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.264 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.830 ops/ms
Iteration   1: 12.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.595 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 4.838 ops/ms
Iteration   1: 11.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.232 ops/ms


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
# Warmup Iteration   1: 4.564 ops/ms
Iteration   1: 8.276 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.276 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.089 ms/op
Iteration   1: 2.358 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.358 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.054 ms/op
Iteration   1: 1.911 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.911 ms/op


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
# Warmup Iteration   1: 3.776 ±(99.9%) 0.078 ms/op
Iteration   1: 2.296 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.296 ms/op


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
# Warmup Iteration   1: 5.477 ±(99.9%) 0.198 ms/op
Iteration   1: 3.583 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.583 ms/op


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.119 ms/op
Iteration   1: 2.315 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.492 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.097 ms/op
                 createUser·p0.99:   5.952 ms/op
                 createUser·p0.999:  31.185 ms/op
                 createUser·p0.9999: 31.771 ms/op
                 createUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14147
  mean =      2.315 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11275 
    [ 2.500,  5.000) = 2642 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      5.952 ms/op
     p(99.9000) =     31.185 ms/op
     p(99.9900) =     31.771 ms/op
     p(99.9990) =     31.785 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


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
# Warmup Iteration   1: 3.096 ±(99.9%) 0.070 ms/op
Iteration   1: 2.041 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   1.982 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.798 ms/op
                 existUser·p0.99:   3.438 ms/op
                 existUser·p0.999:  11.758 ms/op
                 existUser·p0.9999: 12.700 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15663
  mean =      2.041 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 293 
    [ 1.250,  2.500) = 13607 
    [ 2.500,  3.750) = 1657 
    [ 3.750,  5.000) = 69 
    [ 5.000,  6.250) = 5 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      3.438 ms/op
     p(99.9000) =     11.758 ms/op
     p(99.9900) =     12.700 ms/op
     p(99.9990) =     12.747 ms/op
     p(99.9999) =     12.747 ms/op
    p(100.0000) =     12.747 ms/op


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
# Warmup Iteration   1: 3.343 ±(99.9%) 0.101 ms/op
Iteration   1: 1.960 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.475 ms/op
                 getUser·p0.50:   1.772 ms/op
                 getUser·p0.90:   2.486 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   4.504 ms/op
                 getUser·p0.999:  29.262 ms/op
                 getUser·p0.9999: 30.916 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16307
  mean =      1.960 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14734 
    [ 2.500,  5.000) = 1483 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.475 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      4.504 ms/op
     p(99.9000) =     29.262 ms/op
     p(99.9900) =     30.916 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.165 ms/op
Iteration   1: 3.840 ±(99.9%) 0.054 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  23.733 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8367
  mean =      3.840 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 450 
    [ 2.500,  5.000) = 7498 
    [ 5.000,  7.500) = 348 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     23.733 ms/op
     p(99.9900) =     24.642 ms/op
     p(99.9990) =     24.642 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.264          ops/ms
ClientSimple.existUser                       thrpt         12.595          ops/ms
ClientSimple.getUser                         thrpt         11.232          ops/ms
ClientSimple.listUser                        thrpt          8.276          ops/ms
ClientSimple.createUser                       avgt          2.358           ms/op
ClientSimple.existUser                        avgt          1.911           ms/op
ClientSimple.getUser                          avgt          2.296           ms/op
ClientSimple.listUser                         avgt          3.583           ms/op
ClientSimple.createUser                     sample  14147   2.315 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.492           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.097           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.952           ms/op
ClientSimple.createUser:createUser·p0.999   sample         31.185           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         31.771           ms/op
ClientSimple.createUser:createUser·p1.00    sample         31.785           ms/op
ClientSimple.existUser                      sample  15663   2.041 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.446           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.798           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.438           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.758           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.700           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.747           ms/op
ClientSimple.getUser                        sample  16307   1.960 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.475           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.772           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.486           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.504           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.262           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.916           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.999           ms/op
ClientSimple.listUser                       sample   8367   3.840 ± 0.054   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.950           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.005           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.283           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.733           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.642           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.642           ms/op

Benchmark result is saved to 1716531188400.json
