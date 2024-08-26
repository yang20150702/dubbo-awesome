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
# Warmup Iteration   1: 1.742 ops/ms
Iteration   1: 7.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.133 ops/ms


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
# Warmup Iteration   1: 6.954 ops/ms
Iteration   1: 11.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.126 ops/ms


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
# Warmup Iteration   1: 5.063 ops/ms
Iteration   1: 10.626 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.626 ops/ms


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
# Warmup Iteration   1: 3.921 ops/ms
Iteration   1: 7.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.684 ops/ms


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
# Warmup Iteration   1: 4.446 ±(99.9%) 0.083 ms/op
Iteration   1: 2.169 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.169 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.047 ms/op
Iteration   1: 2.080 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.080 ms/op


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
# Warmup Iteration   1: 3.565 ±(99.9%) 0.067 ms/op
Iteration   1: 2.255 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.255 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.095 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.184 ms/op


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
# Warmup Iteration   1: 3.484 ±(99.9%) 0.090 ms/op
Iteration   1: 2.133 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.429 ms/op
                 createUser·p0.95:   2.720 ms/op
                 createUser·p0.99:   9.776 ms/op
                 createUser·p0.999:  23.068 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15028
  mean =      2.133 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13796 
    [ 2.500,  5.000) = 987 
    [ 5.000,  7.500) = 79 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.429 ms/op
     p(95.0000) =      2.720 ms/op
     p(99.0000) =      9.776 ms/op
     p(99.9000) =     23.068 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 3.081 ±(99.9%) 0.076 ms/op
Iteration   1: 1.915 ±(99.9%) 0.026 ms/op
                 existUser·p0.00:   0.590 ms/op
                 existUser·p0.50:   1.767 ms/op
                 existUser·p0.90:   2.327 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  17.573 ms/op
                 existUser·p0.9999: 18.273 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16699
  mean =      1.915 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 337 
    [ 1.250,  2.500) = 15326 
    [ 2.500,  3.750) = 819 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.590 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.327 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     17.573 ms/op
     p(99.9900) =     18.273 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.098 ms/op
Iteration   1: 2.101 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   2.030 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  12.550 ms/op
                 getUser·p0.9999: 13.828 ms/op
                 getUser·p1.00:   13.828 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15269
  mean =      2.101 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 356 
    [ 1.250,  2.500) = 12205 
    [ 2.500,  3.750) = 2420 
    [ 3.750,  5.000) = 119 
    [ 5.000,  6.250) = 132 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      2.030 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      5.038 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     13.828 ms/op
     p(99.9990) =     13.828 ms/op
     p(99.9999) =     13.828 ms/op
    p(100.0000) =     13.828 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.131 ms/op
Iteration   1: 3.326 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.160 ms/op
                 listUser·p0.999:  20.473 ms/op
                 listUser·p0.9999: 23.396 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9909
  mean =      3.326 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 694 
    [ 2.500,  5.000) = 8902 
    [ 5.000,  7.500) = 247 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     20.473 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.396 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.133          ops/ms
ClientSimple.existUser                       thrpt         11.126          ops/ms
ClientSimple.getUser                         thrpt         10.626          ops/ms
ClientSimple.listUser                        thrpt          7.684          ops/ms
ClientSimple.createUser                       avgt          2.169           ms/op
ClientSimple.existUser                        avgt          2.080           ms/op
ClientSimple.getUser                          avgt          2.255           ms/op
ClientSimple.listUser                         avgt          3.184           ms/op
ClientSimple.createUser                     sample  15028   2.133 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.528           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.429           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.720           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.776           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.068           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.608           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.608           ms/op
ClientSimple.existUser                      sample  16699   1.915 ± 0.026   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.590           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.767           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.327           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.759           ms/op
ClientSimple.existUser:existUser·p0.999     sample         17.573           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.273           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.317           ms/op
ClientSimple.getUser                        sample  15269   2.101 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.738           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.030           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.038           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.550           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.828           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.828           ms/op
ClientSimple.listUser                       sample   9909   3.326 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.110           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.888           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.784           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.160           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.473           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.396           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.396           ms/op

Benchmark result is saved to 1724674695071.json
