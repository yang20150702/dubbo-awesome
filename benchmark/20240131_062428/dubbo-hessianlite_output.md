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
# Warmup Iteration   1: 2.500 ops/ms
Iteration   1: 6.324 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.324 ops/ms


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
# Warmup Iteration   1: 5.320 ops/ms
Iteration   1: 15.110 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  15.110 ops/ms


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
# Warmup Iteration   1: 4.015 ops/ms
Iteration   1: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.484 ops/ms


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
# Warmup Iteration   1: 1.923 ops/ms
Iteration   1: 3.550 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.550 ops/ms


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.049 ms/op
Iteration   1: 2.947 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.947 ms/op


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
# Warmup Iteration   1: 3.116 ±(99.9%) 0.034 ms/op
Iteration   1: 1.713 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.713 ms/op


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
# Warmup Iteration   1: 4.599 ±(99.9%) 0.052 ms/op
Iteration   1: 2.963 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.963 ms/op


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
# Warmup Iteration   1: 11.604 ±(99.9%) 0.198 ms/op
Iteration   1: 8.621 ±(99.9%) 0.119 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.621 ms/op


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.105 ms/op
Iteration   1: 2.939 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.716 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   9.117 ms/op
                 createUser·p0.999:  19.137 ms/op
                 createUser·p0.9999: 19.586 ms/op
                 createUser·p1.00:   19.595 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10917
  mean =      2.939 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 2893 
    [ 2.500,  3.750) = 6990 
    [ 3.750,  5.000) = 817 
    [ 5.000,  6.250) = 57 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.944 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      9.117 ms/op
     p(99.9000) =     19.137 ms/op
     p(99.9900) =     19.586 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.080 ms/op
Iteration   1: 1.951 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.344 ms/op
                 existUser·p0.50:   1.878 ms/op
                 existUser·p0.90:   2.400 ms/op
                 existUser·p0.95:   2.560 ms/op
                 existUser·p0.99:   2.929 ms/op
                 existUser·p0.999:  5.654 ms/op
                 existUser·p0.9999: 5.827 ms/op
                 existUser·p1.00:   5.833 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16390
  mean =      1.951 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 6 
    [0.500, 1.000) = 43 
    [1.000, 1.500) = 572 
    [1.500, 2.000) = 10448 
    [2.000, 2.500) = 4234 
    [2.500, 3.000) = 965 
    [3.000, 3.500) = 72 
    [3.500, 4.000) = 6 
    [4.000, 4.500) = 8 
    [4.500, 5.000) = 1 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      1.878 ms/op
     p(90.0000) =      2.400 ms/op
     p(95.0000) =      2.560 ms/op
     p(99.0000) =      2.929 ms/op
     p(99.9000) =      5.654 ms/op
     p(99.9900) =      5.827 ms/op
     p(99.9990) =      5.833 ms/op
     p(99.9999) =      5.833 ms/op
    p(100.0000) =      5.833 ms/op


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
# Warmup Iteration   1: 4.683 ±(99.9%) 0.114 ms/op
Iteration   1: 2.855 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   2.646 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   5.399 ms/op
                 getUser·p0.999:  17.557 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11189
  mean =      2.855 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 4439 
    [ 2.500,  3.750) = 5683 
    [ 3.750,  5.000) = 867 
    [ 5.000,  6.250) = 133 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.399 ms/op
     p(99.9000) =     17.557 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 12.693 ±(99.9%) 0.507 ms/op
Iteration   1: 7.940 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   3.187 ms/op
                 listUser·p0.50:   7.528 ms/op
                 listUser·p0.90:   9.994 ms/op
                 listUser·p0.95:   11.190 ms/op
                 listUser·p0.99:   19.486 ms/op
                 listUser·p0.999:  24.543 ms/op
                 listUser·p0.9999: 26.608 ms/op
                 listUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4033
  mean =      7.940 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 69 
    [ 5.000,  7.500) = 1919 
    [ 7.500, 10.000) = 1643 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.187 ms/op
     p(50.0000) =      7.528 ms/op
     p(90.0000) =      9.994 ms/op
     p(95.0000) =     11.190 ms/op
     p(99.0000) =     19.486 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     26.608 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


# Run complete. Total time: 00:01:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.324          ops/ms
Client.existUser                       thrpt         15.110          ops/ms
Client.getUser                         thrpt          8.484          ops/ms
Client.listUser                        thrpt          3.550          ops/ms
Client.createUser                       avgt          2.947           ms/op
Client.existUser                        avgt          1.713           ms/op
Client.getUser                          avgt          2.963           ms/op
Client.listUser                         avgt          8.621           ms/op
Client.createUser                     sample  10917   2.939 ± 0.041   ms/op
Client.createUser:createUser·p0.00    sample          0.944           ms/op
Client.createUser:createUser·p0.50    sample          2.716           ms/op
Client.createUser:createUser·p0.90    sample          3.695           ms/op
Client.createUser:createUser·p0.95    sample          4.092           ms/op
Client.createUser:createUser·p0.99    sample          9.117           ms/op
Client.createUser:createUser·p0.999   sample         19.137           ms/op
Client.createUser:createUser·p0.9999  sample         19.586           ms/op
Client.createUser:createUser·p1.00    sample         19.595           ms/op
Client.existUser                      sample  16390   1.951 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.344           ms/op
Client.existUser:existUser·p0.50      sample          1.878           ms/op
Client.existUser:existUser·p0.90      sample          2.400           ms/op
Client.existUser:existUser·p0.95      sample          2.560           ms/op
Client.existUser:existUser·p0.99      sample          2.929           ms/op
Client.existUser:existUser·p0.999     sample          5.654           ms/op
Client.existUser:existUser·p0.9999    sample          5.827           ms/op
Client.existUser:existUser·p1.00      sample          5.833           ms/op
Client.getUser                        sample  11189   2.855 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.575           ms/op
Client.getUser:getUser·p0.50          sample          2.646           ms/op
Client.getUser:getUser·p0.90          sample          3.711           ms/op
Client.getUser:getUser·p0.95          sample          4.080           ms/op
Client.getUser:getUser·p0.99          sample          5.399           ms/op
Client.getUser:getUser·p0.999         sample         17.557           ms/op
Client.getUser:getUser·p0.9999        sample         17.859           ms/op
Client.getUser:getUser·p1.00          sample         17.859           ms/op
Client.listUser                       sample   4033   7.940 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          3.187           ms/op
Client.listUser:listUser·p0.50        sample          7.528           ms/op
Client.listUser:listUser·p0.90        sample          9.994           ms/op
Client.listUser:listUser·p0.95        sample         11.190           ms/op
Client.listUser:listUser·p0.99        sample         19.486           ms/op
Client.listUser:listUser·p0.999       sample         24.543           ms/op
Client.listUser:listUser·p0.9999      sample         26.608           ms/op
Client.listUser:listUser·p1.00        sample         26.608           ms/op
