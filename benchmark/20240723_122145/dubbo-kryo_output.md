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
# Warmup Iteration   1: 1.917 ops/ms
Iteration   1: 7.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.577 ops/ms


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
# Warmup Iteration   1: 6.136 ops/ms
Iteration   1: 13.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.769 ops/ms


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
# Warmup Iteration   1: 6.162 ops/ms
Iteration   1: 14.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.644 ops/ms


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
# Warmup Iteration   1: 5.720 ops/ms
Iteration   1: 8.551 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.551 ops/ms


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
# Warmup Iteration   1: 3.772 ±(99.9%) 0.071 ms/op
Iteration   1: 2.234 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.234 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.055 ms/op
Iteration   1: 2.073 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.073 ms/op


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
# Warmup Iteration   1: 2.950 ±(99.9%) 0.060 ms/op
Iteration   1: 1.883 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.883 ms/op


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.092 ms/op
Iteration   1: 3.422 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.422 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.601 ±(99.9%) 0.086 ms/op
Iteration   1: 2.193 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   1.919 ms/op
                 createUser·p0.90:   2.547 ms/op
                 createUser·p0.95:   2.884 ms/op
                 createUser·p0.99:   9.736 ms/op
                 createUser·p0.999:  26.870 ms/op
                 createUser·p0.9999: 27.967 ms/op
                 createUser·p1.00:   28.148 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14591
  mean =      2.193 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12947 
    [ 2.500,  5.000) = 1351 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      1.919 ms/op
     p(90.0000) =      2.547 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      9.736 ms/op
     p(99.9000) =     26.870 ms/op
     p(99.9900) =     27.967 ms/op
     p(99.9990) =     28.148 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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
# Warmup Iteration   1: 3.013 ±(99.9%) 0.067 ms/op
Iteration   1: 2.094 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.013 ms/op
                 existUser·p0.90:   2.683 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   3.589 ms/op
                 existUser·p0.999:  13.615 ms/op
                 existUser·p0.9999: 13.836 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15275
  mean =      2.094 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 474 
    [ 1.250,  2.500) = 12179 
    [ 2.500,  3.750) = 2493 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      3.589 ms/op
     p(99.9000) =     13.615 ms/op
     p(99.9900) =     13.836 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.071 ms/op
Iteration   1: 2.178 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.664 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  19.342 ms/op
                 getUser·p0.9999: 20.454 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14742
  mean =      2.178 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10919 
    [ 2.500,  5.000) = 3744 
    [ 5.000,  7.500) = 15 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     19.342 ms/op
     p(99.9900) =     20.454 ms/op
     p(99.9990) =     20.578 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.113 ms/op
Iteration   1: 3.311 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.627 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.422 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   5.691 ms/op
                 listUser·p0.999:  6.494 ms/op
                 listUser·p0.9999: 8.536 ms/op
                 listUser·p1.00:   8.536 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9661
  mean =      3.311 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 33 
    [1.500, 2.000) = 301 
    [2.000, 2.500) = 1626 
    [2.500, 3.000) = 2108 
    [3.000, 3.500) = 1692 
    [3.500, 4.000) = 1641 
    [4.000, 4.500) = 1414 
    [4.500, 5.000) = 498 
    [5.000, 5.500) = 218 
    [5.500, 6.000) = 68 
    [6.000, 6.500) = 49 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 4 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.422 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.691 ms/op
     p(99.9000) =      6.494 ms/op
     p(99.9900) =      8.536 ms/op
     p(99.9990) =      8.536 ms/op
     p(99.9999) =      8.536 ms/op
    p(100.0000) =      8.536 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.577          ops/ms
ClientSimple.existUser                       thrpt         13.769          ops/ms
ClientSimple.getUser                         thrpt         14.644          ops/ms
ClientSimple.listUser                        thrpt          8.551          ops/ms
ClientSimple.createUser                       avgt          2.234           ms/op
ClientSimple.existUser                        avgt          2.073           ms/op
ClientSimple.getUser                          avgt          1.883           ms/op
ClientSimple.listUser                         avgt          3.422           ms/op
ClientSimple.createUser                     sample  14591   2.193 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.591           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.919           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.547           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.884           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.736           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.870           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.967           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.148           ms/op
ClientSimple.existUser                      sample  15275   2.094 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.586           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.589           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.615           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.836           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.844           ms/op
ClientSimple.getUser                        sample  14742   2.178 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.664           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.415           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.342           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.454           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.578           ms/op
ClientSimple.listUser                       sample   9661   3.311 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.627           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.422           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.776           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.691           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.494           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.536           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.536           ms/op

Benchmark result is saved to 1721737085633.json
