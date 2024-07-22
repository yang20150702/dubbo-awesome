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
# Warmup Iteration   1: 1.121 ops/ms
Iteration   1: 6.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.549 ops/ms


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
# Warmup Iteration   1: 5.986 ops/ms
Iteration   1: 12.964 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.964 ops/ms


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
# Warmup Iteration   1: 6.541 ops/ms
Iteration   1: 14.280 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.280 ops/ms


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
# Warmup Iteration   1: 6.256 ops/ms
Iteration   1: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.346 ops/ms


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
# Warmup Iteration   1: 4.793 ±(99.9%) 0.143 ms/op
Iteration   1: 2.131 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.131 ms/op


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
# Warmup Iteration   1: 3.505 ±(99.9%) 0.059 ms/op
Iteration   1: 1.940 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.940 ms/op


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
# Warmup Iteration   1: 3.570 ±(99.9%) 0.072 ms/op
Iteration   1: 1.970 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.970 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.094 ms/op
Iteration   1: 3.884 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.884 ms/op


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
# Warmup Iteration   1: 3.499 ±(99.9%) 0.095 ms/op
Iteration   1: 2.207 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.066 ms/op
                 createUser·p0.90:   2.571 ms/op
                 createUser·p0.95:   2.789 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  20.349 ms/op
                 createUser·p0.9999: 21.642 ms/op
                 createUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14513
  mean =      2.207 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12581 
    [ 2.500,  5.000) = 1721 
    [ 5.000,  7.500) = 81 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.066 ms/op
     p(90.0000) =      2.571 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     20.349 ms/op
     p(99.9900) =     21.642 ms/op
     p(99.9990) =     22.086 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 3.051 ±(99.9%) 0.072 ms/op
Iteration   1: 1.768 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   1.677 ms/op
                 existUser·p0.90:   1.987 ms/op
                 existUser·p0.95:   2.205 ms/op
                 existUser·p0.99:   2.683 ms/op
                 existUser·p0.999:  25.181 ms/op
                 existUser·p0.9999: 25.877 ms/op
                 existUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18090
  mean =      1.768 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17783 
    [ 2.500,  5.000) = 240 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      1.677 ms/op
     p(90.0000) =      1.987 ms/op
     p(95.0000) =      2.205 ms/op
     p(99.0000) =      2.683 ms/op
     p(99.9000) =     25.181 ms/op
     p(99.9900) =     25.877 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 3.265 ±(99.9%) 0.102 ms/op
Iteration   1: 1.864 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   1.714 ms/op
                 getUser·p0.90:   2.351 ms/op
                 getUser·p0.95:   2.580 ms/op
                 getUser·p0.99:   3.408 ms/op
                 getUser·p0.999:  17.990 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17148
  mean =      1.864 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 15822 
    [ 2.500,  3.750) = 1013 
    [ 3.750,  5.000) = 43 
    [ 5.000,  6.250) = 8 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      1.714 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      3.408 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.144 ms/op
Iteration   1: 3.623 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.253 ms/op
                 listUser·p0.50:   3.539 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   4.987 ms/op
                 listUser·p0.99:   6.357 ms/op
                 listUser·p0.999:  7.027 ms/op
                 listUser·p0.9999: 10.781 ms/op
                 listUser·p1.00:   10.781 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8844
  mean =      3.623 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 47 
    [ 2.000,  3.000) = 1691 
    [ 3.000,  4.000) = 4841 
    [ 4.000,  5.000) = 1842 
    [ 5.000,  6.000) = 270 
    [ 6.000,  7.000) = 144 
    [ 7.000,  8.000) = 6 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.987 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =      7.027 ms/op
     p(99.9900) =     10.781 ms/op
     p(99.9990) =     10.781 ms/op
     p(99.9999) =     10.781 ms/op
    p(100.0000) =     10.781 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.549          ops/ms
ClientSimple.existUser                       thrpt         12.964          ops/ms
ClientSimple.getUser                         thrpt         14.280          ops/ms
ClientSimple.listUser                        thrpt          8.346          ops/ms
ClientSimple.createUser                       avgt          2.131           ms/op
ClientSimple.existUser                        avgt          1.940           ms/op
ClientSimple.getUser                          avgt          1.970           ms/op
ClientSimple.listUser                         avgt          3.884           ms/op
ClientSimple.createUser                     sample  14513   2.207 ± 0.035   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.656           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.066           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.571           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.789           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.939           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.349           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.642           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.086           ms/op
ClientSimple.existUser                      sample  18090   1.768 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.624           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.677           ms/op
ClientSimple.existUser:existUser·p0.90      sample          1.987           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.205           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.999     sample         25.181           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.877           ms/op
ClientSimple.existUser:existUser·p1.00      sample         26.116           ms/op
ClientSimple.getUser                        sample  17148   1.864 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.708           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.714           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.351           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.580           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.408           ms/op
ClientSimple.getUser:getUser·p0.999         sample         17.990           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         18.350           ms/op
ClientSimple.getUser:getUser·p1.00          sample         18.350           ms/op
ClientSimple.listUser                       sample   8844   3.623 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.253           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.539           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.555           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.987           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.357           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.027           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.781           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.781           ms/op

Benchmark result is saved to 1721671951060.json
