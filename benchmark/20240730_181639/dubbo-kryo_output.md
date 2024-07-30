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
# Warmup Iteration   1: 1.504 ops/ms
Iteration   1: 6.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.679 ops/ms


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
# Warmup Iteration   1: 6.549 ops/ms
Iteration   1: 11.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.272 ops/ms


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
# Warmup Iteration   1: 4.728 ops/ms
Iteration   1: 12.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.396 ops/ms


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
# Warmup Iteration   1: 4.570 ops/ms
Iteration   1: 8.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.656 ops/ms


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.106 ms/op
Iteration   1: 2.293 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.293 ms/op


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
# Warmup Iteration   1: 3.640 ±(99.9%) 0.057 ms/op
Iteration   1: 1.961 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.961 ms/op


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
# Warmup Iteration   1: 3.356 ±(99.9%) 0.058 ms/op
Iteration   1: 1.858 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.858 ms/op


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
# Warmup Iteration   1: 5.307 ±(99.9%) 0.111 ms/op
Iteration   1: 3.381 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.381 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.097 ms/op
Iteration   1: 2.363 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   2.105 ms/op
                 createUser·p0.90:   2.707 ms/op
                 createUser·p0.95:   3.434 ms/op
                 createUser·p0.99:   6.551 ms/op
                 createUser·p0.999:  24.913 ms/op
                 createUser·p0.9999: 26.735 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13529
  mean =      2.363 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11428 
    [ 2.500,  5.000) = 1874 
    [ 5.000,  7.500) = 117 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.434 ms/op
     p(99.0000) =      6.551 ms/op
     p(99.9000) =     24.913 ms/op
     p(99.9900) =     26.735 ms/op
     p(99.9990) =     26.804 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.465 ±(99.9%) 0.089 ms/op
Iteration   1: 2.250 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   2.187 ms/op
                 existUser·p0.90:   2.822 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  13.284 ms/op
                 existUser·p0.9999: 13.513 ms/op
                 existUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14194
  mean =      2.250 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 290 
    [ 1.250,  2.500) = 10359 
    [ 2.500,  3.750) = 3290 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.187 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     13.284 ms/op
     p(99.9900) =     13.513 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.145 ms/op
Iteration   1: 2.317 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.683 ms/op
                 getUser·p0.50:   1.995 ms/op
                 getUser·p0.90:   3.183 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   6.044 ms/op
                 getUser·p0.999:  23.691 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13820
  mean =      2.317 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10249 
    [ 2.500,  5.000) = 3393 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.995 ms/op
     p(90.0000) =      3.183 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      6.044 ms/op
     p(99.9000) =     23.691 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.148 ms/op
Iteration   1: 3.830 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.118 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   7.497 ms/op
                 listUser·p0.999:  14.625 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8354
  mean =      3.830 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 557 
    [ 2.500,  3.750) = 3431 
    [ 3.750,  5.000) = 3913 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.118 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.497 ms/op
     p(99.9000) =     14.625 ms/op
     p(99.9900) =     14.893 ms/op
     p(99.9990) =     14.893 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.679          ops/ms
ClientSimple.existUser                       thrpt         11.272          ops/ms
ClientSimple.getUser                         thrpt         12.396          ops/ms
ClientSimple.listUser                        thrpt          8.656          ops/ms
ClientSimple.createUser                       avgt          2.293           ms/op
ClientSimple.existUser                        avgt          1.961           ms/op
ClientSimple.getUser                          avgt          1.858           ms/op
ClientSimple.listUser                         avgt          3.381           ms/op
ClientSimple.createUser                     sample  13529   2.363 ± 0.042   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.708           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.105           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.707           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.434           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.551           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.913           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         26.735           ms/op
ClientSimple.createUser:createUser·p1.00    sample         26.804           ms/op
ClientSimple.existUser                      sample  14194   2.250 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.901           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.027           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.415           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.284           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.513           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.533           ms/op
ClientSimple.getUser                        sample  13820   2.317 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.683           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.995           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.588           ms/op
ClientSimple.getUser:getUser·p0.99          sample          6.044           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.691           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.855           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.855           ms/op
ClientSimple.listUser                       sample   8354   3.830 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.118           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.785           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.694           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.063           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.497           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.625           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.893           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.893           ms/op

Benchmark result is saved to 1722363153639.json
