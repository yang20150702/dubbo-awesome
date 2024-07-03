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
# Warmup Iteration   1: 1.590 ops/ms
Iteration   1: 6.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.976 ops/ms


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
# Warmup Iteration   1: 6.530 ops/ms
Iteration   1: 12.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.483 ops/ms


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
# Warmup Iteration   1: 5.022 ops/ms
Iteration   1: 12.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.849 ops/ms


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
# Warmup Iteration   1: 4.802 ops/ms
Iteration   1: 8.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.636 ops/ms


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.075 ms/op
Iteration   1: 2.629 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.629 ms/op


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
# Warmup Iteration   1: 3.369 ±(99.9%) 0.056 ms/op
Iteration   1: 1.861 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 3.234 ±(99.9%) 0.053 ms/op
Iteration   1: 1.824 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.824 ms/op


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
# Warmup Iteration   1: 4.846 ±(99.9%) 0.089 ms/op
Iteration   1: 3.504 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.504 ms/op


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
# Warmup Iteration   1: 3.771 ±(99.9%) 0.097 ms/op
Iteration   1: 2.432 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   2.013 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   11.993 ms/op
                 createUser·p0.999:  19.235 ms/op
                 createUser·p0.9999: 19.783 ms/op
                 createUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13142
  mean =      2.432 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 9573 
    [ 2.500,  3.750) = 2859 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.555 ms/op
     p(99.0000) =     11.993 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     19.783 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 2.893 ±(99.9%) 0.063 ms/op
Iteration   1: 2.062 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.993 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.785 ms/op
                 existUser·p0.99:   4.684 ms/op
                 existUser·p0.999:  18.070 ms/op
                 existUser·p0.9999: 19.050 ms/op
                 existUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15516
  mean =      2.062 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 656 
    [ 1.250,  2.500) = 12938 
    [ 2.500,  3.750) = 1713 
    [ 3.750,  5.000) = 80 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.785 ms/op
     p(99.0000) =      4.684 ms/op
     p(99.9000) =     18.070 ms/op
     p(99.9900) =     19.050 ms/op
     p(99.9990) =     19.104 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.076 ms/op
Iteration   1: 1.985 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   1.921 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.728 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  11.664 ms/op
                 getUser·p0.9999: 11.754 ms/op
                 getUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16103
  mean =      1.985 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 353 
    [ 1.250,  2.500) = 14040 
    [ 2.500,  3.750) = 1554 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =     11.664 ms/op
     p(99.9900) =     11.754 ms/op
     p(99.9990) =     11.764 ms/op
     p(99.9999) =     11.764 ms/op
    p(100.0000) =     11.764 ms/op


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.126 ms/op
Iteration   1: 3.244 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.262 ms/op
                 listUser·p0.99:   5.222 ms/op
                 listUser·p0.999:  16.534 ms/op
                 listUser·p0.9999: 17.400 ms/op
                 listUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9853
  mean =      3.244 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 341 
    [ 2.500,  3.750) = 7569 
    [ 3.750,  5.000) = 1767 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.262 ms/op
     p(99.0000) =      5.222 ms/op
     p(99.9000) =     16.534 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.976          ops/ms
ClientSimple.existUser                       thrpt         12.483          ops/ms
ClientSimple.getUser                         thrpt         12.849          ops/ms
ClientSimple.listUser                        thrpt          8.636          ops/ms
ClientSimple.createUser                       avgt          2.629           ms/op
ClientSimple.existUser                        avgt          1.861           ms/op
ClientSimple.getUser                          avgt          1.824           ms/op
ClientSimple.listUser                         avgt          3.504           ms/op
ClientSimple.createUser                     sample  13142   2.432 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.735           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.013           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.047           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.555           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.993           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.235           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.783           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.825           ms/op
ClientSimple.existUser                      sample  15516   2.062 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.523           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.993           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.684           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.070           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.050           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.104           ms/op
ClientSimple.getUser                        sample  16103   1.985 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.770           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.921           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.728           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.731           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.664           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.754           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.764           ms/op
ClientSimple.listUser                       sample   9853   3.244 ± 0.032   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.255           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.262           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.222           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.534           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.400           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.400           ms/op

Benchmark result is saved to 1719967289474.json
