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
# Warmup Iteration   1: 1.725 ops/ms
Iteration   1: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.759 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.024 ops/ms
Iteration   1: 13.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.795 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.734 ops/ms
Iteration   1: 15.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  15.378 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.658 ops/ms
Iteration   1: 9.294 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.294 ops/ms


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.098 ms/op
Iteration   1: 2.041 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.041 ms/op


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
# Warmup Iteration   1: 3.543 ±(99.9%) 0.063 ms/op
Iteration   1: 1.861 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 3.352 ±(99.9%) 0.060 ms/op
Iteration   1: 1.953 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.953 ms/op


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.087 ms/op
Iteration   1: 3.651 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.651 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.834 ±(99.9%) 0.116 ms/op
Iteration   1: 2.308 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   2.245 ms/op
                 createUser·p0.90:   2.810 ms/op
                 createUser·p0.95:   3.016 ms/op
                 createUser·p0.99:   4.911 ms/op
                 createUser·p0.999:  12.550 ms/op
                 createUser·p0.9999: 12.668 ms/op
                 createUser·p1.00:   12.681 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13934
  mean =      2.308 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 207 
    [ 1.250,  2.500) = 9766 
    [ 2.500,  3.750) = 3697 
    [ 3.750,  5.000) = 127 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.245 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.016 ms/op
     p(99.0000) =      4.911 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     12.668 ms/op
     p(99.9990) =     12.681 ms/op
     p(99.9999) =     12.681 ms/op
    p(100.0000) =     12.681 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.084 ms/op
Iteration   1: 2.092 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   1.958 ms/op
                 existUser·p0.90:   2.601 ms/op
                 existUser·p0.95:   2.781 ms/op
                 existUser·p0.99:   5.120 ms/op
                 existUser·p0.999:  21.838 ms/op
                 existUser·p0.9999: 23.158 ms/op
                 existUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15280
  mean =      2.092 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13123 
    [ 2.500,  5.000) = 1999 
    [ 5.000,  7.500) = 59 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      1.958 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     21.838 ms/op
     p(99.9900) =     23.158 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.636 ±(99.9%) 0.111 ms/op
Iteration   1: 2.029 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.678 ms/op
                 getUser·p0.50:   1.868 ms/op
                 getUser·p0.90:   2.531 ms/op
                 getUser·p0.95:   2.790 ms/op
                 getUser·p0.99:   3.614 ms/op
                 getUser·p0.999:  13.152 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15755
  mean =      2.029 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 39 
    [ 1.250,  2.500) = 13999 
    [ 2.500,  3.750) = 1573 
    [ 3.750,  5.000) = 57 
    [ 5.000,  6.250) = 55 
    [ 6.250,  7.500) = 0 
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
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      1.868 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.790 ms/op
     p(99.0000) =      3.614 ms/op
     p(99.9000) =     13.152 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 4.595 ±(99.9%) 0.127 ms/op
Iteration   1: 3.567 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  10.142 ms/op
                 listUser·p0.9999: 10.568 ms/op
                 listUser·p1.00:   10.568 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8988
  mean =      3.567 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 113 
    [ 2.000,  3.000) = 1663 
    [ 3.000,  4.000) = 5440 
    [ 4.000,  5.000) = 1505 
    [ 5.000,  6.000) = 101 
    [ 6.000,  7.000) = 85 
    [ 7.000,  8.000) = 18 
    [ 8.000,  9.000) = 22 
    [ 9.000, 10.000) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     10.142 ms/op
     p(99.9900) =     10.568 ms/op
     p(99.9990) =     10.568 ms/op
     p(99.9999) =     10.568 ms/op
    p(100.0000) =     10.568 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.759          ops/ms
ClientSimple.existUser                       thrpt         13.795          ops/ms
ClientSimple.getUser                         thrpt         15.378          ops/ms
ClientSimple.listUser                        thrpt          9.294          ops/ms
ClientSimple.createUser                       avgt          2.041           ms/op
ClientSimple.existUser                        avgt          1.861           ms/op
ClientSimple.getUser                          avgt          1.953           ms/op
ClientSimple.listUser                         avgt          3.651           ms/op
ClientSimple.createUser                     sample  13934   2.308 ± 0.022   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.501           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.245           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.016           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.911           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.550           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.668           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.681           ms/op
ClientSimple.existUser                      sample  15280   2.092 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.674           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.958           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.781           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.120           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.838           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.158           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.626           ms/op
ClientSimple.getUser                        sample  15755   2.029 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.678           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.868           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.531           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.790           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.614           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.152           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.435           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample   8988   3.567 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.141           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.857           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.142           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.568           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.568           ms/op

Benchmark result is saved to 1710722276102.json
