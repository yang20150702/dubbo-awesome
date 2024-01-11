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
# Warmup Iteration   1: 2.560 ops/ms
Iteration   1: 6.458 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.458 ops/ms


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
# Warmup Iteration   1: 6.458 ops/ms
Iteration   1: 12.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.377 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.592 ops/ms
Iteration   1: 8.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.761 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
Iteration   1: 3.805 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.805 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.677 ±(99.9%) 0.086 ms/op
Iteration   1: 2.977 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.977 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.571 ±(99.9%) 0.045 ms/op
Iteration   1: 1.876 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.876 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.047 ms/op
Iteration   1: 3.018 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.018 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.505 ±(99.9%) 0.189 ms/op
Iteration   1: 8.732 ±(99.9%) 0.114 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.732 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.956 ±(99.9%) 0.104 ms/op
Iteration   1: 3.299 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   2.777 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   13.486 ms/op
                 createUser·p0.999:  68.067 ms/op
                 createUser·p0.9999: 70.255 ms/op
                 createUser·p1.00:   70.255 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9690
  mean =      3.299 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9242 
    [ 5.000, 10.000) = 282 
    [10.000, 15.000) = 119 
    [15.000, 20.000) = 8 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 1 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 4 
    [60.000, 65.000) = 2 
    [65.000, 70.000) = 15 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      2.777 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =     13.486 ms/op
     p(99.9000) =     68.067 ms/op
     p(99.9900) =     70.255 ms/op
     p(99.9990) =     70.255 ms/op
     p(99.9999) =     70.255 ms/op
    p(100.0000) =     70.255 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.156 ±(99.9%) 0.070 ms/op
Iteration   1: 1.658 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.469 ms/op
                 existUser·p0.50:   1.620 ms/op
                 existUser·p0.90:   1.946 ms/op
                 existUser·p0.95:   2.101 ms/op
                 existUser·p0.99:   2.680 ms/op
                 existUser·p0.999:  4.503 ms/op
                 existUser·p0.9999: 5.406 ms/op
                 existUser·p1.00:   6.365 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19289
  mean =      1.658 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 5 
    [0.500, 1.000) = 126 
    [1.000, 1.500) = 4916 
    [1.500, 2.000) = 12731 
    [2.000, 2.500) = 1253 
    [2.500, 3.000) = 109 
    [3.000, 3.500) = 46 
    [3.500, 4.000) = 35 
    [4.000, 4.500) = 49 
    [4.500, 5.000) = 15 
    [5.000, 5.500) = 3 
    [5.500, 6.000) = 0 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.469 ms/op
     p(50.0000) =      1.620 ms/op
     p(90.0000) =      1.946 ms/op
     p(95.0000) =      2.101 ms/op
     p(99.0000) =      2.680 ms/op
     p(99.9000) =      4.503 ms/op
     p(99.9900) =      5.406 ms/op
     p(99.9990) =      6.365 ms/op
     p(99.9999) =      6.365 ms/op
    p(100.0000) =      6.365 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.395 ±(99.9%) 0.108 ms/op
Iteration   1: 3.154 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.822 ms/op
                 getUser·p0.999:  14.483 ms/op
                 getUser·p0.9999: 15.384 ms/op
                 getUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10156
  mean =      3.154 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 1637 
    [ 2.500,  3.750) = 7084 
    [ 3.750,  5.000) = 1221 
    [ 5.000,  6.250) = 88 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.822 ms/op
     p(99.9000) =     14.483 ms/op
     p(99.9900) =     15.384 ms/op
     p(99.9990) =     15.385 ms/op
     p(99.9999) =     15.385 ms/op
    p(100.0000) =     15.385 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.902 ±(99.9%) 0.441 ms/op
