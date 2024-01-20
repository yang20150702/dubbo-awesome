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
# Warmup Iteration   1: 2.122 ops/ms
Iteration   1: 6.632 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.632 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.903 ops/ms
Iteration   1: 13.397 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.397 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.811 ops/ms
Iteration   1: 9.917 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.917 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.700 ops/ms
Iteration   1: 2.998 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.998 ops/ms


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
# Warmup Iteration   1: 5.889 ±(99.9%) 0.072 ms/op
Iteration   1: 3.244 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.244 ms/op


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
# Warmup Iteration   1: 3.567 ±(99.9%) 0.050 ms/op
Iteration   1: 1.810 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.810 ms/op


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
# Warmup Iteration   1: 4.622 ±(99.9%) 0.065 ms/op
Iteration   1: 3.323 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.323 ms/op


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
# Warmup Iteration   1: 14.884 ±(99.9%) 0.325 ms/op
Iteration   1: 9.092 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.092 ms/op


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
# Warmup Iteration   1: 5.430 ±(99.9%) 0.166 ms/op
Iteration   1: 2.870 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  13.058 ms/op
                 createUser·p0.9999: 13.531 ms/op
                 createUser·p1.00:   13.533 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11256
  mean =      2.870 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 4461 
    [ 2.500,  3.750) = 5775 
    [ 3.750,  5.000) = 653 
    [ 5.000,  6.250) = 119 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     13.058 ms/op
     p(99.9900) =     13.531 ms/op
     p(99.9990) =     13.533 ms/op
     p(99.9999) =     13.533 ms/op
    p(100.0000) =     13.533 ms/op


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
# Warmup Iteration   1: 3.127 ±(99.9%) 0.086 ms/op
Iteration   1: 1.827 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.378 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.414 ms/op
                 existUser·p0.999:  5.530 ms/op
                 existUser·p0.9999: 7.576 ms/op
                 existUser·p1.00:   7.643 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17477
  mean =      1.827 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 454 
    [1.000, 1.500) = 3634 
    [1.500, 2.000) = 7635 
    [2.000, 2.500) = 4933 
    [2.500, 3.000) = 577 
    [3.000, 3.500) = 87 
    [3.500, 4.000) = 53 
    [4.000, 4.500) = 61 
    [4.500, 5.000) = 10 
    [5.000, 5.500) = 10 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.378 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.414 ms/op
     p(99.9000) =      5.530 ms/op
     p(99.9900) =      7.576 ms/op
     p(99.9990) =      7.643 ms/op
     p(99.9999) =      7.643 ms/op
    p(100.0000) =      7.643 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ±(99.9%) 0.110 ms/op
Iteration   1: 2.942 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.452 ms/op
                 getUser·p0.50:   2.798 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.467 ms/op
                 getUser·p0.999:  5.712 ms/op
                 getUser·p0.9999: 6.769 ms/op
                 getUser·p1.00:   6.808 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10865
  mean =      2.942 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 16 
    [1.500, 2.000) = 112 
    [2.000, 2.500) = 2811 
    [2.500, 3.000) = 3753 
    [3.000, 3.500) = 2069 
    [3.500, 4.000) = 1382 
    [4.000, 4.500) = 621 
    [4.500, 5.000) = 68 
    [5.000, 5.500) = 16 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.452 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.467 ms/op
     p(99.9000) =      5.712 ms/op
     p(99.9900) =      6.769 ms/op
     p(99.9990) =      6.808 ms/op
     p(99.9999) =      6.808 ms/op
    p(100.0000) =      6.808 ms/op


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
# Warmup Iteration   1: 13.623 ±(99.9%) 0.512 ms/op
Iteration   1: 8.373 ±(99.9%) 0.140 ms/op
                 listUser·p0.00:   2.101 ms/op
                 listUser·p0.50:   7.942 ms/op
                 listUser·p0.90:   10.756 ms/op
                 listUser·p0.95:   12.304 ms/op
                 listUser·p0.99:   19.620 ms/op
                 listUser·p0.999:  26.803 ms/op
                 listUser·p0.9999: 31.097 ms/op
                 listUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3824
  mean =      8.373 ±(99.9%) 0.140 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 83 
    [ 5.000,  7.500) = 1404 
    [ 7.500, 10.000) = 1748 
    [10.000, 12.500) = 416 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.101 ms/op
     p(50.0000) =      7.942 ms/op
     p(90.0000) =     10.756 ms/op
     p(95.0000) =     12.304 ms/op
     p(99.0000) =     19.620 ms/op
     p(99.9000) =     26.803 ms/op
     p(99.9900) =     31.097 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.632          ops/ms
Client.existUser                       thrpt         13.397          ops/ms
Client.getUser                         thrpt          9.917          ops/ms
Client.listUser                        thrpt          2.998          ops/ms
Client.createUser                       avgt          3.244           ms/op
Client.existUser                        avgt          1.810           ms/op
Client.getUser                          avgt          3.323           ms/op
Client.listUser                         avgt          9.092           ms/op
Client.createUser                     sample  11256   2.870 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.814           ms/op
Client.createUser:createUser·p0.50    sample          2.617           ms/op
Client.createUser:createUser·p0.90    sample          3.629           ms/op
Client.createUser:createUser·p0.95    sample          4.268           ms/op
Client.createUser:createUser·p0.99    sample          8.602           ms/op
Client.createUser:createUser·p0.999   sample         13.058           ms/op
Client.createUser:createUser·p0.9999  sample         13.531           ms/op
Client.createUser:createUser·p1.00    sample         13.533           ms/op
Client.existUser                      sample  17477   1.827 ± 0.012   ms/op
Client.existUser:existUser·p0.00      sample          0.378           ms/op
Client.existUser:existUser·p0.50      sample          1.817           ms/op
Client.existUser:existUser·p0.90      sample          2.339           ms/op
Client.existUser:existUser·p0.95      sample          2.490           ms/op
Client.existUser:existUser·p0.99      sample          3.414           ms/op
Client.existUser:existUser·p0.999     sample          5.530           ms/op
Client.existUser:existUser·p0.9999    sample          7.576           ms/op
Client.existUser:existUser·p1.00      sample          7.643           ms/op
Client.getUser                        sample  10865   2.942 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          0.452           ms/op
Client.getUser:getUser·p0.50          sample          2.798           ms/op
Client.getUser:getUser·p0.90          sample          3.863           ms/op
Client.getUser:getUser·p0.95          sample          4.092           ms/op
Client.getUser:getUser·p0.99          sample          4.467           ms/op
Client.getUser:getUser·p0.999         sample          5.712           ms/op
Client.getUser:getUser·p0.9999        sample          6.769           ms/op
Client.getUser:getUser·p1.00          sample          6.808           ms/op
Client.listUser                       sample   3824   8.373 ± 0.140   ms/op
Client.listUser:listUser·p0.00        sample          2.101           ms/op
Client.listUser:listUser·p0.50        sample          7.942           ms/op
Client.listUser:listUser·p0.90        sample         10.756           ms/op
Client.listUser:listUser·p0.95        sample         12.304           ms/op
Client.listUser:listUser·p0.99        sample         19.620           ms/op
Client.listUser:listUser·p0.999       sample         26.803           ms/op
Client.listUser:listUser·p0.9999      sample         31.097           ms/op
Client.listUser:listUser·p1.00        sample         31.097           ms/op
