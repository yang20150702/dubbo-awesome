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
# Warmup Iteration   1: 1.867 ops/ms
Iteration   1: 7.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.316 ops/ms


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
# Warmup Iteration   1: 6.618 ops/ms
Iteration   1: 12.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.716 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.502 ops/ms
Iteration   1: 14.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.808 ops/ms


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
# Warmup Iteration   1: 4.881 ops/ms
Iteration   1: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.706 ops/ms


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.062 ms/op
Iteration   1: 2.503 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.503 ms/op


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.057 ms/op
Iteration   1: 1.832 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.832 ms/op


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
# Warmup Iteration   1: 3.384 ±(99.9%) 0.052 ms/op
Iteration   1: 2.227 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.227 ms/op


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.094 ms/op
Iteration   1: 3.087 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.087 ms/op


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.092 ms/op
Iteration   1: 2.204 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.560 ms/op
                 createUser·p0.95:   2.834 ms/op
                 createUser·p0.99:   4.618 ms/op
                 createUser·p0.999:  15.032 ms/op
                 createUser·p0.9999: 16.426 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14510
  mean =      2.204 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 12692 
    [ 2.500,  3.750) = 1450 
    [ 3.750,  5.000) = 145 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.560 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      4.618 ms/op
     p(99.9000) =     15.032 ms/op
     p(99.9900) =     16.426 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.129 ±(99.9%) 0.082 ms/op
Iteration   1: 2.009 ±(99.9%) 0.125 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   1.649 ms/op
                 existUser·p0.90:   2.392 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   4.352 ms/op
                 existUser·p0.999:  107.273 ms/op
                 existUser·p0.9999: 108.844 ms/op
                 existUser·p1.00:   108.921 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15892
  mean =      2.009 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 15846 
    [ 12.500,  25.000) = 14 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 32 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      1.649 ms/op
     p(90.0000) =      2.392 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      4.352 ms/op
     p(99.9000) =    107.273 ms/op
     p(99.9900) =    108.844 ms/op
     p(99.9990) =    108.921 ms/op
     p(99.9999) =    108.921 ms/op
    p(100.0000) =    108.921 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.088 ms/op
Iteration   1: 2.315 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   2.253 ms/op
                 getUser·p0.90:   2.806 ms/op
                 getUser·p0.95:   2.994 ms/op
                 getUser·p0.99:   3.619 ms/op
                 getUser·p0.999:  17.039 ms/op
                 getUser·p0.9999: 18.128 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13824
  mean =      2.315 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 10209 
    [ 2.500,  3.750) = 3382 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 27 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      3.619 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     18.128 ms/op
     p(99.9990) =     18.153 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.680 ±(99.9%) 0.123 ms/op
Iteration   1: 3.050 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   1.021 ms/op
                 listUser·p0.50:   2.789 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.753 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 19.475 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10477
  mean =      3.050 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2598 
    [ 2.500,  3.750) = 6032 
    [ 3.750,  5.000) = 1652 
    [ 5.000,  6.250) = 150 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.753 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     19.475 ms/op
     p(99.9990) =     19.497 ms/op
     p(99.9999) =     19.497 ms/op
    p(100.0000) =     19.497 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt    Score   Error   Units
ClientSimple.createUser                      thrpt           7.316          ops/ms
ClientSimple.existUser                       thrpt          12.716          ops/ms
ClientSimple.getUser                         thrpt          14.808          ops/ms
ClientSimple.listUser                        thrpt           8.706          ops/ms
ClientSimple.createUser                       avgt           2.503           ms/op
ClientSimple.existUser                        avgt           1.832           ms/op
ClientSimple.getUser                          avgt           2.227           ms/op
ClientSimple.listUser                         avgt           3.087           ms/op
ClientSimple.createUser                     sample  14510    2.204 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample           0.689           ms/op
ClientSimple.createUser:createUser·p0.50    sample           2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample           2.560           ms/op
ClientSimple.createUser:createUser·p0.95    sample           2.834           ms/op
ClientSimple.createUser:createUser·p0.99    sample           4.618           ms/op
ClientSimple.createUser:createUser·p0.999   sample          15.032           ms/op
ClientSimple.createUser:createUser·p0.9999  sample          16.426           ms/op
ClientSimple.createUser:createUser·p1.00    sample          16.433           ms/op
ClientSimple.existUser                      sample  15892    2.009 ± 0.125   ms/op
ClientSimple.existUser:existUser·p0.00      sample           0.693           ms/op
ClientSimple.existUser:existUser·p0.50      sample           1.649           ms/op
ClientSimple.existUser:existUser·p0.90      sample           2.392           ms/op
ClientSimple.existUser:existUser·p0.95      sample           2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample           4.352           ms/op
ClientSimple.existUser:existUser·p0.999     sample         107.273           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         108.844           ms/op
ClientSimple.existUser:existUser·p1.00      sample         108.921           ms/op
ClientSimple.getUser                        sample  13824    2.315 ± 0.026   ms/op
ClientSimple.getUser:getUser·p0.00          sample           0.825           ms/op
ClientSimple.getUser:getUser·p0.50          sample           2.253           ms/op
ClientSimple.getUser:getUser·p0.90          sample           2.806           ms/op
ClientSimple.getUser:getUser·p0.95          sample           2.994           ms/op
ClientSimple.getUser:getUser·p0.99          sample           3.619           ms/op
ClientSimple.getUser:getUser·p0.999         sample          17.039           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          18.128           ms/op
ClientSimple.getUser:getUser·p1.00          sample          18.153           ms/op
ClientSimple.listUser                       sample  10477    3.050 ± 0.037   ms/op
ClientSimple.listUser:listUser·p0.00        sample           1.021           ms/op
ClientSimple.listUser:listUser·p0.50        sample           2.789           ms/op
ClientSimple.listUser:listUser·p0.90        sample           4.125           ms/op
ClientSimple.listUser:listUser·p0.95        sample           4.440           ms/op
ClientSimple.listUser:listUser·p0.99        sample           5.753           ms/op
ClientSimple.listUser:listUser·p0.999       sample          18.645           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          19.475           ms/op
ClientSimple.listUser:listUser·p1.00        sample          19.497           ms/op

Benchmark result is saved to 1722622388001.json
