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
# Warmup Iteration   1: 2.174 ops/ms
Iteration   1: 5.898 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.898 ops/ms


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
# Warmup Iteration   1: 6.597 ops/ms
Iteration   1: 14.007 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.007 ops/ms


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
# Warmup Iteration   1: 4.019 ops/ms
Iteration   1: 7.891 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.891 ops/ms


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
# Warmup Iteration   1: 2.070 ops/ms
Iteration   1: 3.692 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.692 ops/ms


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
# Warmup Iteration   1: 5.503 ±(99.9%) 0.050 ms/op
Iteration   1: 3.149 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.149 ms/op


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
# Warmup Iteration   1: 3.244 ±(99.9%) 0.033 ms/op
Iteration   1: 1.884 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.884 ms/op


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.047 ms/op
Iteration   1: 3.098 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.098 ms/op


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
# Warmup Iteration   1: 12.477 ±(99.9%) 0.235 ms/op
Iteration   1: 8.263 ±(99.9%) 0.136 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.263 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.120 ms/op
Iteration   1: 3.340 ±(99.9%) 0.201 ms/op
                 createUser·p0.00:   0.500 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   12.530 ms/op
                 createUser·p0.999:  109.951 ms/op
                 createUser·p0.9999: 119.669 ms/op
                 createUser·p1.00:   119.669 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9570
  mean =      3.340 ±(99.9%) 0.201 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 9473 
    [ 12.500,  25.000) = 59 
    [ 25.000,  37.500) = 6 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 4 
    [ 87.500, 100.000) = 10 
    [100.000, 112.500) = 12 
    [112.500, 125.000) = 6 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.646 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =     12.530 ms/op
     p(99.9000) =    109.951 ms/op
     p(99.9900) =    119.669 ms/op
     p(99.9990) =    119.669 ms/op
     p(99.9999) =    119.669 ms/op
    p(100.0000) =    119.669 ms/op


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
# Warmup Iteration   1: 3.184 ±(99.9%) 0.093 ms/op
Iteration   1: 1.807 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.520 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.183 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   3.306 ms/op
                 existUser·p0.999:  25.080 ms/op
                 existUser·p0.9999: 25.919 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17692
  mean =      1.807 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17001 
    [ 2.500,  5.000) = 647 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.520 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.183 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.306 ms/op
     p(99.9000) =     25.080 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     25.919 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 5.064 ±(99.9%) 0.115 ms/op
Iteration   1: 3.293 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   7.117 ms/op
                 getUser·p0.999:  12.330 ms/op
                 getUser·p0.9999: 12.648 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9708
  mean =      3.293 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1551 
    [ 2.500,  3.750) = 6236 
    [ 3.750,  5.000) = 1663 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 106 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.117 ms/op
     p(99.9000) =     12.330 ms/op
     p(99.9900) =     12.648 ms/op
     p(99.9990) =     12.648 ms/op
     p(99.9999) =     12.648 ms/op
    p(100.0000) =     12.648 ms/op


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
# Warmup Iteration   1: 12.810 ±(99.9%) 0.436 ms/op
Iteration   1: 8.847 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.073 ms/op
                 listUser·p0.50:   8.503 ms/op
                 listUser·p0.90:   11.469 ms/op
                 listUser·p0.95:   12.730 ms/op
                 listUser·p0.99:   17.092 ms/op
                 listUser·p0.999:  19.252 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3619
  mean =      8.847 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 50 
    [ 5.000,  7.500) = 903 
    [ 7.500, 10.000) = 1819 
    [10.000, 12.500) = 625 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      8.503 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     12.730 ms/op
     p(99.0000) =     17.092 ms/op
     p(99.9000) =     19.252 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           5.898          ops/ms
Client.existUser                       thrpt          14.007          ops/ms
Client.getUser                         thrpt           7.891          ops/ms
Client.listUser                        thrpt           3.692          ops/ms
Client.createUser                       avgt           3.149           ms/op
Client.existUser                        avgt           1.884           ms/op
Client.getUser                          avgt           3.098           ms/op
Client.listUser                         avgt           8.263           ms/op
Client.createUser                     sample   9570    3.340 ± 0.201   ms/op
Client.createUser:createUser·p0.00    sample           0.500           ms/op
Client.createUser:createUser·p0.50    sample           2.646           ms/op
Client.createUser:createUser·p0.90    sample           3.916           ms/op
Client.createUser:createUser·p0.95    sample           4.514           ms/op
Client.createUser:createUser·p0.99    sample          12.530           ms/op
Client.createUser:createUser·p0.999   sample         109.951           ms/op
Client.createUser:createUser·p0.9999  sample         119.669           ms/op
Client.createUser:createUser·p1.00    sample         119.669           ms/op
Client.existUser                      sample  17692    1.807 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample           0.520           ms/op
Client.existUser:existUser·p0.50      sample           1.702           ms/op
Client.existUser:existUser·p0.90      sample           2.183           ms/op
Client.existUser:existUser·p0.95      sample           2.392           ms/op
Client.existUser:existUser·p0.99      sample           3.306           ms/op
Client.existUser:existUser·p0.999     sample          25.080           ms/op
Client.existUser:existUser·p0.9999    sample          25.919           ms/op
Client.existUser:existUser·p1.00      sample          25.919           ms/op
Client.getUser                        sample   9708    3.293 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample           1.051           ms/op
Client.getUser:getUser·p0.50          sample           3.215           ms/op
Client.getUser:getUser·p0.90          sample           4.055           ms/op
Client.getUser:getUser·p0.95          sample           4.391           ms/op
Client.getUser:getUser·p0.99          sample           7.117           ms/op
Client.getUser:getUser·p0.999         sample          12.330           ms/op
Client.getUser:getUser·p0.9999        sample          12.648           ms/op
Client.getUser:getUser·p1.00          sample          12.648           ms/op
Client.listUser                       sample   3619    8.847 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample           2.073           ms/op
Client.listUser:listUser·p0.50        sample           8.503           ms/op
Client.listUser:listUser·p0.90        sample          11.469           ms/op
Client.listUser:listUser·p0.95        sample          12.730           ms/op
Client.listUser:listUser·p0.99        sample          17.092           ms/op
Client.listUser:listUser·p0.999       sample          19.252           ms/op
Client.listUser:listUser·p0.9999      sample          22.282           ms/op
Client.listUser:listUser·p1.00        sample          22.282           ms/op
