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
# Warmup Iteration   1: 1.689 ops/ms
Iteration   1: 7.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.325 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.225 ops/ms
Iteration   1: 14.509 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.509 ops/ms


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
# Warmup Iteration   1: 6.572 ops/ms
Iteration   1: 14.031 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.031 ops/ms


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
# Warmup Iteration   1: 6.002 ops/ms
Iteration   1: 8.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.194 ops/ms


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
# Warmup Iteration   1: 3.476 ±(99.9%) 0.071 ms/op
Iteration   1: 2.289 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.289 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.064 ms/op
Iteration   1: 1.683 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.683 ms/op


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
# Warmup Iteration   1: 2.916 ±(99.9%) 0.044 ms/op
Iteration   1: 2.111 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.111 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.111 ms/op
Iteration   1: 3.713 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.713 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.104 ms/op
Iteration   1: 2.270 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.789 ms/op
                 createUser·p0.95:   3.035 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  16.079 ms/op
                 createUser·p0.9999: 16.770 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14303
  mean =      2.270 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 11037 
    [ 2.500,  3.750) = 2891 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.789 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     16.079 ms/op
     p(99.9900) =     16.770 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.073 ms/op
Iteration   1: 1.812 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   1.651 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.642 ms/op
                 existUser·p0.99:   3.916 ms/op
                 existUser·p0.999:  12.490 ms/op
                 existUser·p0.9999: 15.593 ms/op
                 existUser·p1.00:   15.843 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17643
  mean =      1.812 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1023 
    [ 1.250,  2.500) = 15217 
    [ 2.500,  3.750) = 1205 
    [ 3.750,  5.000) = 101 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      1.651 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.916 ms/op
     p(99.9000) =     12.490 ms/op
     p(99.9900) =     15.593 ms/op
     p(99.9990) =     15.843 ms/op
     p(99.9999) =     15.843 ms/op
    p(100.0000) =     15.843 ms/op


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
# Warmup Iteration   1: 3.150 ±(99.9%) 0.078 ms/op
Iteration   1: 2.076 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   1.890 ms/op
                 getUser·p0.90:   2.699 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  23.134 ms/op
                 getUser·p0.9999: 23.428 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15489
  mean =      2.076 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11899 
    [ 2.500,  5.000) = 3447 
    [ 5.000,  7.500) = 47 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.699 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =     23.134 ms/op
     p(99.9900) =     23.428 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.120 ms/op
Iteration   1: 3.423 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.946 ms/op
                 listUser·p0.50:   3.527 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   5.453 ms/op
                 listUser·p0.999:  7.856 ms/op
                 listUser·p0.9999: 8.602 ms/op
                 listUser·p1.00:   8.602 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9343
  mean =      3.423 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 30 
    [1.500, 2.000) = 305 
    [2.000, 2.500) = 999 
    [2.500, 3.000) = 1476 
    [3.000, 3.500) = 1710 
    [3.500, 4.000) = 2891 
    [4.000, 4.500) = 1344 
    [4.500, 5.000) = 360 
    [5.000, 5.500) = 139 
    [5.500, 6.000) = 29 
    [6.000, 6.500) = 20 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 21 
    [7.500, 8.000) = 13 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      5.453 ms/op
     p(99.9000) =      7.856 ms/op
     p(99.9900) =      8.602 ms/op
     p(99.9990) =      8.602 ms/op
     p(99.9999) =      8.602 ms/op
    p(100.0000) =      8.602 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.325          ops/ms
ClientSimple.existUser                       thrpt         14.509          ops/ms
ClientSimple.getUser                         thrpt         14.031          ops/ms
ClientSimple.listUser                        thrpt          8.194          ops/ms
ClientSimple.createUser                       avgt          2.289           ms/op
ClientSimple.existUser                        avgt          1.683           ms/op
ClientSimple.getUser                          avgt          2.111           ms/op
ClientSimple.listUser                         avgt          3.713           ms/op
ClientSimple.createUser                     sample  14303   2.270 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.627           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.035           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.325           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.079           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.770           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.777           ms/op
ClientSimple.existUser                      sample  17643   1.812 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.667           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.651           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.642           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.916           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.490           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.593           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.843           ms/op
ClientSimple.getUser                        sample  15489   2.076 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.615           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.890           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.699           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.121           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.134           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.428           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.626           ms/op
ClientSimple.listUser                       sample   9343   3.423 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.946           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.527           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.637           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.453           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.856           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.602           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.602           ms/op

Benchmark result is saved to 1724566403969.json
