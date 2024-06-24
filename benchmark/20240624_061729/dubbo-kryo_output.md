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
# Warmup Iteration   1: 1.980 ops/ms
Iteration   1: 7.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.114 ops/ms


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
# Warmup Iteration   1: 5.677 ops/ms
Iteration   1: 12.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.128 ops/ms


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
# Warmup Iteration   1: 5.034 ops/ms
Iteration   1: 11.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.812 ops/ms


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
# Warmup Iteration   1: 5.864 ops/ms
Iteration   1: 8.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.672 ops/ms


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.086 ms/op
Iteration   1: 2.449 ±(99.9%) 0.022 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.033 ±(99.9%) 0.045 ms/op
Iteration   1: 1.957 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.957 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.071 ms/op
Iteration   1: 1.868 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ±(99.9%) 0.093 ms/op
Iteration   1: 3.423 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.423 ms/op


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
# Warmup Iteration   1: 3.451 ±(99.9%) 0.080 ms/op
Iteration   1: 2.357 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   2.224 ms/op
                 createUser·p0.90:   2.933 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   4.125 ms/op
                 createUser·p0.999:  14.680 ms/op
                 createUser·p0.9999: 16.070 ms/op
                 createUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13562
  mean =      2.357 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 9961 
    [ 2.500,  3.750) = 3287 
    [ 3.750,  5.000) = 131 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.224 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =     14.680 ms/op
     p(99.9900) =     16.070 ms/op
     p(99.9990) =     16.105 ms/op
     p(99.9999) =     16.105 ms/op
    p(100.0000) =     16.105 ms/op


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
# Warmup Iteration   1: 3.004 ±(99.9%) 0.065 ms/op
Iteration   1: 1.815 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   1.686 ms/op
                 existUser·p0.90:   2.114 ms/op
                 existUser·p0.95:   2.425 ms/op
                 existUser·p0.99:   3.562 ms/op
                 existUser·p0.999:  16.581 ms/op
                 existUser·p0.9999: 16.840 ms/op
                 existUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17637
  mean =      1.815 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 16894 
    [ 2.500,  3.750) = 539 
    [ 3.750,  5.000) = 93 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      1.686 ms/op
     p(90.0000) =      2.114 ms/op
     p(95.0000) =      2.425 ms/op
     p(99.0000) =      3.562 ms/op
     p(99.9000) =     16.581 ms/op
     p(99.9900) =     16.840 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 3.027 ±(99.9%) 0.090 ms/op
Iteration   1: 1.933 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.466 ms/op
                 getUser·p0.50:   1.845 ms/op
                 getUser·p0.90:   2.376 ms/op
                 getUser·p0.95:   2.576 ms/op
                 getUser·p0.99:   4.189 ms/op
                 getUser·p0.999:  11.502 ms/op
                 getUser·p0.9999: 11.975 ms/op
                 getUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16563
  mean =      1.933 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 362 
    [ 1.250,  2.500) = 15158 
    [ 2.500,  3.750) = 847 
    [ 3.750,  5.000) = 134 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      1.845 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.189 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     11.975 ms/op
     p(99.9990) =     12.222 ms/op
     p(99.9999) =     12.222 ms/op
    p(100.0000) =     12.222 ms/op


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
# Warmup Iteration   1: 4.611 ±(99.9%) 0.144 ms/op
Iteration   1: 3.170 ±(99.9%) 0.052 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.085 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 27.197 ms/op
                 listUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10076
  mean =      3.170 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 8108 
    [ 5.000,  7.500) = 90 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.085 ms/op
     p(99.9000) =     26.804 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.114          ops/ms
ClientSimple.existUser                       thrpt         12.128          ops/ms
ClientSimple.getUser                         thrpt         11.812          ops/ms
ClientSimple.listUser                        thrpt          8.672          ops/ms
ClientSimple.createUser                       avgt          2.449           ms/op
ClientSimple.existUser                        avgt          1.957           ms/op
ClientSimple.getUser                          avgt          1.868           ms/op
ClientSimple.listUser                         avgt          3.423           ms/op
ClientSimple.createUser                     sample  13562   2.357 ± 0.027   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.863           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.224           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.933           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.187           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.125           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.680           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.070           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.105           ms/op
ClientSimple.existUser                      sample  17637   1.815 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.627           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.686           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.114           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.425           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.562           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.581           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.840           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.203           ms/op
ClientSimple.getUser                        sample  16563   1.933 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.466           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.845           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.376           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.576           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.189           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.502           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.975           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.222           ms/op
ClientSimple.listUser                       sample  10076   3.170 ± 0.052   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.007           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.998           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.920           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.085           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.804           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.197           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.197           ms/op

Benchmark result is saved to 1719209615872.json
