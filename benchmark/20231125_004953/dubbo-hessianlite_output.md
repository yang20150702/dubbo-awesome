# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
Iteration   1: 5.991 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.991 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.135 ops/ms
Iteration   1: 14.658 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.658 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.160 ops/ms
Iteration   1: 9.256 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.256 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.414 ops/ms
Iteration   1: 3.699 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.699 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.960 ±(99.9%) 0.072 ms/op
Iteration   1: 2.640 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.820 ±(99.9%) 0.033 ms/op
Iteration   1: 1.747 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.747 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.389 ±(99.9%) 0.045 ms/op
Iteration   1: 2.980 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.980 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.697 ±(99.9%) 0.187 ms/op
Iteration   1: 7.428 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.818 ±(99.9%) 0.075 ms/op
Iteration   1: 3.161 ±(99.9%) 0.049 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.863 ms/op
                 createUser·p0.90:   4.190 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   8.026 ms/op
                 createUser·p0.999:  21.394 ms/op
                 createUser·p0.9999: 22.150 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10106
  mean =      3.161 ±(99.9%) 0.049 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2792 
    [ 2.500,  5.000) = 7111 
    [ 5.000,  7.500) = 98 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      8.026 ms/op
     p(99.9000) =     21.394 ms/op
     p(99.9900) =     22.150 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.855 ±(99.9%) 0.051 ms/op
Iteration   1: 1.974 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.942 ms/op
                 existUser·p0.90:   2.482 ms/op
                 existUser·p0.95:   2.666 ms/op
                 existUser·p0.99:   3.059 ms/op
                 existUser·p0.999:  16.613 ms/op
                 existUser·p0.9999: 16.822 ms/op
                 existUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16212
  mean =      1.974 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 736 
    [ 1.250,  2.500) = 13938 
    [ 2.500,  3.750) = 1465 
    [ 3.750,  5.000) = 35 
    [ 5.000,  6.250) = 6 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.482 ms/op
     p(95.0000) =      2.666 ms/op
     p(99.0000) =      3.059 ms/op
     p(99.9000) =     16.613 ms/op
     p(99.9900) =     16.822 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.290 ±(99.9%) 0.096 ms/op
Iteration   1: 2.924 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   2.687 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 19.690 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10940
  mean =      2.924 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 4394 
    [ 2.500,  3.750) = 5384 
    [ 3.750,  5.000) = 929 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      2.687 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     18.547 ms/op
     p(99.9900) =     19.690 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.300 ±(99.9%) 0.417 ms/op
Iteration   1: 9.148 ±(99.9%) 0.302 ms/op
                 listUser·p0.00:   2.191 ms/op
                 listUser·p0.50:   8.249 ms/op
                 listUser·p0.90:   11.747 ms/op
                 listUser·p0.95:   13.202 ms/op
                 listUser·p0.99:   31.202 ms/op
                 listUser·p0.999:  71.371 ms/op
                 listUser·p0.9999: 73.138 ms/op
                 listUser·p1.00:   73.138 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3483
  mean =      9.148 ±(99.9%) 0.302 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 78 
    [ 5.000, 10.000) = 2485 
    [10.000, 15.000) = 837 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 6 
    [50.000, 55.000) = 3 
    [55.000, 60.000) = 3 
    [60.000, 65.000) = 7 
    [65.000, 70.000) = 2 
    [70.000, 75.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.191 ms/op
     p(50.0000) =      8.249 ms/op
     p(90.0000) =     11.747 ms/op
     p(95.0000) =     13.202 ms/op
     p(99.0000) =     31.202 ms/op
     p(99.9000) =     71.371 ms/op
     p(99.9900) =     73.138 ms/op
     p(99.9990) =     73.138 ms/op
     p(99.9999) =     73.138 ms/op
    p(100.0000) =     73.138 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.991          ops/ms
Client.existUser                       thrpt         14.658          ops/ms
Client.getUser                         thrpt          9.256          ops/ms
Client.listUser                        thrpt          3.699          ops/ms
Client.createUser                       avgt          2.640           ms/op
Client.existUser                        avgt          1.747           ms/op
Client.getUser                          avgt          2.980           ms/op
Client.listUser                         avgt          7.428           ms/op
Client.createUser                     sample  10106   3.161 ± 0.049   ms/op
Client.createUser:createUser·p0.00    sample          1.083           ms/op
Client.createUser:createUser·p0.50    sample          2.863           ms/op
Client.createUser:createUser·p0.90    sample          4.190           ms/op
Client.createUser:createUser·p0.95    sample          4.538           ms/op
Client.createUser:createUser·p0.99    sample          8.026           ms/op
Client.createUser:createUser·p0.999   sample         21.394           ms/op
Client.createUser:createUser·p0.9999  sample         22.150           ms/op
Client.createUser:createUser·p1.00    sample         22.151           ms/op
Client.existUser                      sample  16212   1.974 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.571           ms/op
Client.existUser:existUser·p0.50      sample          1.942           ms/op
Client.existUser:existUser·p0.90      sample          2.482           ms/op
Client.existUser:existUser·p0.95      sample          2.666           ms/op
Client.existUser:existUser·p0.99      sample          3.059           ms/op
Client.existUser:existUser·p0.999     sample         16.613           ms/op
Client.existUser:existUser·p0.9999    sample         16.822           ms/op
Client.existUser:existUser·p1.00      sample         16.843           ms/op
Client.getUser                        sample  10940   2.924 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.642           ms/op
Client.getUser:getUser·p0.50          sample          2.687           ms/op
Client.getUser:getUser·p0.90          sample          3.764           ms/op
Client.getUser:getUser·p0.95          sample          4.063           ms/op
Client.getUser:getUser·p0.99          sample          6.570           ms/op
Client.getUser:getUser·p0.999         sample         18.547           ms/op
Client.getUser:getUser·p0.9999        sample         19.690           ms/op
Client.getUser:getUser·p1.00          sample         19.792           ms/op
Client.listUser                       sample   3483   9.148 ± 0.302   ms/op
Client.listUser:listUser·p0.00        sample          2.191           ms/op
Client.listUser:listUser·p0.50        sample          8.249           ms/op
Client.listUser:listUser·p0.90        sample         11.747           ms/op
Client.listUser:listUser·p0.95        sample         13.202           ms/op
Client.listUser:listUser·p0.99        sample         31.202           ms/op
Client.listUser:listUser·p0.999       sample         71.371           ms/op
Client.listUser:listUser·p0.9999      sample         73.138           ms/op
Client.listUser:listUser·p1.00        sample         73.138           ms/op
