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
# Warmup Iteration   1: 1.944 ops/ms
Iteration   1: 7.143 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.143 ops/ms


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
# Warmup Iteration   1: 6.630 ops/ms
Iteration   1: 12.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.606 ops/ms


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
# Warmup Iteration   1: 5.426 ops/ms
Iteration   1: 12.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.086 ops/ms


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
# Warmup Iteration   1: 5.214 ops/ms
Iteration   1: 8.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.754 ops/ms


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
# Warmup Iteration   1: 3.605 ±(99.9%) 0.080 ms/op
Iteration   1: 2.061 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.061 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.056 ms/op
Iteration   1: 2.272 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.272 ms/op


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
# Warmup Iteration   1: 3.277 ±(99.9%) 0.054 ms/op
Iteration   1: 1.972 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.972 ms/op


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
# Warmup Iteration   1: 4.290 ±(99.9%) 0.081 ms/op
Iteration   1: 3.356 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.356 ms/op


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.143 ms/op
Iteration   1: 2.216 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.447 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.982 ms/op
                 createUser·p0.99:   5.602 ms/op
                 createUser·p0.999:  14.864 ms/op
                 createUser·p0.9999: 15.468 ms/op
                 createUser·p1.00:   15.483 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14421
  mean =      2.216 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 11751 
    [ 2.500,  3.750) = 2242 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      5.602 ms/op
     p(99.9000) =     14.864 ms/op
     p(99.9900) =     15.468 ms/op
     p(99.9990) =     15.483 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 2.973 ±(99.9%) 0.066 ms/op
Iteration   1: 1.800 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   1.638 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.736 ms/op
                 existUser·p0.99:   3.826 ms/op
                 existUser·p0.999:  20.873 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17768
  mean =      1.800 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16231 
    [ 2.500,  5.000) = 1468 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      1.638 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.736 ms/op
     p(99.0000) =      3.826 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 3.326 ±(99.9%) 0.078 ms/op
Iteration   1: 2.046 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.920 ms/op
                 getUser·p0.99:   3.678 ms/op
                 getUser·p0.999:  13.405 ms/op
                 getUser·p0.9999: 13.728 ms/op
                 getUser·p1.00:   13.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15609
  mean =      2.046 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 13356 
    [ 2.500,  3.750) = 2049 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.920 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =     13.405 ms/op
     p(99.9900) =     13.728 ms/op
     p(99.9990) =     13.746 ms/op
     p(99.9999) =     13.746 ms/op
    p(100.0000) =     13.746 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.147 ms/op
Iteration   1: 3.113 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.795 ms/op
                 listUser·p0.999:  6.965 ms/op
                 listUser·p0.9999: 7.286 ms/op
                 listUser·p1.00:   7.291 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10279
  mean =      3.113 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 5 
    [1.500, 2.000) = 15 
    [2.000, 2.500) = 187 
    [2.500, 3.000) = 6272 
    [3.000, 3.500) = 1784 
    [3.500, 4.000) = 1114 
    [4.000, 4.500) = 563 
    [4.500, 5.000) = 151 
    [5.000, 5.500) = 60 
    [5.500, 6.000) = 45 
    [6.000, 6.500) = 29 
    [6.500, 7.000) = 44 
    [7.000, 7.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      5.795 ms/op
     p(99.9000) =      6.965 ms/op
     p(99.9900) =      7.286 ms/op
     p(99.9990) =      7.291 ms/op
     p(99.9999) =      7.291 ms/op
    p(100.0000) =      7.291 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.143          ops/ms
ClientSimple.existUser                       thrpt         12.606          ops/ms
ClientSimple.getUser                         thrpt         12.086          ops/ms
ClientSimple.listUser                        thrpt          8.754          ops/ms
ClientSimple.createUser                       avgt          2.061           ms/op
ClientSimple.existUser                        avgt          2.272           ms/op
ClientSimple.getUser                          avgt          1.972           ms/op
ClientSimple.listUser                         avgt          3.356           ms/op
ClientSimple.createUser                     sample  14421   2.216 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.447           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.982           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.602           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.864           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.468           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.483           ms/op
ClientSimple.existUser                      sample  17768   1.800 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.489           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.638           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.736           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.826           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.873           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.299           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.299           ms/op
ClientSimple.getUser                        sample  15609   2.046 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.815           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.920           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.678           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.405           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.728           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.746           ms/op
ClientSimple.listUser                       sample  10279   3.113 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.171           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.900           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.795           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.965           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.286           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.291           ms/op

Benchmark result is saved to 1718259183644.json
