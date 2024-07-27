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
# Warmup Iteration   1: 1.825 ops/ms
Iteration   1: 7.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.027 ops/ms


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
# Warmup Iteration   1: 5.990 ops/ms
Iteration   1: 12.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.968 ops/ms


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
# Warmup Iteration   1: 6.028 ops/ms
Iteration   1: 13.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.262 ops/ms


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
# Warmup Iteration   1: 5.219 ops/ms
Iteration   1: 8.749 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.749 ops/ms


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.090 ms/op
Iteration   1: 2.107 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.107 ms/op


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
# Warmup Iteration   1: 3.560 ±(99.9%) 0.065 ms/op
Iteration   1: 1.721 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.721 ms/op


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
# Warmup Iteration   1: 3.506 ±(99.9%) 0.066 ms/op
Iteration   1: 2.214 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.214 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.078 ms/op
Iteration   1: 3.725 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.725 ms/op


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.090 ms/op
Iteration   1: 2.233 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.476 ms/op
                 createUser·p0.50:   2.077 ms/op
                 createUser·p0.90:   2.806 ms/op
                 createUser·p0.95:   3.084 ms/op
                 createUser·p0.99:   7.930 ms/op
                 createUser·p0.999:  13.329 ms/op
                 createUser·p0.9999: 14.889 ms/op
                 createUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14465
  mean =      2.233 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 258 
    [ 1.250,  2.500) = 11112 
    [ 2.500,  3.750) = 2724 
    [ 3.750,  5.000) = 125 
    [ 5.000,  6.250) = 59 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      2.077 ms/op
     p(90.0000) =      2.806 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     13.329 ms/op
     p(99.9900) =     14.889 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 2.906 ±(99.9%) 0.063 ms/op
Iteration   1: 1.908 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.413 ms/op
                 existUser·p0.99:   3.828 ms/op
                 existUser·p0.999:  22.323 ms/op
                 existUser·p0.9999: 22.565 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16750
  mean =      1.908 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16153 
    [ 2.500,  5.000) = 492 
    [ 5.000,  7.500) = 38 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.413 ms/op
     p(99.0000) =      3.828 ms/op
     p(99.9000) =     22.323 ms/op
     p(99.9900) =     22.565 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.675 ms/op
    p(100.0000) =     22.675 ms/op


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
# Warmup Iteration   1: 3.491 ±(99.9%) 0.087 ms/op
Iteration   1: 2.031 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.942 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.470 ms/op
                 getUser·p0.95:   2.716 ms/op
                 getUser·p0.99:   3.466 ms/op
                 getUser·p0.999:  13.570 ms/op
                 getUser·p0.9999: 13.898 ms/op
                 getUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15741
  mean =      2.031 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 14233 
    [ 2.500,  3.750) = 1353 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.942 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.716 ms/op
     p(99.0000) =      3.466 ms/op
     p(99.9000) =     13.570 ms/op
     p(99.9900) =     13.898 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


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
# Warmup Iteration   1: 4.792 ±(99.9%) 0.167 ms/op
Iteration   1: 3.533 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   3.465 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.080 ms/op
                 listUser·p0.99:   10.851 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9056
  mean =      3.533 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 1446 
    [ 2.500,  3.750) = 4701 
    [ 3.750,  5.000) = 2413 
    [ 5.000,  6.250) = 286 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.080 ms/op
     p(99.0000) =     10.851 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     17.924 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.027          ops/ms
ClientSimple.existUser                       thrpt         12.968          ops/ms
ClientSimple.getUser                         thrpt         13.262          ops/ms
ClientSimple.listUser                        thrpt          8.749          ops/ms
ClientSimple.createUser                       avgt          2.107           ms/op
ClientSimple.existUser                        avgt          1.721           ms/op
ClientSimple.getUser                          avgt          2.214           ms/op
ClientSimple.listUser                         avgt          3.725           ms/op
ClientSimple.createUser                     sample  14465   2.233 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.476           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.077           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.806           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.930           ms/op
ClientSimple.createUser:createUser·p0.999   sample         13.329           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.889           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.926           ms/op
ClientSimple.existUser                      sample  16750   1.908 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.527           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.413           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.828           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.323           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.565           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.675           ms/op
ClientSimple.getUser                        sample  15741   2.031 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.942           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.470           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.466           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.570           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.898           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.926           ms/op
ClientSimple.listUser                       sample   9056   3.533 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.741           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.465           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.350           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.080           ms/op
ClientSimple.listUser:listUser·p0.99        sample         10.851           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.138           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.924           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.924           ms/op

Benchmark result is saved to 1722060714285.json
