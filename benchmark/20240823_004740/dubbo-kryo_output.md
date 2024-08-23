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
# Warmup Iteration   1: 1.274 ops/ms
Iteration   1: 5.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.585 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.402 ops/ms
Iteration   1: 11.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.255 ops/ms


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
# Warmup Iteration   1: 5.022 ops/ms
Iteration   1: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.798 ops/ms


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
# Warmup Iteration   1: 3.653 ops/ms
Iteration   1: 7.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.152 ops/ms


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
# Warmup Iteration   1: 4.472 ±(99.9%) 0.083 ms/op
Iteration   1: 2.305 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.305 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.067 ms/op
Iteration   1: 2.021 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.021 ms/op


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
# Warmup Iteration   1: 3.462 ±(99.9%) 0.061 ms/op
Iteration   1: 2.134 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.134 ms/op


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
# Warmup Iteration   1: 7.514 ±(99.9%) 0.212 ms/op
Iteration   1: 3.704 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.704 ms/op


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
# Warmup Iteration   1: 3.644 ±(99.9%) 0.100 ms/op
Iteration   1: 2.348 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   2.075 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   2.986 ms/op
                 createUser·p0.99:   11.305 ms/op
                 createUser·p0.999:  19.235 ms/op
                 createUser·p0.9999: 20.433 ms/op
                 createUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13602
  mean =      2.348 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11305 
    [ 2.500,  5.000) = 1960 
    [ 5.000,  7.500) = 51 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      2.075 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      2.986 ms/op
     p(99.0000) =     11.305 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     20.433 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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
# Warmup Iteration   1: 3.181 ±(99.9%) 0.077 ms/op
Iteration   1: 2.178 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.702 ms/op
                 existUser·p0.50:   2.064 ms/op
                 existUser·p0.90:   2.683 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   4.009 ms/op
                 existUser·p0.999:  16.472 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14802
  mean =      2.178 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 12023 
    [ 2.500,  3.750) = 2338 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.064 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.009 ms/op
     p(99.9000) =     16.472 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.492 ±(99.9%) 0.080 ms/op
Iteration   1: 2.076 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.615 ms/op
                 getUser·p0.50:   1.933 ms/op
                 getUser·p0.90:   2.540 ms/op
                 getUser·p0.95:   2.777 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  16.777 ms/op
                 getUser·p0.9999: 16.857 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15564
  mean =      2.076 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 127 
    [ 1.250,  2.500) = 13569 
    [ 2.500,  3.750) = 1592 
    [ 3.750,  5.000) = 139 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.540 ms/op
     p(95.0000) =      2.777 ms/op
     p(99.0000) =      4.940 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     16.857 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 6.814 ±(99.9%) 0.234 ms/op
Iteration   1: 3.943 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  13.765 ms/op
                 listUser·p0.9999: 14.811 ms/op
                 listUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8107
  mean =      3.943 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 352 
    [ 2.500,  3.750) = 3021 
    [ 3.750,  5.000) = 4115 
    [ 5.000,  6.250) = 385 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     13.765 ms/op
     p(99.9900) =     14.811 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.585          ops/ms
ClientSimple.existUser                       thrpt         11.255          ops/ms
ClientSimple.getUser                         thrpt          9.798          ops/ms
ClientSimple.listUser                        thrpt          7.152          ops/ms
ClientSimple.createUser                       avgt          2.305           ms/op
ClientSimple.existUser                        avgt          2.021           ms/op
ClientSimple.getUser                          avgt          2.134           ms/op
ClientSimple.listUser                         avgt          3.704           ms/op
ClientSimple.createUser                     sample  13602   2.348 ± 0.048   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.426           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.075           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.986           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.305           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.235           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.433           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.480           ms/op
ClientSimple.existUser                      sample  14802   2.178 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.702           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.064           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.009           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.472           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         17.400           ms/op
ClientSimple.existUser:existUser·p1.00      sample         17.400           ms/op
ClientSimple.getUser                        sample  15564   2.076 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.615           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.933           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.540           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.777           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.940           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.777           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.857           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.876           ms/op
ClientSimple.listUser                       sample   8107   3.943 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.161           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.879           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.801           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.521           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.978           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.765           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.811           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.811           ms/op

Benchmark result is saved to 1724373808714.json
