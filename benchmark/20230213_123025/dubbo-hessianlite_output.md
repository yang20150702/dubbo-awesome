# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.097 ops/ms
Iteration   1: 2.450 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.450 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ops/ms
Iteration   1: 7.268 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.268 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
Iteration   1: 5.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.952 ops/ms
Iteration   1: 1.440 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.440 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 13.485 ±(99.9%) 0.216 ms/op
Iteration   1: 5.481 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.481 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.534 ±(99.9%) 0.064 ms/op
Iteration   1: 3.885 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.885 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.408 ±(99.9%) 0.092 ms/op
Iteration   1: 4.202 ±(99.9%) 0.054 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.202 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 24.176 ±(99.9%) 0.429 ms/op
Iteration   1: 16.504 ±(99.9%) 0.076 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.504 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.998 ±(99.9%) 0.338 ms/op
Iteration   1: 7.837 ±(99.9%) 0.338 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   6.750 ms/op
                 createUser·p0.90:   7.981 ms/op
                 createUser·p0.95:   14.500 ms/op
                 createUser·p0.99:   26.739 ms/op
                 createUser·p0.999:  83.108 ms/op
                 createUser·p0.9999: 83.231 ms/op
                 createUser·p1.00:   83.231 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4133
  mean =      7.837 ±(99.9%) 0.338 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 110 
    [ 5.000, 10.000) = 3652 
    [10.000, 15.000) = 175 
    [15.000, 20.000) = 123 
    [20.000, 25.000) = 17 
    [25.000, 30.000) = 24 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 11 
    [70.000, 75.000) = 1 
    [75.000, 80.000) = 13 
    [80.000, 85.000) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      6.750 ms/op
     p(90.0000) =      7.981 ms/op
     p(95.0000) =     14.500 ms/op
     p(99.0000) =     26.739 ms/op
     p(99.9000) =     83.108 ms/op
     p(99.9900) =     83.231 ms/op
     p(99.9990) =     83.231 ms/op
     p(99.9999) =     83.231 ms/op
    p(100.0000) =     83.231 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.284 ±(99.9%) 0.197 ms/op
Iteration   1: 3.147 ±(99.9%) 0.038 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   10.142 ms/op
                 existUser·p0.999:  16.712 ms/op
                 existUser·p0.9999: 16.940 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 10163
  mean =      3.147 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 310 
    [ 2.500,  3.750) = 9232 
    [ 3.750,  5.000) = 316 
    [ 5.000,  6.250) = 143 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     16.940 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 9.550 ±(99.9%) 0.290 ms/op
Iteration   1: 4.218 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   4.710 ms/op
                 getUser·p0.95:   4.980 ms/op
                 getUser·p0.99:   7.664 ms/op
                 getUser·p0.999:  18.630 ms/op
                 getUser·p0.9999: 18.973 ms/op
                 getUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7722
  mean =      4.218 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 32 
    [ 2.500,  3.750) = 952 
    [ 3.750,  5.000) = 6367 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      4.080 ms/op
     p(90.0000) =      4.710 ms/op
     p(95.0000) =      4.980 ms/op
     p(99.0000) =      7.664 ms/op
     p(99.9000) =     18.630 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 23.572 ±(99.9%) 0.656 ms/op
Iteration   1: 14.287 ±(99.9%) 0.200 ms/op
                 listUser·p0.00:   4.620 ms/op
                 listUser·p0.50:   13.746 ms/op
                 listUser·p0.90:   15.827 ms/op
                 listUser·p0.95:   19.169 ms/op
                 listUser·p0.99:   28.900 ms/op
                 listUser·p0.999:  35.197 ms/op
                 listUser·p0.9999: 38.666 ms/op
                 listUser·p1.00:   38.666 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2233
  mean =     14.287 ±(99.9%) 0.200 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 2 
    [ 5.000,  7.500) = 9 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 1770 
    [15.000, 17.500) = 213 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.620 ms/op
     p(50.0000) =     13.746 ms/op
     p(90.0000) =     15.827 ms/op
     p(95.0000) =     19.169 ms/op
     p(99.0000) =     28.900 ms/op
     p(99.9000) =     35.197 ms/op
     p(99.9900) =     38.666 ms/op
     p(99.9990) =     38.666 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          2.450          ops/ms
Client.existUser                       thrpt          7.268          ops/ms
Client.getUser                         thrpt          5.355          ops/ms
Client.listUser                        thrpt          1.440          ops/ms
Client.createUser                       avgt          5.481           ms/op
Client.existUser                        avgt          3.885           ms/op
Client.getUser                          avgt          4.202           ms/op
Client.listUser                         avgt         16.504           ms/op
Client.createUser                     sample   4133   7.837 ± 0.338   ms/op
Client.createUser:createUser·p0.00    sample          1.569           ms/op
Client.createUser:createUser·p0.50    sample          6.750           ms/op
Client.createUser:createUser·p0.90    sample          7.981           ms/op
Client.createUser:createUser·p0.95    sample         14.500           ms/op
Client.createUser:createUser·p0.99    sample         26.739           ms/op
Client.createUser:createUser·p0.999   sample         83.108           ms/op
Client.createUser:createUser·p0.9999  sample         83.231           ms/op
Client.createUser:createUser·p1.00    sample         83.231           ms/op
Client.existUser                      sample  10163   3.147 ± 0.038   ms/op
Client.existUser:existUser·p0.00      sample          0.948           ms/op
Client.existUser:existUser·p0.50      sample          2.941           ms/op
Client.existUser:existUser·p0.90      sample          3.490           ms/op
Client.existUser:existUser·p0.95      sample          4.047           ms/op
Client.existUser:existUser·p0.99      sample         10.142           ms/op
Client.existUser:existUser·p0.999     sample         16.712           ms/op
Client.existUser:existUser·p0.9999    sample         16.940           ms/op
Client.existUser:existUser·p1.00      sample         16.941           ms/op
Client.getUser                        sample   7722   4.218 ± 0.042   ms/op
Client.getUser:getUser·p0.00          sample          1.167           ms/op
Client.getUser:getUser·p0.50          sample          4.080           ms/op
Client.getUser:getUser·p0.90          sample          4.710           ms/op
Client.getUser:getUser·p0.95          sample          4.980           ms/op
Client.getUser:getUser·p0.99          sample          7.664           ms/op
Client.getUser:getUser·p0.999         sample         18.630           ms/op
Client.getUser:getUser·p0.9999        sample         18.973           ms/op
Client.getUser:getUser·p1.00          sample         18.973           ms/op
Client.listUser                       sample   2233  14.287 ± 0.200   ms/op
Client.listUser:listUser·p0.00        sample          4.620           ms/op
Client.listUser:listUser·p0.50        sample         13.746           ms/op
Client.listUser:listUser·p0.90        sample         15.827           ms/op
Client.listUser:listUser·p0.95        sample         19.169           ms/op
Client.listUser:listUser·p0.99        sample         28.900           ms/op
Client.listUser:listUser·p0.999       sample         35.197           ms/op
Client.listUser:listUser·p0.9999      sample         38.666           ms/op
Client.listUser:listUser·p1.00        sample         38.666           ms/op
