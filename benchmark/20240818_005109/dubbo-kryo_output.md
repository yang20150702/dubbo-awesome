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
# Warmup Iteration   1: 1.629 ops/ms
Iteration   1: 7.110 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.110 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.175 ops/ms
Iteration   1: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.998 ops/ms


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
# Warmup Iteration   1: 4.734 ops/ms
Iteration   1: 11.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.737 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.348 ops/ms
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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.472 ±(99.9%) 0.063 ms/op
Iteration   1: 2.351 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.351 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.245 ±(99.9%) 0.056 ms/op
Iteration   1: 1.749 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.749 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.124 ±(99.9%) 0.062 ms/op
Iteration   1: 1.840 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.840 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.280 ±(99.9%) 0.076 ms/op
Iteration   1: 3.514 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.514 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.680 ±(99.9%) 0.093 ms/op
Iteration   1: 2.342 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.068 ms/op
                 createUser·p0.90:   2.867 ms/op
                 createUser·p0.95:   3.482 ms/op
                 createUser·p0.99:   8.634 ms/op
                 createUser·p0.999:  19.431 ms/op
                 createUser·p0.9999: 20.501 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13656
  mean =      2.342 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10859 
    [ 2.500,  5.000) = 2377 
    [ 5.000,  7.500) = 249 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.068 ms/op
     p(90.0000) =      2.867 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     20.501 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ±(99.9%) 0.063 ms/op
Iteration   1: 2.002 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   1.890 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.740 ms/op
                 existUser·p0.99:   4.109 ms/op
                 existUser·p0.999:  13.877 ms/op
                 existUser·p0.9999: 15.011 ms/op
                 existUser·p1.00:   15.041 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15960
  mean =      2.002 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 379 
    [ 1.250,  2.500) = 13788 
    [ 2.500,  3.750) = 1586 
    [ 3.750,  5.000) = 92 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.615 ms/op
     p(50.0000) =      1.890 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.740 ms/op
     p(99.0000) =      4.109 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     15.011 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.041 ms/op
    p(100.0000) =     15.041 ms/op


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
# Warmup Iteration   1: 3.533 ±(99.9%) 0.122 ms/op
Iteration   1: 2.078 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   1.907 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.933 ms/op
                 getUser·p0.99:   3.527 ms/op
                 getUser·p0.999:  22.517 ms/op
                 getUser·p0.9999: 22.952 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15614
  mean =      2.078 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13947 
    [ 2.500,  5.000) = 1581 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      3.527 ms/op
     p(99.9000) =     22.517 ms/op
     p(99.9900) =     22.952 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 4.125 ±(99.9%) 0.102 ms/op
Iteration   1: 3.626 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   5.192 ms/op
                 listUser·p0.999:  24.089 ms/op
                 listUser·p0.9999: 24.510 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8859
  mean =      3.626 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 329 
    [ 2.500,  5.000) = 8419 
    [ 5.000,  7.500) = 78 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.192 ms/op
     p(99.9000) =     24.089 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     24.510 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.110          ops/ms
ClientSimple.existUser                       thrpt         12.998          ops/ms
ClientSimple.getUser                         thrpt         11.737          ops/ms
ClientSimple.listUser                        thrpt          8.128          ops/ms
ClientSimple.createUser                       avgt          2.351           ms/op
ClientSimple.existUser                        avgt          1.749           ms/op
ClientSimple.getUser                          avgt          1.840           ms/op
ClientSimple.listUser                         avgt          3.514           ms/op
ClientSimple.createUser                     sample  13656   2.342 ± 0.040   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.851           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.068           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.867           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.482           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.634           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.431           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.501           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.513           ms/op
ClientSimple.existUser                      sample  15960   2.002 ± 0.021   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.615           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.890           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.740           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.109           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.877           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.011           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.041           ms/op
ClientSimple.getUser                        sample  15614   2.078 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.729           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.907           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.933           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.527           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.517           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.952           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.970           ms/op
ClientSimple.listUser                       sample   8859   3.626 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.020           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.592           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.252           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.192           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.089           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.510           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.510           ms/op

Benchmark result is saved to 1723942016543.json
