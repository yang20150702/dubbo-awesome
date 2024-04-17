# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.632 ops/ms
Iteration   1: 5.633 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.633 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.458 ops/ms
Iteration   1: 11.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.836 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.112 ops/ms
Iteration   1: 11.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.163 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.927 ops/ms
Iteration   1: 8.012 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.012 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.078 ms/op
Iteration   1: 2.396 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.095 ±(99.9%) 0.057 ms/op
Iteration   1: 2.145 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ±(99.9%) 0.061 ms/op
Iteration   1: 2.073 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.713 ±(99.9%) 0.118 ms/op
Iteration   1: 3.583 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.583 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.119 ms/op
Iteration   1: 2.280 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.477 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   11.377 ms/op
                 createUser·p0.999:  20.644 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14058
  mean =      2.280 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11398 
    [ 2.500,  5.000) = 2432 
    [ 5.000,  7.500) = 64 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =     11.377 ms/op
     p(99.9000) =     20.644 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.087 ±(99.9%) 0.082 ms/op
Iteration   1: 2.423 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.314 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.277 ms/op
                 existUser·p0.99:   5.920 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 17.094 ms/op
                 existUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 13210
  mean =      2.423 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 162 
    [ 1.250,  2.500) = 8342 
    [ 2.500,  3.750) = 4397 
    [ 3.750,  5.000) = 99 
    [ 5.000,  6.250) = 129 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.314 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      5.920 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     17.094 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.101 ms/op
Iteration   1: 2.038 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   1.839 ms/op
                 getUser·p0.90:   2.482 ms/op
                 getUser·p0.95:   2.703 ms/op
                 getUser·p0.99:   5.579 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15714
  mean =      2.038 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14246 
    [ 2.500,  5.000) = 1271 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.137 ms/op
Iteration   1: 3.494 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.453 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  23.193 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9198
  mean =      3.494 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 859 
    [ 2.500,  5.000) = 8036 
    [ 5.000,  7.500) = 197 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.994 ms/op
     p(50.0000) =      3.453 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     23.193 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.633          ops/ms
ClientSimple.existUser                       thrpt         11.836          ops/ms
ClientSimple.getUser                         thrpt         11.163          ops/ms
ClientSimple.listUser                        thrpt          8.012          ops/ms
ClientSimple.createUser                       avgt          2.396           ms/op
ClientSimple.existUser                        avgt          2.145           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          3.583           ms/op
ClientSimple.createUser                     sample  14058   2.280 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.477           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.377           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.644           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.692           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.692           ms/op
ClientSimple.existUser                      sample  13210   2.423 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.665           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.314           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.994           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.920           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.094           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.105           ms/op
ClientSimple.getUser                        sample  15714   2.038 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.674           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.839           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.482           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.579           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.546           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.151           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.069           ms/op
ClientSimple.listUser                       sample   9198   3.494 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.994           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.453           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.864           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.193           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.412           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.412           ms/op

Benchmark result is saved to 1713334442238.json
