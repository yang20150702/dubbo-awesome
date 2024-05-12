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
# Warmup Iteration   1: 1.609 ops/ms
Iteration   1: 6.580 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.580 ops/ms


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
# Warmup Iteration   1: 6.002 ops/ms
Iteration   1: 11.536 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.536 ops/ms


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
# Warmup Iteration   1: 5.223 ops/ms
Iteration   1: 12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.494 ops/ms


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
# Warmup Iteration   1: 5.358 ops/ms
Iteration   1: 8.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.363 ops/ms


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
# Warmup Iteration   1: 3.860 ±(99.9%) 0.061 ms/op
Iteration   1: 2.247 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.247 ms/op


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
# Warmup Iteration   1: 3.266 ±(99.9%) 0.061 ms/op
Iteration   1: 2.089 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.089 ms/op


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
# Warmup Iteration   1: 3.405 ±(99.9%) 0.050 ms/op
Iteration   1: 1.852 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.852 ms/op


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.088 ms/op
Iteration   1: 3.651 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.651 ms/op


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
# Warmup Iteration   1: 3.575 ±(99.9%) 0.085 ms/op
Iteration   1: 2.299 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.721 ms/op
                 createUser·p0.50:   2.191 ms/op
                 createUser·p0.90:   2.818 ms/op
                 createUser·p0.95:   3.006 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  16.130 ms/op
                 createUser·p0.9999: 17.747 ms/op
                 createUser·p1.00:   17.760 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13901
  mean =      2.299 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 9668 
    [ 2.500,  3.750) = 3911 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.818 ms/op
     p(95.0000) =      3.006 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =     16.130 ms/op
     p(99.9900) =     17.747 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.760 ms/op
    p(100.0000) =     17.760 ms/op


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
# Warmup Iteration   1: 3.049 ±(99.9%) 0.083 ms/op
Iteration   1: 1.772 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.466 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   2.138 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.164 ms/op
                 existUser·p0.999:  31.031 ms/op
                 existUser·p0.9999: 31.883 ms/op
                 existUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18047
  mean =      1.772 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17083 
    [ 2.500,  5.000) = 877 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.138 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.164 ms/op
     p(99.9000) =     31.031 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     31.883 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 2.981 ±(99.9%) 0.085 ms/op
Iteration   1: 2.139 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   2.081 ms/op
                 getUser·p0.90:   2.748 ms/op
                 getUser·p0.95:   3.027 ms/op
                 getUser·p0.99:   4.726 ms/op
                 getUser·p0.999:  6.693 ms/op
                 getUser·p0.9999: 8.770 ms/op
                 getUser·p1.00:   9.290 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14952
  mean =      2.139 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 61 
    [ 1.000,  2.000) = 6247 
    [ 2.000,  3.000) = 7839 
    [ 3.000,  4.000) = 626 
    [ 4.000,  5.000) = 61 
    [ 5.000,  6.000) = 78 
    [ 6.000,  7.000) = 37 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.081 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      4.726 ms/op
     p(99.9000) =      6.693 ms/op
     p(99.9900) =      8.770 ms/op
     p(99.9990) =      9.290 ms/op
     p(99.9999) =      9.290 ms/op
    p(100.0000) =      9.290 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.156 ms/op
Iteration   1: 3.312 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.084 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.459 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9653
  mean =      3.312 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 535 
    [ 2.500,  3.750) = 6969 
    [ 3.750,  5.000) = 1895 
    [ 5.000,  6.250) = 123 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.260 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.459 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.580          ops/ms
ClientSimple.existUser                       thrpt         11.536          ops/ms
ClientSimple.getUser                         thrpt         12.494          ops/ms
ClientSimple.listUser                        thrpt          8.363          ops/ms
ClientSimple.createUser                       avgt          2.247           ms/op
ClientSimple.existUser                        avgt          2.089           ms/op
ClientSimple.getUser                          avgt          1.852           ms/op
ClientSimple.listUser                         avgt          3.651           ms/op
ClientSimple.createUser                     sample  13901   2.299 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.721           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.191           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.818           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.006           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.251           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.130           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.747           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.760           ms/op
ClientSimple.existUser                      sample  18047   1.772 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.466           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.608           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.138           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.164           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.031           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         31.883           ms/op
ClientSimple.existUser:existUser·p1.00      sample         31.883           ms/op
ClientSimple.getUser                        sample  14952   2.139 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.677           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.081           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.027           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.726           ms/op
ClientSimple.getUser:getUser·p0.999         sample          6.693           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.770           ms/op
ClientSimple.getUser:getUser·p1.00          sample          9.290           ms/op
ClientSimple.listUser                       sample   9653   3.312 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.260           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.084           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.071           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.459           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.072           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.793           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.793           ms/op

Benchmark result is saved to 1715516147407.json
