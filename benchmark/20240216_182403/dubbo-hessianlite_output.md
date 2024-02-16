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
# Warmup Iteration   1: 2.615 ops/ms
Iteration   1: 6.134 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.134 ops/ms


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
# Warmup Iteration   1: 7.107 ops/ms
Iteration   1: 13.562 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.562 ops/ms


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
# Warmup Iteration   1: 4.537 ops/ms
Iteration   1: 9.012 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.012 ops/ms


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
# Warmup Iteration   1: 2.102 ops/ms
Iteration   1: 3.156 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.156 ops/ms


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
# Warmup Iteration   1: 5.483 ±(99.9%) 0.100 ms/op
Iteration   1: 3.332 ±(99.9%) 0.050 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.332 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.035 ms/op
Iteration   1: 1.851 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.851 ms/op


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.054 ms/op
Iteration   1: 3.293 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.293 ms/op


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
# Warmup Iteration   1: 12.348 ±(99.9%) 0.200 ms/op
Iteration   1: 8.664 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.664 ms/op


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
# Warmup Iteration   1: 4.889 ±(99.9%) 0.120 ms/op
Iteration   1: 3.119 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.950 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.858 ms/op
                 createUser·p0.999:  10.614 ms/op
                 createUser·p0.9999: 11.695 ms/op
                 createUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10396
  mean =      3.119 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1870 
    [ 2.500,  3.750) = 6818 
    [ 3.750,  5.000) = 1532 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.950 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.858 ms/op
     p(99.9000) =     10.614 ms/op
     p(99.9900) =     11.695 ms/op
     p(99.9990) =     11.698 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


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
# Warmup Iteration   1: 2.963 ±(99.9%) 0.078 ms/op
Iteration   1: 2.044 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.535 ms/op
                 existUser·p0.95:   2.750 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  24.718 ms/op
                 existUser·p0.9999: 25.587 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15669
  mean =      2.044 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13817 
    [ 2.500,  5.000) = 1757 
    [ 5.000,  7.500) = 54 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.750 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     24.718 ms/op
     p(99.9900) =     25.587 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.106 ms/op
Iteration   1: 3.301 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.204 ms/op
                 getUser·p0.50:   3.115 ms/op
                 getUser·p0.90:   4.127 ms/op
                 getUser·p0.95:   4.635 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  9.494 ms/op
                 getUser·p0.9999: 9.830 ms/op
                 getUser·p1.00:   9.830 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9704
  mean =      3.301 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 16 
    [ 1.500,  2.000) = 39 
    [ 2.000,  2.500) = 498 
    [ 2.500,  3.000) = 3637 
    [ 3.000,  3.500) = 2358 
    [ 3.500,  4.000) = 1933 
    [ 4.000,  4.500) = 675 
    [ 4.500,  5.000) = 274 
    [ 5.000,  5.500) = 88 
    [ 5.500,  6.000) = 73 
    [ 6.000,  6.500) = 39 
    [ 6.500,  7.000) = 37 
    [ 7.000,  7.500) = 7 
    [ 7.500,  8.000) = 7 
    [ 8.000,  8.500) = 7 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.204 ms/op
     p(50.0000) =      3.115 ms/op
     p(90.0000) =      4.127 ms/op
     p(95.0000) =      4.635 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =      9.494 ms/op
     p(99.9900) =      9.830 ms/op
     p(99.9990) =      9.830 ms/op
     p(99.9999) =      9.830 ms/op
    p(100.0000) =      9.830 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.432 ±(99.9%) 0.500 ms/op
Iteration   1: 8.907 ±(99.9%) 0.133 ms/op
                 listUser·p0.00:   3.478 ms/op
                 listUser·p0.50:   8.405 ms/op
                 listUser·p0.90:   11.762 ms/op
                 listUser·p0.95:   13.131 ms/op
                 listUser·p0.99:   19.236 ms/op
                 listUser·p0.999:  21.987 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3570
  mean =      8.907 ±(99.9%) 0.133 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 50 
    [ 5.000,  7.500) = 930 
    [ 7.500, 10.000) = 1682 
    [10.000, 12.500) = 684 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.478 ms/op
     p(50.0000) =      8.405 ms/op
     p(90.0000) =     11.762 ms/op
     p(95.0000) =     13.131 ms/op
     p(99.0000) =     19.236 ms/op
     p(99.9000) =     21.987 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.134          ops/ms
Client.existUser                       thrpt         13.562          ops/ms
Client.getUser                         thrpt          9.012          ops/ms
Client.listUser                        thrpt          3.156          ops/ms
Client.createUser                       avgt          3.332           ms/op
Client.existUser                        avgt          1.851           ms/op
Client.getUser                          avgt          3.293           ms/op
Client.listUser                         avgt          8.664           ms/op
Client.createUser                     sample  10396   3.119 ± 0.026   ms/op
Client.createUser:createUser·p0.00    sample          1.104           ms/op
Client.createUser:createUser·p0.50    sample          2.986           ms/op
Client.createUser:createUser·p0.90    sample          3.950           ms/op
Client.createUser:createUser·p0.95    sample          4.211           ms/op
Client.createUser:createUser·p0.99    sample          5.858           ms/op
Client.createUser:createUser·p0.999   sample         10.614           ms/op
Client.createUser:createUser·p0.9999  sample         11.695           ms/op
Client.createUser:createUser·p1.00    sample         11.698           ms/op
Client.existUser                      sample  15669   2.044 ± 0.031   ms/op
Client.existUser:existUser·p0.00      sample          0.679           ms/op
Client.existUser:existUser·p0.50      sample          1.880           ms/op
Client.existUser:existUser·p0.90      sample          2.535           ms/op
Client.existUser:existUser·p0.95      sample          2.750           ms/op
Client.existUser:existUser·p0.99      sample          4.604           ms/op
Client.existUser:existUser·p0.999     sample         24.718           ms/op
Client.existUser:existUser·p0.9999    sample         25.587           ms/op
Client.existUser:existUser·p1.00      sample         25.625           ms/op
Client.getUser                        sample   9704   3.301 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          1.204           ms/op
Client.getUser:getUser·p0.50          sample          3.115           ms/op
Client.getUser:getUser·p0.90          sample          4.127           ms/op
Client.getUser:getUser·p0.95          sample          4.635           ms/op
Client.getUser:getUser·p0.99          sample          6.111           ms/op
Client.getUser:getUser·p0.999         sample          9.494           ms/op
Client.getUser:getUser·p0.9999        sample          9.830           ms/op
Client.getUser:getUser·p1.00          sample          9.830           ms/op
Client.listUser                       sample   3570   8.907 ± 0.133   ms/op
Client.listUser:listUser·p0.00        sample          3.478           ms/op
Client.listUser:listUser·p0.50        sample          8.405           ms/op
Client.listUser:listUser·p0.90        sample         11.762           ms/op
Client.listUser:listUser·p0.95        sample         13.131           ms/op
Client.listUser:listUser·p0.99        sample         19.236           ms/op
Client.listUser:listUser·p0.999       sample         21.987           ms/op
Client.listUser:listUser·p0.9999      sample         23.462           ms/op
Client.listUser:listUser·p1.00        sample         23.462           ms/op
