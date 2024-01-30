# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.676 ops/ms
Iteration   1: 6.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.344 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 6.854 ops/ms
Iteration   1: 11.711 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.711 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ops/ms
Iteration   1: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.088 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.191 ops/ms
Iteration   1: 3.667 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.667 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.060 ms/op
Iteration   1: 3.079 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.235 ±(99.9%) 0.040 ms/op
Iteration   1: 1.949 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.949 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ±(99.9%) 0.068 ms/op
Iteration   1: 3.142 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.142 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.583 ±(99.9%) 0.215 ms/op
Iteration   1: 9.282 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.282 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ±(99.9%) 0.106 ms/op
Iteration   1: 3.031 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.198 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   6.110 ms/op
                 createUser·p0.999:  8.528 ms/op
                 createUser·p0.9999: 9.864 ms/op
                 createUser·p1.00:   9.896 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10615
  mean =      3.031 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 28 
    [ 1.500,  2.000) = 140 
    [ 2.000,  2.500) = 1102 
    [ 2.500,  3.000) = 4691 
    [ 3.000,  3.500) = 3388 
    [ 3.500,  4.000) = 701 
    [ 4.000,  4.500) = 289 
    [ 4.500,  5.000) = 100 
    [ 5.000,  5.500) = 25 
    [ 5.500,  6.000) = 39 
    [ 6.000,  6.500) = 42 
    [ 6.500,  7.000) = 13 
    [ 7.000,  7.500) = 6 
    [ 7.500,  8.000) = 35 
    [ 8.000,  8.500) = 6 
    [ 8.500,  9.000) = 5 
    [ 9.000,  9.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.110 ms/op
     p(99.9000) =      8.528 ms/op
     p(99.9900) =      9.864 ms/op
     p(99.9990) =      9.896 ms/op
     p(99.9999) =      9.896 ms/op
    p(100.0000) =      9.896 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.075 ±(99.9%) 0.063 ms/op
Iteration   1: 1.832 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   1.772 ms/op
                 existUser·p0.90:   2.241 ms/op
                 existUser·p0.95:   2.421 ms/op
                 existUser·p0.99:   2.830 ms/op
                 existUser·p0.999:  14.221 ms/op
                 existUser·p0.9999: 14.426 ms/op
                 existUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17499
  mean =      1.832 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 786 
    [ 1.250,  2.500) = 16119 
    [ 2.500,  3.750) = 478 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 39 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.241 ms/op
     p(95.0000) =      2.421 ms/op
     p(99.0000) =      2.830 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     14.426 ms/op
     p(99.9990) =     14.598 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.476 ±(99.9%) 0.107 ms/op
Iteration   1: 2.910 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   2.777 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.016 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 10.633 ms/op
                 getUser·p1.00:   10.633 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10988
  mean =      2.910 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 201 
    [ 2.000,  3.000) = 6625 
    [ 3.000,  4.000) = 3598 
    [ 4.000,  5.000) = 416 
    [ 5.000,  6.000) = 76 
    [ 6.000,  7.000) = 6 
    [ 7.000,  8.000) = 34 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.016 ms/op
     p(99.0000) =      5.218 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     10.633 ms/op
     p(99.9990) =     10.633 ms/op
     p(99.9999) =     10.633 ms/op
    p(100.0000) =     10.633 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.984 ±(99.9%) 0.446 ms/op
Iteration   1: 9.613 ±(99.9%) 0.254 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   8.929 ms/op
                 listUser·p0.90:   12.743 ms/op
                 listUser·p0.95:   13.992 ms/op
                 listUser·p0.99:   30.322 ms/op
                 listUser·p0.999:  60.952 ms/op
                 listUser·p0.9999: 64.815 ms/op
                 listUser·p1.00:   64.815 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3331
  mean =      9.613 ±(99.9%) 0.254 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 57 
    [ 5.000, 10.000) = 2221 
    [10.000, 15.000) = 937 
    [15.000, 20.000) = 73 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 6 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 16 
    [45.000, 50.000) = 3 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      8.929 ms/op
     p(90.0000) =     12.743 ms/op
     p(95.0000) =     13.992 ms/op
     p(99.0000) =     30.322 ms/op
     p(99.9000) =     60.952 ms/op
     p(99.9900) =     64.815 ms/op
     p(99.9990) =     64.815 ms/op
     p(99.9999) =     64.815 ms/op
    p(100.0000) =     64.815 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.344          ops/ms
Client.existUser                       thrpt         11.711          ops/ms
Client.getUser                         thrpt          8.088          ops/ms
Client.listUser                        thrpt          3.667          ops/ms
Client.createUser                       avgt          3.079           ms/op
Client.existUser                        avgt          1.949           ms/op
Client.getUser                          avgt          3.142           ms/op
Client.listUser                         avgt          9.282           ms/op
Client.createUser                     sample  10615   3.031 ± 0.022   ms/op
Client.createUser:createUser·p0.00    sample          1.198           ms/op
Client.createUser:createUser·p0.50    sample          2.916           ms/op
Client.createUser:createUser·p0.90    sample          3.584           ms/op
Client.createUser:createUser·p0.95    sample          4.039           ms/op
Client.createUser:createUser·p0.99    sample          6.110           ms/op
Client.createUser:createUser·p0.999   sample          8.528           ms/op
Client.createUser:createUser·p0.9999  sample          9.864           ms/op
Client.createUser:createUser·p1.00    sample          9.896           ms/op
Client.existUser                      sample  17499   1.832 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.655           ms/op
Client.existUser:existUser·p0.50      sample          1.772           ms/op
Client.existUser:existUser·p0.90      sample          2.241           ms/op
Client.existUser:existUser·p0.95      sample          2.421           ms/op
Client.existUser:existUser·p0.99      sample          2.830           ms/op
Client.existUser:existUser·p0.999     sample         14.221           ms/op
Client.existUser:existUser·p0.9999    sample         14.426           ms/op
Client.existUser:existUser·p1.00      sample         14.598           ms/op
Client.getUser                        sample  10988   2.910 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.137           ms/op
Client.getUser:getUser·p0.50          sample          2.777           ms/op
Client.getUser:getUser·p0.90          sample          3.699           ms/op
Client.getUser:getUser·p0.95          sample          4.016           ms/op
Client.getUser:getUser·p0.99          sample          5.218           ms/op
Client.getUser:getUser·p0.999         sample         10.125           ms/op
Client.getUser:getUser·p0.9999        sample         10.633           ms/op
Client.getUser:getUser·p1.00          sample         10.633           ms/op
Client.listUser                       sample   3331   9.613 ± 0.254   ms/op
Client.listUser:listUser·p0.00        sample          2.253           ms/op
Client.listUser:listUser·p0.50        sample          8.929           ms/op
Client.listUser:listUser·p0.90        sample         12.743           ms/op
Client.listUser:listUser·p0.95        sample         13.992           ms/op
Client.listUser:listUser·p0.99        sample         30.322           ms/op
Client.listUser:listUser·p0.999       sample         60.952           ms/op
Client.listUser:listUser·p0.9999      sample         64.815           ms/op
Client.listUser:listUser·p1.00        sample         64.815           ms/op
