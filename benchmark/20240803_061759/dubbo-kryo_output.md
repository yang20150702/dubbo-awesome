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
# Warmup Iteration   1: 1.047 ops/ms
Iteration   1: 5.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.169 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ops/ms
Iteration   1: 11.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.684 ops/ms


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
# Warmup Iteration   1: 4.643 ops/ms
Iteration   1: 9.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.512 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ops/ms
Iteration   1: 7.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.810 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.496 ±(99.9%) 0.091 ms/op
Iteration   1: 2.291 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.291 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.392 ±(99.9%) 0.055 ms/op
Iteration   1: 1.974 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.080 ms/op
Iteration   1: 2.156 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.156 ms/op


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
# Warmup Iteration   1: 5.410 ±(99.9%) 0.117 ms/op
Iteration   1: 3.684 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.684 ms/op


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.229 ms/op
Iteration   1: 2.686 ±(99.9%) 0.070 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   2.417 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.698 ms/op
                 createUser·p0.99:   11.125 ms/op
                 createUser·p0.999:  41.163 ms/op
                 createUser·p0.9999: 41.288 ms/op
                 createUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 11902
  mean =      2.686 ±(99.9%) 0.070 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 11572 
    [ 5.000, 10.000) = 167 
    [10.000, 15.000) = 131 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      2.417 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.698 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     41.163 ms/op
     p(99.9900) =     41.288 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.074 ms/op
Iteration   1: 1.739 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   1.636 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.380 ms/op
                 existUser·p0.99:   3.277 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 12.911 ms/op
                 existUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18388
  mean =      1.739 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1186 
    [ 1.250,  2.500) = 16543 
    [ 2.500,  3.750) = 563 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      1.636 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.380 ms/op
     p(99.0000) =      3.277 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     12.911 ms/op
     p(99.9990) =     13.255 ms/op
     p(99.9999) =     13.255 ms/op
    p(100.0000) =     13.255 ms/op


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
# Warmup Iteration   1: 3.554 ±(99.9%) 0.105 ms/op
Iteration   1: 2.212 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.540 ms/op
                 getUser·p0.50:   2.054 ms/op
                 getUser·p0.90:   2.966 ms/op
                 getUser·p0.95:   3.252 ms/op
                 getUser·p0.99:   4.585 ms/op
                 getUser·p0.999:  19.202 ms/op
                 getUser·p0.9999: 19.318 ms/op
                 getUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14527
  mean =      2.212 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 10169 
    [ 2.500,  3.750) = 3923 
    [ 3.750,  5.000) = 189 
    [ 5.000,  6.250) = 43 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      2.054 ms/op
     p(90.0000) =      2.966 ms/op
     p(95.0000) =      3.252 ms/op
     p(99.0000) =      4.585 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.318 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.139 ms/op
Iteration   1: 3.483 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.338 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   7.732 ms/op
                 listUser·p0.999:  17.231 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9159
  mean =      3.483 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1371 
    [ 2.500,  3.750) = 5386 
    [ 3.750,  5.000) = 1831 
    [ 5.000,  6.250) = 283 
    [ 6.250,  7.500) = 164 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.032 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      7.732 ms/op
     p(99.9000) =     17.231 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.169          ops/ms
ClientSimple.existUser                       thrpt         11.684          ops/ms
ClientSimple.getUser                         thrpt          9.512          ops/ms
ClientSimple.listUser                        thrpt          7.810          ops/ms
ClientSimple.createUser                       avgt          2.291           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.156           ms/op
ClientSimple.listUser                         avgt          3.684           ms/op
ClientSimple.createUser                     sample  11902   2.686 ± 0.070   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.827           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.417           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.698           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.125           ms/op
ClientSimple.createUser:createUser·p0.999   sample         41.163           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         41.288           ms/op
ClientSimple.createUser:createUser·p1.00    sample         41.288           ms/op
ClientSimple.existUser                      sample  18388   1.739 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.761           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.636           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.380           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.277           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.878           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.911           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.255           ms/op
ClientSimple.getUser                        sample  14527   2.212 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.540           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.054           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.252           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.585           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.202           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.318           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.333           ms/op
ClientSimple.listUser                       sample   9159   3.483 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.032           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.338           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.505           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.732           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.231           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.793           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.793           ms/op

Benchmark result is saved to 1722665620512.json
