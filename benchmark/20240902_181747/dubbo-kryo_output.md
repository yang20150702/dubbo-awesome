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
# Warmup Iteration   1: 1.162 ops/ms
Iteration   1: 6.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.290 ops/ms


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
# Warmup Iteration   1: 5.897 ops/ms
Iteration   1: 13.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.707 ops/ms


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
# Warmup Iteration   1: 5.713 ops/ms
Iteration   1: 11.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.083 ops/ms


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
# Warmup Iteration   1: 3.707 ops/ms
Iteration   1: 8.243 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.243 ops/ms


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.102 ms/op
Iteration   1: 2.444 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.444 ms/op


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
# Warmup Iteration   1: 3.425 ±(99.9%) 0.047 ms/op
Iteration   1: 1.881 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.881 ms/op


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
# Warmup Iteration   1: 3.341 ±(99.9%) 0.060 ms/op
Iteration   1: 2.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.052 ms/op


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
# Warmup Iteration   1: 4.557 ±(99.9%) 0.088 ms/op
Iteration   1: 3.301 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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
# Warmup Iteration   1: 3.590 ±(99.9%) 0.087 ms/op
Iteration   1: 2.044 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.532 ms/op
                 createUser·p0.50:   1.806 ms/op
                 createUser·p0.90:   2.445 ms/op
                 createUser·p0.95:   2.683 ms/op
                 createUser·p0.99:   6.330 ms/op
                 createUser·p0.999:  32.771 ms/op
                 createUser·p0.9999: 33.358 ms/op
                 createUser·p1.00:   33.358 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15728
  mean =      2.044 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14427 
    [ 2.500,  5.000) = 1066 
    [ 5.000,  7.500) = 137 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.445 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      6.330 ms/op
     p(99.9000) =     32.771 ms/op
     p(99.9900) =     33.358 ms/op
     p(99.9990) =     33.358 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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
# Warmup Iteration   1: 3.408 ±(99.9%) 0.075 ms/op
Iteration   1: 2.063 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.005 ms/op
                 existUser·p0.90:   2.543 ms/op
                 existUser·p0.95:   2.753 ms/op
                 existUser·p0.99:   3.793 ms/op
                 existUser·p0.999:  11.329 ms/op
                 existUser·p0.9999: 11.636 ms/op
                 existUser·p1.00:   11.682 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15561
  mean =      2.063 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 13615 
    [ 2.500,  3.750) = 1640 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      2.005 ms/op
     p(90.0000) =      2.543 ms/op
     p(95.0000) =      2.753 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =     11.329 ms/op
     p(99.9900) =     11.636 ms/op
     p(99.9990) =     11.682 ms/op
     p(99.9999) =     11.682 ms/op
    p(100.0000) =     11.682 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.108 ms/op
Iteration   1: 2.341 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   2.187 ms/op
                 getUser·p0.90:   2.871 ms/op
                 getUser·p0.95:   3.338 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.540 ms/op
                 getUser·p0.9999: 17.826 ms/op
                 getUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13707
  mean =      2.341 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 10421 
    [ 2.500,  3.750) = 2668 
    [ 3.750,  5.000) = 176 
    [ 5.000,  6.250) = 164 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     17.540 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     17.826 ms/op
     p(99.9999) =     17.826 ms/op
    p(100.0000) =     17.826 ms/op


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
# Warmup Iteration   1: 4.780 ±(99.9%) 0.137 ms/op
Iteration   1: 3.558 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.411 ms/op
                 listUser·p0.50:   3.547 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   4.645 ms/op
                 listUser·p0.99:   6.143 ms/op
                 listUser·p0.999:  10.060 ms/op
                 listUser·p0.9999: 10.551 ms/op
                 listUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9016
  mean =      3.558 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 74 
    [ 2.000,  3.000) = 1741 
    [ 3.000,  4.000) = 5343 
    [ 4.000,  5.000) = 1600 
    [ 5.000,  6.000) = 153 
    [ 6.000,  7.000) = 73 
    [ 7.000,  8.000) = 0 
    [ 8.000,  9.000) = 13 
    [ 9.000, 10.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.143 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     10.551 ms/op
     p(99.9990) =     10.551 ms/op
     p(99.9999) =     10.551 ms/op
    p(100.0000) =     10.551 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.290          ops/ms
ClientSimple.existUser                       thrpt         13.707          ops/ms
ClientSimple.getUser                         thrpt         11.083          ops/ms
ClientSimple.listUser                        thrpt          8.243          ops/ms
ClientSimple.createUser                       avgt          2.444           ms/op
ClientSimple.existUser                        avgt          1.881           ms/op
ClientSimple.getUser                          avgt          2.052           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  15728   2.044 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.532           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.806           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.445           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.683           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.330           ms/op
ClientSimple.createUser:createUser·p0.999   sample         32.771           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         33.358           ms/op
ClientSimple.createUser:createUser·p1.00    sample         33.358           ms/op
ClientSimple.existUser                      sample  15561   2.063 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.631           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.005           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.543           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.753           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.793           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.329           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.636           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.682           ms/op
ClientSimple.getUser                        sample  13707   2.341 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.719           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.187           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.338           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.218           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.540           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.826           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.826           ms/op
ClientSimple.listUser                       sample   9016   3.558 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.411           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.547           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.645           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.143           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.060           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.551           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.551           ms/op

Benchmark result is saved to 1725300801034.json
