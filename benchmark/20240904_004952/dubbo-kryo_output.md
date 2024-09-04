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
# Warmup Iteration   1: 1.796 ops/ms
Iteration   1: 6.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.285 ops/ms


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
# Warmup Iteration   1: 6.543 ops/ms
Iteration   1: 13.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.913 ops/ms


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
# Warmup Iteration   1: 5.405 ops/ms
Iteration   1: 12.709 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.709 ops/ms


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
# Warmup Iteration   1: 3.633 ops/ms
Iteration   1: 7.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.721 ops/ms


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
# Warmup Iteration   1: 4.313 ±(99.9%) 0.094 ms/op
Iteration   1: 2.256 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.256 ms/op


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
# Warmup Iteration   1: 2.995 ±(99.9%) 0.043 ms/op
Iteration   1: 1.776 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.776 ms/op


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
# Warmup Iteration   1: 3.330 ±(99.9%) 0.064 ms/op
Iteration   1: 2.045 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.045 ms/op


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.078 ms/op
Iteration   1: 3.235 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.235 ms/op


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
# Warmup Iteration   1: 3.603 ±(99.9%) 0.096 ms/op
Iteration   1: 2.228 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.644 ms/op
                 createUser·p0.50:   2.023 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.843 ms/op
                 createUser·p0.99:   12.567 ms/op
                 createUser·p0.999:  19.333 ms/op
                 createUser·p0.9999: 21.513 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14348
  mean =      2.228 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12654 
    [ 2.500,  5.000) = 1455 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.023 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.843 ms/op
     p(99.0000) =     12.567 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     21.513 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 3.297 ±(99.9%) 0.090 ms/op
Iteration   1: 1.984 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.429 ms/op
                 existUser·p0.50:   1.907 ms/op
                 existUser·p0.90:   2.437 ms/op
                 existUser·p0.95:   2.638 ms/op
                 existUser·p0.99:   3.935 ms/op
                 existUser·p0.999:  10.957 ms/op
                 existUser·p0.9999: 12.461 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16112
  mean =      1.984 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 251 
    [ 1.250,  2.500) = 14564 
    [ 2.500,  3.750) = 1098 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.638 ms/op
     p(99.0000) =      3.935 ms/op
     p(99.9000) =     10.957 ms/op
     p(99.9900) =     12.461 ms/op
     p(99.9990) =     12.501 ms/op
     p(99.9999) =     12.501 ms/op
    p(100.0000) =     12.501 ms/op


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
# Warmup Iteration   1: 3.545 ±(99.9%) 0.090 ms/op
Iteration   1: 2.321 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.191 ms/op
                 getUser·p0.90:   2.720 ms/op
                 getUser·p0.95:   2.982 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  18.554 ms/op
                 getUser·p0.9999: 19.142 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13778
  mean =      2.321 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 10638 
    [ 2.500,  3.750) = 2852 
    [ 3.750,  5.000) = 135 
    [ 5.000,  6.250) = 36 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.982 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     18.554 ms/op
     p(99.9900) =     19.142 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.117 ms/op
Iteration   1: 3.521 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.278 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.818 ms/op
                 listUser·p0.999:  6.439 ms/op
                 listUser·p0.9999: 7.201 ms/op
                 listUser·p1.00:   7.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9087
  mean =      3.521 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 31 
    [1.500, 2.000) = 40 
    [2.000, 2.500) = 637 
    [2.500, 3.000) = 1092 
    [3.000, 3.500) = 2518 
    [3.500, 4.000) = 2865 
    [4.000, 4.500) = 1283 
    [4.500, 5.000) = 411 
    [5.000, 5.500) = 93 
    [5.500, 6.000) = 52 
    [6.000, 6.500) = 60 
    [6.500, 7.000) = 1 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.954 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.278 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.818 ms/op
     p(99.9000) =      6.439 ms/op
     p(99.9900) =      7.201 ms/op
     p(99.9990) =      7.201 ms/op
     p(99.9999) =      7.201 ms/op
    p(100.0000) =      7.201 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.285          ops/ms
ClientSimple.existUser                       thrpt         13.913          ops/ms
ClientSimple.getUser                         thrpt         12.709          ops/ms
ClientSimple.listUser                        thrpt          7.721          ops/ms
ClientSimple.createUser                       avgt          2.256           ms/op
ClientSimple.existUser                        avgt          1.776           ms/op
ClientSimple.getUser                          avgt          2.045           ms/op
ClientSimple.listUser                         avgt          3.235           ms/op
ClientSimple.createUser                     sample  14348   2.228 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.644           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.023           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.843           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.567           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.333           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.513           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.627           ms/op
ClientSimple.existUser                      sample  16112   1.984 ± 0.016   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.429           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.907           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.437           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.935           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.957           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.461           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.501           ms/op
ClientSimple.getUser                        sample  13778   2.321 ± 0.029   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.741           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.191           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.720           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.982           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.554           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.142           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.464           ms/op
ClientSimple.listUser                       sample   9087   3.521 ± 0.024   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.954           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.535           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.278           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.818           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.439           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.201           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.201           ms/op

Benchmark result is saved to 1725410737182.json
