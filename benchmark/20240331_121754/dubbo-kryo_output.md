# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.663 ops/ms
Iteration   1: 6.272 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.272 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.419 ops/ms
Iteration   1: 10.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.456 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.016 ops/ms
Iteration   1: 12.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.281 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.548 ops/ms
Iteration   1: 8.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.433 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.022 ±(99.9%) 0.084 ms/op
Iteration   1: 2.274 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.274 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ±(99.9%) 0.055 ms/op
Iteration   1: 1.882 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.882 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.366 ±(99.9%) 0.054 ms/op
Iteration   1: 1.907 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ±(99.9%) 0.155 ms/op
Iteration   1: 3.710 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.710 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.816 ±(99.9%) 0.096 ms/op
Iteration   1: 2.203 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.486 ms/op
                 createUser·p0.50:   2.060 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   2.863 ms/op
                 createUser·p0.99:   8.004 ms/op
                 createUser·p0.999:  15.212 ms/op
                 createUser·p0.9999: 16.681 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14519
  mean =      2.203 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 12114 
    [ 2.500,  3.750) = 1814 
    [ 3.750,  5.000) = 67 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.486 ms/op
     p(50.0000) =      2.060 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.863 ms/op
     p(99.0000) =      8.004 ms/op
     p(99.9000) =     15.212 ms/op
     p(99.9900) =     16.681 ms/op
     p(99.9990) =     16.777 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.228 ±(99.9%) 0.072 ms/op
Iteration   1: 2.124 ±(99.9%) 0.065 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.552 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  47.504 ms/op
                 existUser·p0.9999: 48.987 ms/op
                 existUser·p1.00:   49.021 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15146
  mean =      2.124 ±(99.9%) 0.065 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14948 
    [ 5.000, 10.000) = 102 
    [10.000, 15.000) = 32 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 32 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.552 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     47.504 ms/op
     p(99.9900) =     48.987 ms/op
     p(99.9990) =     49.021 ms/op
     p(99.9999) =     49.021 ms/op
    p(100.0000) =     49.021 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.544 ±(99.9%) 0.093 ms/op
Iteration   1: 2.117 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   2.007 ms/op
                 getUser·p0.90:   2.642 ms/op
                 getUser·p0.95:   2.851 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  13.187 ms/op
                 getUser·p0.9999: 13.829 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15102
  mean =      2.117 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 12361 
    [ 2.500,  3.750) = 2403 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 86 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      2.007 ms/op
     p(90.0000) =      2.642 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =     13.187 ms/op
     p(99.9900) =     13.829 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.815 ±(99.9%) 0.144 ms/op
Iteration   1: 3.845 ±(99.9%) 0.057 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   8.380 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8361
  mean =      3.845 ±(99.9%) 0.057 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 494 
    [ 2.500,  3.750) = 3674 
    [ 3.750,  5.000) = 3654 
    [ 5.000,  6.250) = 288 
    [ 6.250,  7.500) = 127 
    [ 7.500,  8.750) = 43 
    [ 8.750, 10.000) = 9 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.272          ops/ms
ClientSimple.existUser                       thrpt         10.456          ops/ms
ClientSimple.getUser                         thrpt         12.281          ops/ms
ClientSimple.listUser                        thrpt          8.433          ops/ms
ClientSimple.createUser                       avgt          2.274           ms/op
ClientSimple.existUser                        avgt          1.882           ms/op
ClientSimple.getUser                          avgt          1.907           ms/op
ClientSimple.listUser                         avgt          3.710           ms/op
ClientSimple.createUser                     sample  14519   2.203 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.486           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.060           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.863           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.004           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.212           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.681           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.777           ms/op
ClientSimple.existUser                      sample  15146   2.124 ± 0.065   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.642           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.892           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.552           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.822           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.964           ms/op
ClientSimple.existUser:existUser·p0.999     sample         47.504           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         48.987           ms/op
ClientSimple.existUser:existUser·p1.00      sample         49.021           ms/op
ClientSimple.getUser                        sample  15102   2.117 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.626           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.007           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.851           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.358           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.187           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.829           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.205           ms/op
ClientSimple.listUser                       sample   8361   3.845 ± 0.057   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.092           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.752           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.719           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.226           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.380           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.202           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.562           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.562           ms/op

Benchmark result is saved to 1711887232098.json
