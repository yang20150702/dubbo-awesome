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
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 6.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.698 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.570 ops/ms
Iteration   1: 13.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.500 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.666 ops/ms
Iteration   1: 10.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.884 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ops/ms
Iteration   1: 9.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.191 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.084 ms/op
Iteration   1: 2.214 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.214 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.070 ms/op
Iteration   1: 1.865 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.865 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.336 ±(99.9%) 0.055 ms/op
Iteration   1: 2.050 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.050 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.475 ±(99.9%) 0.096 ms/op
Iteration   1: 3.907 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.907 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.628 ±(99.9%) 0.100 ms/op
Iteration   1: 2.410 ±(99.9%) 0.069 ms/op
                 createUser·p0.00:   0.596 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.941 ms/op
                 createUser·p0.95:   3.446 ms/op
                 createUser·p0.99:   12.534 ms/op
                 createUser·p0.999:  38.142 ms/op
                 createUser·p0.9999: 40.220 ms/op
                 createUser·p1.00:   40.370 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13274
  mean =      2.410 ±(99.9%) 0.069 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 12914 
    [ 5.000, 10.000) = 138 
    [10.000, 15.000) = 134 
    [15.000, 20.000) = 24 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.446 ms/op
     p(99.0000) =     12.534 ms/op
     p(99.9000) =     38.142 ms/op
     p(99.9900) =     40.220 ms/op
     p(99.9990) =     40.370 ms/op
     p(99.9999) =     40.370 ms/op
    p(100.0000) =     40.370 ms/op


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
# Warmup Iteration   1: 3.230 ±(99.9%) 0.077 ms/op
Iteration   1: 1.994 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.754 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.621 ms/op
                 existUser·p0.99:   3.281 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 14.326 ms/op
                 existUser·p1.00:   14.336 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16087
  mean =      1.994 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 214 
    [ 1.250,  2.500) = 14452 
    [ 2.500,  3.750) = 1313 
    [ 3.750,  5.000) = 8 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.621 ms/op
     p(99.0000) =      3.281 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     14.326 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.336 ms/op
    p(100.0000) =     14.336 ms/op


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
# Warmup Iteration   1: 3.296 ±(99.9%) 0.078 ms/op
Iteration   1: 2.062 ±(99.9%) 0.040 ms/op
                 getUser·p0.00:   0.610 ms/op
                 getUser·p0.50:   1.806 ms/op
                 getUser·p0.90:   2.639 ms/op
                 getUser·p0.95:   2.925 ms/op
                 getUser·p0.99:   4.751 ms/op
                 getUser·p0.999:  30.212 ms/op
                 getUser·p0.9999: 30.766 ms/op
                 getUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15506
  mean =      2.062 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13527 
    [ 2.500,  5.000) = 1842 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.610 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.639 ms/op
     p(95.0000) =      2.925 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =     30.212 ms/op
     p(99.9900) =     30.766 ms/op
     p(99.9990) =     30.802 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


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
# Warmup Iteration   1: 4.691 ±(99.9%) 0.146 ms/op
Iteration   1: 3.110 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.211 ms/op
                 listUser·p0.999:  7.398 ms/op
                 listUser·p0.9999: 8.730 ms/op
                 listUser·p1.00:   8.765 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10290
  mean =      3.110 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 3 
    [1.000, 1.500) = 58 
    [1.500, 2.000) = 292 
    [2.000, 2.500) = 838 
    [2.500, 3.000) = 4428 
    [3.000, 3.500) = 2516 
    [3.500, 4.000) = 1069 
    [4.000, 4.500) = 540 
    [4.500, 5.000) = 406 
    [5.000, 5.500) = 63 
    [5.500, 6.000) = 45 
    [6.000, 6.500) = 6 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 21 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.211 ms/op
     p(99.9000) =      7.398 ms/op
     p(99.9900) =      8.730 ms/op
     p(99.9990) =      8.765 ms/op
     p(99.9999) =      8.765 ms/op
    p(100.0000) =      8.765 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.698          ops/ms
ClientSimple.existUser                       thrpt         13.500          ops/ms
ClientSimple.getUser                         thrpt         10.884          ops/ms
ClientSimple.listUser                        thrpt          9.191          ops/ms
ClientSimple.createUser                       avgt          2.214           ms/op
ClientSimple.existUser                        avgt          1.865           ms/op
ClientSimple.getUser                          avgt          2.050           ms/op
ClientSimple.listUser                         avgt          3.907           ms/op
ClientSimple.createUser                     sample  13274   2.410 ± 0.069   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.596           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.941           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.446           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.534           ms/op
ClientSimple.createUser:createUser·p0.999   sample         38.142           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         40.220           ms/op
ClientSimple.createUser:createUser·p1.00    sample         40.370           ms/op
ClientSimple.existUser                      sample  16087   1.994 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.754           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.880           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.621           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.281           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.238           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.326           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.336           ms/op
ClientSimple.getUser                        sample  15506   2.062 ± 0.040   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.610           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.806           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.639           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.925           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.751           ms/op
ClientSimple.getUser:getUser·p0.999         sample         30.212           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         30.766           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.802           ms/op
ClientSimple.listUser                       sample  10290   3.110 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.930           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.966           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.035           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.211           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.398           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.730           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.765           ms/op

Benchmark result is saved to 1716898568636.json
