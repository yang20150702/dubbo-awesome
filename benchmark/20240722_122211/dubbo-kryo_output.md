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
# Warmup Iteration   1: 1.725 ops/ms
Iteration   1: 6.375 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.375 ops/ms


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
# Warmup Iteration   1: 5.635 ops/ms
Iteration   1: 12.345 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.345 ops/ms


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
# Warmup Iteration   1: 5.179 ops/ms
Iteration   1: 11.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.986 ops/ms


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
# Warmup Iteration   1: 3.410 ops/ms
Iteration   1: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.128 ops/ms


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.066 ms/op
Iteration   1: 2.180 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.180 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.066 ms/op
Iteration   1: 2.018 ±(99.9%) 0.006 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.376 ±(99.9%) 0.068 ms/op
Iteration   1: 1.997 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.997 ms/op


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
# Warmup Iteration   1: 4.874 ±(99.9%) 0.126 ms/op
Iteration   1: 3.276 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.276 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.090 ms/op
Iteration   1: 2.263 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.658 ms/op
                 createUser·p0.50:   2.118 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   3.023 ms/op
                 createUser·p0.99:   5.190 ms/op
                 createUser·p0.999:  16.448 ms/op
                 createUser·p0.9999: 18.533 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14110
  mean =      2.263 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 11545 
    [ 2.500,  3.750) = 2269 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      2.118 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      3.023 ms/op
     p(99.0000) =      5.190 ms/op
     p(99.9000) =     16.448 ms/op
     p(99.9900) =     18.533 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.548 ±(99.9%) 0.099 ms/op
Iteration   1: 1.978 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   1.780 ms/op
                 existUser·p0.90:   2.638 ms/op
                 existUser·p0.95:   2.806 ms/op
                 existUser·p0.99:   4.410 ms/op
                 existUser·p0.999:  21.987 ms/op
                 existUser·p0.9999: 22.574 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16169
  mean =      1.978 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13552 
    [ 2.500,  5.000) = 2524 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.780 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      4.410 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     22.574 ms/op
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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.095 ms/op
Iteration   1: 2.065 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   1.911 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.900 ms/op
                 getUser·p0.99:   4.199 ms/op
                 getUser·p0.999:  12.239 ms/op
                 getUser·p0.9999: 12.327 ms/op
                 getUser·p1.00:   12.354 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15442
  mean =      2.065 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 13194 
    [ 2.500,  3.750) = 1867 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 100 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.911 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.900 ms/op
     p(99.0000) =      4.199 ms/op
     p(99.9000) =     12.239 ms/op
     p(99.9900) =     12.327 ms/op
     p(99.9990) =     12.354 ms/op
     p(99.9999) =     12.354 ms/op
    p(100.0000) =     12.354 ms/op


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
# Warmup Iteration   1: 4.679 ±(99.9%) 0.159 ms/op
Iteration   1: 3.242 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   6.459 ms/op
                 listUser·p0.999:  15.485 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9858
  mean =      3.242 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 427 
    [ 2.500,  3.750) = 7767 
    [ 3.750,  5.000) = 1271 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 66 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      6.459 ms/op
     p(99.9000) =     15.485 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     18.416 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.375          ops/ms
ClientSimple.existUser                       thrpt         12.345          ops/ms
ClientSimple.getUser                         thrpt         11.986          ops/ms
ClientSimple.listUser                        thrpt          8.128          ops/ms
ClientSimple.createUser                       avgt          2.180           ms/op
ClientSimple.existUser                        avgt          2.018           ms/op
ClientSimple.getUser                          avgt          1.997           ms/op
ClientSimple.listUser                         avgt          3.276           ms/op
ClientSimple.createUser                     sample  14110   2.263 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.658           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.118           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.023           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.190           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.448           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.533           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  16169   1.978 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.520           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.780           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.638           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.806           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.410           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.987           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.574           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.675           ms/op
ClientSimple.getUser                        sample  15442   2.065 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.599           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.911           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.900           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.199           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.327           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.354           ms/op
ClientSimple.listUser                       sample   9858   3.242 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.462           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.925           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.998           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.459           ms/op
ClientSimple.listUser:listUser·p0.999       sample         15.485           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         18.416           ms/op
ClientSimple.listUser:listUser·p1.00        sample         18.416           ms/op

Benchmark result is saved to 1721650676549.json
