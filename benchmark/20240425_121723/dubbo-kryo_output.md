# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.970 ops/ms
Iteration   1: 7.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.082 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.589 ops/ms
Iteration   1: 12.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.796 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.720 ops/ms
Iteration   1: 12.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.661 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.608 ops/ms
Iteration   1: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.489 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.752 ±(99.9%) 0.079 ms/op
Iteration   1: 2.163 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.163 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.368 ±(99.9%) 0.060 ms/op
Iteration   1: 1.876 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.467 ±(99.9%) 0.061 ms/op
Iteration   1: 2.281 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.398 ±(99.9%) 0.087 ms/op
Iteration   1: 3.460 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.453 ±(99.9%) 0.092 ms/op
Iteration   1: 2.185 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.019 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   2.979 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  14.877 ms/op
                 createUser·p0.9999: 18.770 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14635
  mean =      2.185 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 12217 
    [ 2.500,  3.750) = 1898 
    [ 3.750,  5.000) = 82 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 83 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      2.019 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      2.979 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     18.770 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.135 ±(99.9%) 0.098 ms/op
Iteration   1: 1.781 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.104 ms/op
                 existUser·p0.95:   2.318 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  19.297 ms/op
                 existUser·p0.9999: 19.851 ms/op
                 existUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18112
  mean =      1.781 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17588 
    [ 2.500,  5.000) = 369 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.104 ms/op
     p(95.0000) =      2.318 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =     19.297 ms/op
     p(99.9900) =     19.851 ms/op
     p(99.9990) =     20.808 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.290 ±(99.9%) 0.076 ms/op
Iteration   1: 1.800 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.446 ms/op
                 getUser·p0.50:   1.679 ms/op
                 getUser·p0.90:   2.306 ms/op
                 getUser·p0.95:   2.490 ms/op
                 getUser·p0.99:   2.843 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 18.838 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17788
  mean =      1.800 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 463 
    [ 1.250,  2.500) = 16476 
    [ 2.500,  3.750) = 802 
    [ 3.750,  5.000) = 15 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.306 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      2.843 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     18.838 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.516 ±(99.9%) 0.143 ms/op
Iteration   1: 3.543 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.497 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   6.347 ms/op
                 listUser·p0.999:  8.110 ms/op
                 listUser·p0.9999: 8.487 ms/op
                 listUser·p1.00:   8.487 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9026
  mean =      3.543 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 17 
    [1.500, 2.000) = 46 
    [2.000, 2.500) = 1749 
    [2.500, 3.000) = 1145 
    [3.000, 3.500) = 1230 
    [3.500, 4.000) = 1868 
    [4.000, 4.500) = 1646 
    [4.500, 5.000) = 774 
    [5.000, 5.500) = 350 
    [5.500, 6.000) = 62 
    [6.000, 6.500) = 88 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 10 
    [8.000, 8.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.347 ms/op
     p(99.9000) =      8.110 ms/op
     p(99.9900) =      8.487 ms/op
     p(99.9990) =      8.487 ms/op
     p(99.9999) =      8.487 ms/op
    p(100.0000) =      8.487 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.082          ops/ms
ClientSimple.existUser                       thrpt         12.796          ops/ms
ClientSimple.getUser                         thrpt         12.661          ops/ms
ClientSimple.listUser                        thrpt          8.489          ops/ms
ClientSimple.createUser                       avgt          2.163           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          2.281           ms/op
ClientSimple.listUser                         avgt          3.460           ms/op
ClientSimple.createUser                     sample  14635   2.185 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.785           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.019           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.979           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.602           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.877           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.770           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.907           ms/op
ClientSimple.existUser                      sample  18112   1.781 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.751           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.104           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.318           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.141           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.297           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.851           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.808           ms/op
ClientSimple.getUser                        sample  17788   1.800 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.446           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.679           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.306           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.490           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.843           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.547           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.838           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.940           ms/op
ClientSimple.listUser                       sample   9026   3.543 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.497           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.584           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.760           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.071           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.347           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.110           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.487           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.487           ms/op

Benchmark result is saved to 1714047207438.json
