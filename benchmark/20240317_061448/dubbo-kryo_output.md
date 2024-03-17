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
# Warmup Iteration   1: 2.078 ops/ms
Iteration   1: 7.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.620 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ops/ms
Iteration   1: 13.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.363 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.237 ops/ms
Iteration   1: 11.314 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.314 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.537 ops/ms
Iteration   1: 9.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.382 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.920 ±(99.9%) 0.068 ms/op
Iteration   1: 2.030 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.030 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.840 ±(99.9%) 0.049 ms/op
Iteration   1: 1.909 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.909 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.355 ±(99.9%) 0.053 ms/op
Iteration   1: 1.976 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.976 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.283 ±(99.9%) 0.086 ms/op
Iteration   1: 3.342 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.342 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.595 ±(99.9%) 0.089 ms/op
Iteration   1: 2.331 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.207 ms/op
                 createUser·p0.50:   2.261 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   3.076 ms/op
                 createUser·p0.99:   7.103 ms/op
                 createUser·p0.999:  22.848 ms/op
                 createUser·p0.9999: 23.476 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13720
  mean =      2.331 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10331 
    [ 2.500,  5.000) = 3153 
    [ 5.000,  7.500) = 104 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.207 ms/op
     p(50.0000) =      2.261 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      7.103 ms/op
     p(99.9000) =     22.848 ms/op
     p(99.9900) =     23.476 ms/op
     p(99.9990) =     23.757 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ±(99.9%) 0.075 ms/op
Iteration   1: 2.048 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.523 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.290 ms/op
                 existUser·p0.999:  14.522 ms/op
                 existUser·p0.9999: 15.100 ms/op
                 existUser·p1.00:   15.221 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15660
  mean =      2.048 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 793 
    [ 1.250,  2.500) = 13101 
    [ 2.500,  3.750) = 1634 
    [ 3.750,  5.000) = 11 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.290 ms/op
     p(99.9000) =     14.522 ms/op
     p(99.9900) =     15.100 ms/op
     p(99.9990) =     15.221 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 2.926 ±(99.9%) 0.074 ms/op
Iteration   1: 2.084 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   1.960 ms/op
                 getUser·p0.90:   2.731 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   3.926 ms/op
                 getUser·p0.999:  13.599 ms/op
                 getUser·p0.9999: 14.405 ms/op
                 getUser·p1.00:   14.991 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15341
  mean =      2.084 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 322 
    [ 1.250,  2.500) = 12471 
    [ 2.500,  3.750) = 2346 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.731 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      3.926 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     14.405 ms/op
     p(99.9990) =     14.991 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.137 ms/op
Iteration   1: 3.302 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.015 ms/op
                 listUser·p0.50:   3.121 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  15.127 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9695
  mean =      3.302 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 1513 
    [ 2.500,  3.750) = 5361 
    [ 3.750,  5.000) = 2583 
    [ 5.000,  6.250) = 160 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     15.127 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.620          ops/ms
ClientSimple.existUser                       thrpt         13.363          ops/ms
ClientSimple.getUser                         thrpt         11.314          ops/ms
ClientSimple.listUser                        thrpt          9.382          ops/ms
ClientSimple.createUser                       avgt          2.030           ms/op
ClientSimple.existUser                        avgt          1.909           ms/op
ClientSimple.getUser                          avgt          1.976           ms/op
ClientSimple.listUser                         avgt          3.342           ms/op
ClientSimple.createUser                     sample  13720   2.331 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.207           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.261           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.076           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.103           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.848           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.476           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.757           ms/op
ClientSimple.existUser                      sample  15660   2.048 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.612           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.290           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.522           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.100           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.221           ms/op
ClientSimple.getUser                        sample  15341   2.084 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.568           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.960           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.731           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.926           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.599           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.405           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.991           ms/op
ClientSimple.listUser                       sample   9695   3.302 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.015           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.121           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.743           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.127           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.990           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.990           ms/op

Benchmark result is saved to 1710655817582.json
