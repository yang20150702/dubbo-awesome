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
# Warmup Iteration   1: 1.248 ops/ms
Iteration   1: 5.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.679 ops/ms


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
# Warmup Iteration   1: 5.325 ops/ms
Iteration   1: 11.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.508 ops/ms


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
# Warmup Iteration   1: 4.580 ops/ms
Iteration   1: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.639 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 3.885 ops/ms
Iteration   1: 7.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.257 ops/ms


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
# Warmup Iteration   1: 5.510 ±(99.9%) 0.107 ms/op
Iteration   1: 2.449 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.449 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.635 ±(99.9%) 0.067 ms/op
Iteration   1: 2.282 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.282 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.073 ms/op
Iteration   1: 2.190 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.190 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:36
# Fork: 1 of 1
# Warmup Iteration   1: 5.556 ±(99.9%) 0.116 ms/op
Iteration   1: 3.533 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.533 ms/op


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
# Warmup Iteration   1: 4.037 ±(99.9%) 0.114 ms/op
Iteration   1: 2.086 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   1.896 ms/op
                 createUser·p0.90:   2.417 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   8.274 ms/op
                 createUser·p0.999:  16.728 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15359
  mean =      2.086 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 98 
    [ 1.250,  2.500) = 14031 
    [ 2.500,  3.750) = 839 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      1.896 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.151 ±(99.9%) 0.088 ms/op
Iteration   1: 2.129 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.662 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   4.803 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 12.303 ms/op
                 existUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15172
  mean =      2.129 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 213 
    [ 1.250,  2.500) = 12534 
    [ 2.500,  3.750) = 2101 
    [ 3.750,  5.000) = 244 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.662 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.803 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     12.303 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


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
# Warmup Iteration   1: 3.504 ±(99.9%) 0.101 ms/op
Iteration   1: 2.551 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.707 ms/op
                 getUser·p0.50:   2.376 ms/op
                 getUser·p0.90:   3.178 ms/op
                 getUser·p0.95:   3.469 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  17.153 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12533
  mean =      2.551 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 7390 
    [ 2.500,  3.750) = 4671 
    [ 3.750,  5.000) = 166 
    [ 5.000,  6.250) = 136 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 44 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      2.376 ms/op
     p(90.0000) =      3.178 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =     17.153 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 5.310 ±(99.9%) 0.150 ms/op
Iteration   1: 3.913 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.212 ms/op
                 listUser·p0.999:  8.976 ms/op
                 listUser·p0.9999: 14.008 ms/op
                 listUser·p1.00:   14.008 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8177
  mean =      3.913 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 245 
    [ 2.500,  3.750) = 3788 
    [ 3.750,  5.000) = 3391 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      8.212 ms/op
     p(99.9000) =      8.976 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# Run complete. Total time: 00:01:27

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.679          ops/ms
ClientSimple.existUser                       thrpt         11.508          ops/ms
ClientSimple.getUser                         thrpt          9.639          ops/ms
ClientSimple.listUser                        thrpt          7.257          ops/ms
ClientSimple.createUser                       avgt          2.449           ms/op
ClientSimple.existUser                        avgt          2.282           ms/op
ClientSimple.getUser                          avgt          2.190           ms/op
ClientSimple.listUser                         avgt          3.533           ms/op
ClientSimple.createUser                     sample  15359   2.086 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.684           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.896           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.274           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.728           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.990           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.990           ms/op
ClientSimple.existUser                      sample  15172   2.129 ± 0.020   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.727           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.662           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.803           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.862           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.303           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.354           ms/op
ClientSimple.getUser                        sample  12533   2.551 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.707           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.178           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.469           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.332           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.153           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.400           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.400           ms/op
ClientSimple.listUser                       sample   8177   3.913 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.317           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.764           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.964           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.562           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.212           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.008           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.008           ms/op

Benchmark result is saved to 1717092798736.json
