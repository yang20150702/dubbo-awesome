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
# Warmup Iteration   1: 1.420 ops/ms
Iteration   1: 7.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.070 ops/ms


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
# Warmup Iteration   1: 5.627 ops/ms
Iteration   1: 12.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.390 ops/ms


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
# Warmup Iteration   1: 6.191 ops/ms
Iteration   1: 14.332 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.332 ops/ms


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
# Warmup Iteration   1: 5.373 ops/ms
Iteration   1: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.936 ops/ms


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
# Warmup Iteration   1: 4.323 ±(99.9%) 0.075 ms/op
Iteration   1: 2.394 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.394 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.059 ms/op
Iteration   1: 1.868 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.490 ±(99.9%) 0.073 ms/op
Iteration   1: 1.865 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.865 ms/op


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
# Warmup Iteration   1: 4.469 ±(99.9%) 0.090 ms/op
Iteration   1: 3.304 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.304 ms/op


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
# Warmup Iteration   1: 3.738 ±(99.9%) 0.144 ms/op
Iteration   1: 2.257 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.056 ms/op
                 createUser·p0.90:   2.777 ms/op
                 createUser·p0.95:   3.019 ms/op
                 createUser·p0.99:   9.385 ms/op
                 createUser·p0.999:  20.124 ms/op
                 createUser·p0.9999: 22.940 ms/op
                 createUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14854
  mean =      2.257 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12217 
    [ 2.500,  5.000) = 2404 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.056 ms/op
     p(90.0000) =      2.777 ms/op
     p(95.0000) =      3.019 ms/op
     p(99.0000) =      9.385 ms/op
     p(99.9000) =     20.124 ms/op
     p(99.9900) =     22.940 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 3.236 ±(99.9%) 0.092 ms/op
Iteration   1: 1.984 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   1.827 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   5.873 ms/op
                 existUser·p0.999:  23.953 ms/op
                 existUser·p0.9999: 24.440 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16106
  mean =      1.984 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15001 
    [ 2.500,  5.000) = 848 
    [ 5.000,  7.500) = 156 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      1.827 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      5.873 ms/op
     p(99.9000) =     23.953 ms/op
     p(99.9900) =     24.440 ms/op
     p(99.9990) =     24.740 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 3.281 ±(99.9%) 0.084 ms/op
Iteration   1: 2.018 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.579 ms/op
                 getUser·p0.50:   1.769 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   3.180 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  21.322 ms/op
                 getUser·p0.9999: 84.140 ms/op
                 getUser·p1.00:   87.818 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15612
  mean =      2.018 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15390 
    [ 5.000, 10.000) = 146 
    [10.000, 15.000) = 44 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 9 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 1 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 4 
    [75.000, 80.000) = 1 
    [80.000, 85.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      3.180 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     21.322 ms/op
     p(99.9900) =     84.140 ms/op
     p(99.9990) =     87.818 ms/op
     p(99.9999) =     87.818 ms/op
    p(100.0000) =     87.818 ms/op


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
# Warmup Iteration   1: 4.752 ±(99.9%) 0.157 ms/op
Iteration   1: 3.858 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   0.697 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   7.092 ms/op
                 listUser·p0.999:  14.349 ms/op
                 listUser·p0.9999: 14.942 ms/op
                 listUser·p1.00:   14.942 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8324
  mean =      3.858 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 440 
    [ 2.500,  3.750) = 3362 
    [ 3.750,  5.000) = 3916 
    [ 5.000,  6.250) = 408 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.697 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.092 ms/op
     p(99.9000) =     14.349 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.070          ops/ms
ClientSimple.existUser                       thrpt         12.390          ops/ms
ClientSimple.getUser                         thrpt         14.332          ops/ms
ClientSimple.listUser                        thrpt          9.936          ops/ms
ClientSimple.createUser                       avgt          2.394           ms/op
ClientSimple.existUser                        avgt          1.868           ms/op
ClientSimple.getUser                          avgt          1.865           ms/op
ClientSimple.listUser                         avgt          3.304           ms/op
ClientSimple.createUser                     sample  14854   2.257 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.588           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.056           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.777           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.019           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.385           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.124           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.940           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.003           ms/op
ClientSimple.existUser                      sample  16106   1.984 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.482           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.827           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.675           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.873           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.953           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.440           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.740           ms/op
ClientSimple.getUser                        sample  15612   2.018 ± 0.056   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.579           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.769           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.180           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.538           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.322           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         84.140           ms/op
ClientSimple.getUser:getUser·p1.00          sample         87.818           ms/op
ClientSimple.listUser                       sample   8324   3.858 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.697           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.838           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.809           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.259           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.092           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.349           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.942           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.942           ms/op

Benchmark result is saved to 1718000049852.json
