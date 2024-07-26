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
# Warmup Iteration   1: 1.942 ops/ms
Iteration   1: 6.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.444 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.953 ops/ms
Iteration   1: 12.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.259 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.151 ops/ms
Iteration   1: 11.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.491 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.682 ops/ms
Iteration   1: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.418 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.070 ms/op
Iteration   1: 2.262 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.262 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.394 ±(99.9%) 0.059 ms/op
Iteration   1: 1.781 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.781 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.582 ±(99.9%) 0.065 ms/op
Iteration   1: 2.094 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.094 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.528 ±(99.9%) 0.121 ms/op
Iteration   1: 3.163 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.163 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.649 ±(99.9%) 0.097 ms/op
Iteration   1: 2.370 ±(99.9%) 0.057 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   2.179 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.039 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  37.224 ms/op
                 createUser·p0.9999: 38.116 ms/op
                 createUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13484
  mean =      2.370 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10321 
    [ 2.500,  5.000) = 3012 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     37.224 ms/op
     p(99.9900) =     38.116 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.465 ±(99.9%) 0.116 ms/op
Iteration   1: 1.998 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   1.867 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   4.076 ms/op
                 existUser·p0.999:  11.059 ms/op
                 existUser·p0.9999: 12.144 ms/op
                 existUser·p1.00:   12.173 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16004
  mean =      1.998 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 142 
    [ 1.250,  2.500) = 14722 
    [ 2.500,  3.750) = 956 
    [ 3.750,  5.000) = 110 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      1.867 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =     11.059 ms/op
     p(99.9900) =     12.144 ms/op
     p(99.9990) =     12.173 ms/op
     p(99.9999) =     12.173 ms/op
    p(100.0000) =     12.173 ms/op


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
# Warmup Iteration   1: 3.798 ±(99.9%) 0.109 ms/op
Iteration   1: 2.387 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.541 ms/op
                 getUser·p0.50:   2.310 ms/op
                 getUser·p0.90:   2.908 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  14.877 ms/op
                 getUser·p0.9999: 15.172 ms/op
                 getUser·p1.00:   15.172 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13339
  mean =      2.387 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 9196 
    [ 2.500,  3.750) = 3740 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 71 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.310 ms/op
     p(90.0000) =      2.908 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     15.172 ms/op
     p(99.9990) =     15.172 ms/op
     p(99.9999) =     15.172 ms/op
    p(100.0000) =     15.172 ms/op


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
# Warmup Iteration   1: 4.529 ±(99.9%) 0.139 ms/op
Iteration   1: 3.794 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.788 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8434
  mean =      3.794 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 490 
    [ 2.500,  3.750) = 3799 
    [ 3.750,  5.000) = 3673 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.145 ms/op
     p(99.0000) =      6.788 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.444          ops/ms
ClientSimple.existUser                       thrpt         12.259          ops/ms
ClientSimple.getUser                         thrpt         11.491          ops/ms
ClientSimple.listUser                        thrpt          8.418          ops/ms
ClientSimple.createUser                       avgt          2.262           ms/op
ClientSimple.existUser                        avgt          1.781           ms/op
ClientSimple.getUser                          avgt          2.094           ms/op
ClientSimple.listUser                         avgt          3.163           ms/op
ClientSimple.createUser                     sample  13484   2.370 ± 0.057   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.599           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.179           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.039           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.874           ms/op
ClientSimple.createUser:createUser·p0.999   sample         37.224           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.116           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.207           ms/op
ClientSimple.existUser                      sample  16004   1.998 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.753           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.867           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.417           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.076           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.059           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.144           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.173           ms/op
ClientSimple.getUser                        sample  13339   2.387 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.541           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.310           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.908           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.199           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.939           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.877           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.172           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.172           ms/op
ClientSimple.listUser                       sample   8434   3.794 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.718           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.736           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.145           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.788           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.908           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.859           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.859           ms/op

Benchmark result is saved to 1721954538652.json
