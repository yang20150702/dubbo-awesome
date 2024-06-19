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
# Warmup Iteration   1: 1.623 ops/ms
Iteration   1: 6.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.643 ops/ms


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
# Warmup Iteration   1: 5.483 ops/ms
Iteration   1: 12.920 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.920 ops/ms


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
# Warmup Iteration   1: 4.576 ops/ms
Iteration   1: 11.405 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.405 ops/ms


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
# Warmup Iteration   1: 4.138 ops/ms
Iteration   1: 8.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.886 ops/ms


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
# Warmup Iteration   1: 4.272 ±(99.9%) 0.087 ms/op
Iteration   1: 2.199 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.199 ms/op


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
# Warmup Iteration   1: 3.815 ±(99.9%) 0.074 ms/op
Iteration   1: 1.909 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.909 ms/op


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
# Warmup Iteration   1: 3.310 ±(99.9%) 0.059 ms/op
Iteration   1: 2.182 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.182 ms/op


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
# Warmup Iteration   1: 5.169 ±(99.9%) 0.087 ms/op
Iteration   1: 4.098 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.098 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.227 ms/op
Iteration   1: 2.598 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   2.228 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   14.172 ms/op
                 createUser·p0.999:  21.452 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12350
  mean =      2.598 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8680 
    [ 2.500,  5.000) = 3118 
    [ 5.000,  7.500) = 235 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      2.228 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =     14.172 ms/op
     p(99.9000) =     21.452 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 2.939 ±(99.9%) 0.077 ms/op
Iteration   1: 1.924 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.384 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   3.749 ms/op
                 existUser·p0.999:  19.351 ms/op
                 existUser·p0.9999: 20.251 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16722
  mean =      1.924 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15501 
    [ 2.500,  5.000) = 1189 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.384 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.749 ms/op
     p(99.9000) =     19.351 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     20.251 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.200 ±(99.9%) 0.077 ms/op
Iteration   1: 1.854 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   1.700 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.666 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  15.053 ms/op
                 getUser·p0.9999: 15.225 ms/op
                 getUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17243
  mean =      1.854 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1708 
    [ 1.250,  2.500) = 13978 
    [ 2.500,  3.750) = 1356 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.753 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =     15.053 ms/op
     p(99.9900) =     15.225 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.131 ms/op
Iteration   1: 2.986 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.904 ms/op
                 listUser·p0.50:   2.740 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.178 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  21.915 ms/op
                 listUser·p0.9999: 23.316 ms/op
                 listUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10739
  mean =      2.986 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3005 
    [ 2.500,  5.000) = 7588 
    [ 5.000,  7.500) = 114 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     21.915 ms/op
     p(99.9900) =     23.316 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.643          ops/ms
ClientSimple.existUser                       thrpt         12.920          ops/ms
ClientSimple.getUser                         thrpt         11.405          ops/ms
ClientSimple.listUser                        thrpt          8.886          ops/ms
ClientSimple.createUser                       avgt          2.199           ms/op
ClientSimple.existUser                        avgt          1.909           ms/op
ClientSimple.getUser                          avgt          2.182           ms/op
ClientSimple.listUser                         avgt          4.098           ms/op
ClientSimple.createUser                     sample  12350   2.598 ± 0.060   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.551           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.228           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.105           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.686           ms/op
ClientSimple.createUser:createUser·p0.99    sample         14.172           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.452           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.692           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.692           ms/op
ClientSimple.existUser                      sample  16722   1.924 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.805           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.765           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.384           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.749           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.351           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.251           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.251           ms/op
ClientSimple.getUser                        sample  17243   1.854 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.753           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.700           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.666           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.243           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.053           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         15.225           ms/op
ClientSimple.getUser:getUser·p1.00          sample         15.237           ms/op
ClientSimple.listUser                       sample  10739   2.986 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.904           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.740           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.867           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.448           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.915           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.316           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.331           ms/op

Benchmark result is saved to 1718820662678.json
