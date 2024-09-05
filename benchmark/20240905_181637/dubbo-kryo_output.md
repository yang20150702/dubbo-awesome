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
# Warmup Iteration   1: 1.710 ops/ms
Iteration   1: 6.215 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.215 ops/ms


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
# Warmup Iteration   1: 7.293 ops/ms
Iteration   1: 12.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.380 ops/ms


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
# Warmup Iteration   1: 6.057 ops/ms
Iteration   1: 12.231 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.231 ops/ms


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
# Warmup Iteration   1: 5.319 ops/ms
Iteration   1: 9.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.103 ops/ms


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.083 ms/op
Iteration   1: 2.434 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.434 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.079 ±(99.9%) 0.047 ms/op
Iteration   1: 2.018 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.018 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.202 ±(99.9%) 0.057 ms/op
Iteration   1: 2.432 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.432 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.939 ±(99.9%) 0.091 ms/op
Iteration   1: 3.197 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.197 ms/op


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
# Warmup Iteration   1: 4.008 ±(99.9%) 0.126 ms/op
Iteration   1: 2.210 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.418 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.728 ms/op
                 createUser·p0.95:   3.000 ms/op
                 createUser·p0.99:   8.065 ms/op
                 createUser·p0.999:  15.745 ms/op
                 createUser·p0.9999: 16.395 ms/op
                 createUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14451
  mean =      2.210 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 147 
    [ 1.250,  2.500) = 12136 
    [ 2.500,  3.750) = 1807 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.728 ms/op
     p(95.0000) =      3.000 ms/op
     p(99.0000) =      8.065 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     16.395 ms/op
     p(99.9990) =     16.482 ms/op
     p(99.9999) =     16.482 ms/op
    p(100.0000) =     16.482 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.896 ±(99.9%) 0.064 ms/op
Iteration   1: 1.846 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.345 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.273 ms/op
                 existUser·p0.95:   2.404 ms/op
                 existUser·p0.99:   3.101 ms/op
                 existUser·p0.999:  24.545 ms/op
                 existUser·p0.9999: 25.420 ms/op
                 existUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17485
  mean =      1.846 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16948 
    [ 2.500,  5.000) = 466 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.273 ms/op
     p(95.0000) =      2.404 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     24.545 ms/op
     p(99.9900) =     25.420 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 3.323 ±(99.9%) 0.112 ms/op
Iteration   1: 1.957 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   1.804 ms/op
                 getUser·p0.90:   2.466 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   4.186 ms/op
                 getUser·p0.999:  13.812 ms/op
                 getUser·p0.9999: 14.053 ms/op
                 getUser·p1.00:   14.074 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16402
  mean =      1.957 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 134 
    [ 1.250,  2.500) = 14756 
    [ 2.500,  3.750) = 1295 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      1.804 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     14.053 ms/op
     p(99.9990) =     14.074 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.116 ms/op
Iteration   1: 3.428 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.266 ms/op
                 listUser·p0.50:   3.330 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.011 ms/op
                 listUser·p0.999:  21.026 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9323
  mean =      3.428 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 931 
    [ 2.500,  5.000) = 8190 
    [ 5.000,  7.500) = 170 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.011 ms/op
     p(99.9000) =     21.026 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.215          ops/ms
ClientSimple.existUser                       thrpt         12.380          ops/ms
ClientSimple.getUser                         thrpt         12.231          ops/ms
ClientSimple.listUser                        thrpt          9.103          ops/ms
ClientSimple.createUser                       avgt          2.434           ms/op
ClientSimple.existUser                        avgt          2.018           ms/op
ClientSimple.getUser                          avgt          2.432           ms/op
ClientSimple.listUser                         avgt          3.197           ms/op
ClientSimple.createUser                     sample  14451   2.210 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.418           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.728           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.000           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.065           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.745           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.395           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.482           ms/op
ClientSimple.existUser                      sample  17485   1.846 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.345           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.731           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.273           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.404           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.101           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.545           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.420           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.494           ms/op
ClientSimple.getUser                        sample  16402   1.957 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.783           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.804           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.466           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.186           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.812           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.053           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.074           ms/op
ClientSimple.listUser                       sample   9323   3.428 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.266           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.330           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.227           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.011           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.026           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.266           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.266           ms/op

Benchmark result is saved to 1725559950706.json