Iteration   1: 8.042 ±(99.9%) 0.316 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   7.250 ms/op
                 listUser·p0.90:   9.929 ms/op
                 listUser·p0.95:   11.321 ms/op
                 listUser·p0.99:   24.710 ms/op
                 listUser·p0.999:  76.419 ms/op
                 listUser·p0.9999: 92.799 ms/op
                 listUser·p1.00:   92.799 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3969
  mean =      8.042 ±(99.9%) 0.316 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 3583 
    [ 10.000,  20.000) = 338 
    [ 20.000,  30.000) = 14 
    [ 30.000,  40.000) = 2 
    [ 40.000,  50.000) = 3 
    [ 50.000,  60.000) = 3 
    [ 60.000,  70.000) = 8 
    [ 70.000,  80.000) = 16 
    [ 80.000,  90.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      7.250 ms/op
     p(90.0000) =      9.929 ms/op
     p(95.0000) =     11.321 ms/op
     p(99.0000) =     24.710 ms/op
     p(99.9000) =     76.419 ms/op
     p(99.9900) =     92.799 ms/op
     p(99.9990) =     92.799 ms/op
     p(99.9999) =     92.799 ms/op
    p(100.0000) =     92.799 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.458          ops/ms
Client.existUser                       thrpt         12.377          ops/ms
Client.getUser                         thrpt          8.761          ops/ms
Client.listUser                        thrpt          3.805          ops/ms
Client.createUser                       avgt          2.977           ms/op
Client.existUser                        avgt          1.876           ms/op
Client.getUser                          avgt          3.018           ms/op
Client.listUser                         avgt          8.732           ms/op
Client.createUser                     sample   9690   3.299 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample          1.243           ms/op
Client.createUser:createUser·p0.50    sample          2.777           ms/op
Client.createUser:createUser·p0.90    sample          4.030           ms/op
Client.createUser:createUser·p0.95    sample          4.825           ms/op
Client.createUser:createUser·p0.99    sample         13.486           ms/op
Client.createUser:createUser·p0.999   sample         68.067           ms/op
Client.createUser:createUser·p0.9999  sample         70.255           ms/op
Client.createUser:createUser·p1.00    sample         70.255           ms/op
Client.existUser                      sample  19289   1.658 ± 0.007   ms/op
Client.existUser:existUser·p0.00      sample          0.469           ms/op
Client.existUser:existUser·p0.50      sample          1.620           ms/op
Client.existUser:existUser·p0.90      sample          1.946           ms/op
Client.existUser:existUser·p0.95      sample          2.101           ms/op
Client.existUser:existUser·p0.99      sample          2.680           ms/op
Client.existUser:existUser·p0.999     sample          4.503           ms/op
Client.existUser:existUser·p0.9999    sample          5.406           ms/op
Client.existUser:existUser·p1.00      sample          6.365           ms/op
Client.getUser                        sample  10156   3.154 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.867           ms/op
Client.getUser:getUser·p0.50          sample          2.998           ms/op
Client.getUser:getUser·p0.90          sample          3.957           ms/op
Client.getUser:getUser·p0.95          sample          4.334           ms/op
Client.getUser:getUser·p0.99          sample          6.822           ms/op
Client.getUser:getUser·p0.999         sample         14.483           ms/op
Client.getUser:getUser·p0.9999        sample         15.384           ms/op
Client.getUser:getUser·p1.00          sample         15.385           ms/op
Client.listUser                       sample   3969   8.042 ± 0.316   ms/op
Client.listUser:listUser·p0.00        sample          1.167           ms/op
Client.listUser:listUser·p0.50        sample          7.250           ms/op
Client.listUser:listUser·p0.90        sample          9.929           ms/op
Client.listUser:listUser·p0.95        sample         11.321           ms/op
Client.listUser:listUser·p0.99        sample         24.710           ms/op
Client.listUser:listUser·p0.999       sample         76.419           ms/op
Client.listUser:listUser·p0.9999      sample         92.799           ms/op
Client.listUser:listUser·p1.00        sample         92.799           ms/op
