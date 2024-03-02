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
# Warmup Iteration   1: 2.334 ops/ms
Iteration   1: 6.309 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.309 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ops/ms
Iteration   1: 13.739 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.739 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.261 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.864 ops/ms
Iteration   1: 3.593 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.593 ops/ms


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
# Warmup Iteration   1: 5.491 ±(99.9%) 0.096 ms/op
Iteration   1: 3.111 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.111 ms/op


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
# Warmup Iteration   1: 3.389 ±(99.9%) 0.037 ms/op
Iteration   1: 1.828 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.828 ms/op


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
# Warmup Iteration   1: 4.452 ±(99.9%) 0.051 ms/op
Iteration   1: 2.954 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.954 ms/op


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
# Warmup Iteration   1: 12.884 ±(99.9%) 0.276 ms/op
Iteration   1: 8.025 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.025 ms/op


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
# Warmup Iteration   1: 4.887 ±(99.9%) 0.095 ms/op
Iteration   1: 3.076 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   2.877 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   7.469 ms/op
                 createUser·p0.999:  14.722 ms/op
                 createUser·p0.9999: 16.420 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10414
  mean =      3.076 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2080 
    [ 2.500,  3.750) = 7249 
    [ 3.750,  5.000) = 793 
    [ 5.000,  6.250) = 172 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      2.877 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      7.469 ms/op
     p(99.9000) =     14.722 ms/op
     p(99.9900) =     16.420 ms/op
     p(99.9990) =     16.433 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.087 ms/op
Iteration   1: 2.003 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   1.909 ms/op
                 existUser·p0.90:   2.576 ms/op
                 existUser·p0.95:   2.789 ms/op
                 existUser·p0.99:   4.229 ms/op
                 existUser·p0.999:  5.662 ms/op
                 existUser·p0.9999: 5.702 ms/op
                 existUser·p1.00:   5.702 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15944
  mean =      2.003 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 9 
    [1.000, 1.500) = 1575 
    [1.500, 2.000) = 7985 
    [2.000, 2.500) = 4456 
    [2.500, 3.000) = 1406 
    [3.000, 3.500) = 218 
    [3.500, 4.000) = 100 
    [4.000, 4.500) = 86 
    [4.500, 5.000) = 42 
    [5.000, 5.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      4.229 ms/op
     p(99.9000) =      5.662 ms/op
     p(99.9900) =      5.702 ms/op
     p(99.9990) =      5.702 ms/op
     p(99.9999) =      5.702 ms/op
    p(100.0000) =      5.702 ms/op


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
# Warmup Iteration   1: 4.531 ±(99.9%) 0.124 ms/op
Iteration   1: 2.911 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   5.202 ms/op
                 getUser·p0.999:  6.865 ms/op
                 getUser·p0.9999: 7.659 ms/op
                 getUser·p1.00:   7.660 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10996
  mean =      2.911 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 8 
    [1.000, 1.500) = 150 
    [1.500, 2.000) = 780 
    [2.000, 2.500) = 1847 
    [2.500, 3.000) = 3205 
    [3.000, 3.500) = 3454 
    [3.500, 4.000) = 1112 
    [4.000, 4.500) = 272 
    [4.500, 5.000) = 45 
    [5.000, 5.500) = 41 
    [5.500, 6.000) = 20 
    [6.000, 6.500) = 43 
    [6.500, 7.000) = 15 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      6.865 ms/op
     p(99.9900) =      7.659 ms/op
     p(99.9990) =      7.660 ms/op
     p(99.9999) =      7.660 ms/op
    p(100.0000) =      7.660 ms/op


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
# Warmup Iteration   1: 11.707 ±(99.9%) 0.418 ms/op
Iteration   1: 7.828 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   3.469 ms/op
                 listUser·p0.50:   7.479 ms/op
                 listUser·p0.90:   9.748 ms/op
                 listUser·p0.95:   11.045 ms/op
                 listUser·p0.99:   19.268 ms/op
                 listUser·p0.999:  26.023 ms/op
                 listUser·p0.9999: 28.639 ms/op
                 listUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4076
  mean =      7.828 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 99 
    [ 5.000,  7.500) = 1967 
    [ 7.500, 10.000) = 1665 
    [10.000, 12.500) = 221 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.469 ms/op
     p(50.0000) =      7.479 ms/op
     p(90.0000) =      9.748 ms/op
     p(95.0000) =     11.045 ms/op
     p(99.0000) =     19.268 ms/op
     p(99.9000) =     26.023 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.309          ops/ms
Client.existUser                       thrpt         13.739          ops/ms
Client.getUser                         thrpt          8.261          ops/ms
Client.listUser                        thrpt          3.593          ops/ms
Client.createUser                       avgt          3.111           ms/op
Client.existUser                        avgt          1.828           ms/op
Client.getUser                          avgt          2.954           ms/op
Client.listUser                         avgt          8.025           ms/op
Client.createUser                     sample  10414   3.076 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.268           ms/op
Client.createUser:createUser·p0.50    sample          2.877           ms/op
Client.createUser:createUser·p0.90    sample          3.772           ms/op
Client.createUser:createUser·p0.95    sample          4.293           ms/op
Client.createUser:createUser·p0.99    sample          7.469           ms/op
Client.createUser:createUser·p0.999   sample         14.722           ms/op
Client.createUser:createUser·p0.9999  sample         16.420           ms/op
Client.createUser:createUser·p1.00    sample         16.433           ms/op
Client.existUser                      sample  15944   2.003 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.769           ms/op
Client.existUser:existUser·p0.50      sample          1.909           ms/op
Client.existUser:existUser·p0.90      sample          2.576           ms/op
Client.existUser:existUser·p0.95      sample          2.789           ms/op
Client.existUser:existUser·p0.99      sample          4.229           ms/op
Client.existUser:existUser·p0.999     sample          5.662           ms/op
Client.existUser:existUser·p0.9999    sample          5.702           ms/op
Client.existUser:existUser·p1.00      sample          5.702           ms/op
Client.getUser                        sample  10996   2.911 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.805           ms/op
Client.getUser:getUser·p0.50          sample          2.941           ms/op
Client.getUser:getUser·p0.90          sample          3.645           ms/op
Client.getUser:getUser·p0.95          sample          3.908           ms/op
Client.getUser:getUser·p0.99          sample          5.202           ms/op
Client.getUser:getUser·p0.999         sample          6.865           ms/op
Client.getUser:getUser·p0.9999        sample          7.659           ms/op
Client.getUser:getUser·p1.00          sample          7.660           ms/op
Client.listUser                       sample   4076   7.828 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          3.469           ms/op
Client.listUser:listUser·p0.50        sample          7.479           ms/op
Client.listUser:listUser·p0.90        sample          9.748           ms/op
Client.listUser:listUser·p0.95        sample         11.045           ms/op
Client.listUser:listUser·p0.99        sample         19.268           ms/op
Client.listUser:listUser·p0.999       sample         26.023           ms/op
Client.listUser:listUser·p0.9999      sample         28.639           ms/op
Client.listUser:listUser·p1.00        sample         28.639           ms/op
