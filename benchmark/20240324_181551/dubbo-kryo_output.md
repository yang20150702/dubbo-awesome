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
# Warmup Iteration   1: 1.513 ops/ms
Iteration   1: 6.434 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.434 ops/ms


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
# Warmup Iteration   1: 6.737 ops/ms
Iteration   1: 12.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.421 ops/ms


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
# Warmup Iteration   1: 5.221 ops/ms
Iteration   1: 14.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.182 ops/ms


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
# Warmup Iteration   1: 5.481 ops/ms
Iteration   1: 8.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.769 ops/ms


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.076 ms/op
Iteration   1: 2.280 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.280 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.057 ms/op
Iteration   1: 2.017 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.017 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.067 ms/op
Iteration   1: 1.928 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.928 ms/op


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
# Warmup Iteration   1: 5.363 ±(99.9%) 0.173 ms/op
Iteration   1: 3.636 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.636 ms/op


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
# Warmup Iteration   1: 3.370 ±(99.9%) 0.085 ms/op
Iteration   1: 2.241 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.101 ms/op
                 createUser·p0.90:   2.654 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   5.266 ms/op
                 createUser·p0.999:  20.438 ms/op
                 createUser·p0.9999: 21.262 ms/op
                 createUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14255
  mean =      2.241 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11955 
    [ 2.500,  5.000) = 2149 
    [ 5.000,  7.500) = 86 
    [ 7.500, 10.000) = 33 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.654 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      5.266 ms/op
     p(99.9000) =     20.438 ms/op
     p(99.9900) =     21.262 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 3.284 ±(99.9%) 0.077 ms/op
Iteration   1: 1.945 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.749 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   4.142 ms/op
                 existUser·p0.999:  25.052 ms/op
                 existUser·p0.9999: 25.757 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16484
  mean =      1.945 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15409 
    [ 2.500,  5.000) = 964 
    [ 5.000,  7.500) = 46 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.749 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      4.142 ms/op
     p(99.9000) =     25.052 ms/op
     p(99.9900) =     25.757 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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
# Warmup Iteration   1: 3.162 ±(99.9%) 0.076 ms/op
Iteration   1: 2.114 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   1.939 ms/op
                 getUser·p0.90:   2.630 ms/op
                 getUser·p0.95:   2.859 ms/op
                 getUser·p0.99:   3.408 ms/op
                 getUser·p0.999:  19.694 ms/op
                 getUser·p0.9999: 19.857 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15123
  mean =      2.114 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 12854 
    [ 2.500,  3.750) = 2124 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      1.939 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.859 ms/op
     p(99.0000) =      3.408 ms/op
     p(99.9000) =     19.694 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.890 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.140 ms/op
Iteration   1: 3.074 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   2.814 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   5.767 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 14.031 ms/op
                 listUser·p1.00:   14.057 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10399
  mean =      3.074 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1328 
    [ 2.500,  3.750) = 7535 
    [ 3.750,  5.000) = 1390 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.767 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     14.031 ms/op
     p(99.9990) =     14.057 ms/op
     p(99.9999) =     14.057 ms/op
    p(100.0000) =     14.057 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.434          ops/ms
ClientSimple.existUser                       thrpt         12.421          ops/ms
ClientSimple.getUser                         thrpt         14.182          ops/ms
ClientSimple.listUser                        thrpt          8.769          ops/ms
ClientSimple.createUser                       avgt          2.280           ms/op
ClientSimple.existUser                        avgt          2.017           ms/op
ClientSimple.getUser                          avgt          1.928           ms/op
ClientSimple.listUser                         avgt          3.636           ms/op
ClientSimple.createUser                     sample  14255   2.241 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.783           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.101           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.654           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.266           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.438           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.262           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.332           ms/op
ClientSimple.existUser                      sample  16484   1.945 ± 0.032   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.749           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.142           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.052           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.757           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.182           ms/op
ClientSimple.getUser                        sample  15123   2.114 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.929           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.939           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.630           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.859           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.408           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.694           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.857           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.890           ms/op
ClientSimple.listUser                       sample  10399   3.074 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.139           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.814           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.767           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.976           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.031           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.057           ms/op

Benchmark result is saved to 1711303883981.json
