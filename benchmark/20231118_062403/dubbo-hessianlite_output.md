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
# Warmup Iteration   1: 2.374 ops/ms
Iteration   1: 6.207 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.207 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.607 ops/ms
Iteration   1: 12.345 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.345 ops/ms


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
# Warmup Iteration   1: 4.820 ops/ms
Iteration   1: 9.173 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.173 ops/ms


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
# Warmup Iteration   1: 2.193 ops/ms
Iteration   1: 3.941 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.941 ops/ms


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.065 ms/op
Iteration   1: 3.213 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.213 ms/op


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
# Warmup Iteration   1: 3.211 ±(99.9%) 0.031 ms/op
Iteration   1: 1.960 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.960 ms/op


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
# Warmup Iteration   1: 4.373 ±(99.9%) 0.047 ms/op
Iteration   1: 3.197 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.197 ms/op


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
# Warmup Iteration   1: 12.666 ±(99.9%) 0.282 ms/op
Iteration   1: 7.483 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.483 ms/op


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
# Warmup Iteration   1: 4.503 ±(99.9%) 0.097 ms/op
Iteration   1: 2.798 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   2.632 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.105 ms/op
                 createUser·p0.999:  14.233 ms/op
                 createUser·p0.9999: 15.272 ms/op
                 createUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11280
  mean =      2.798 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 4176 
    [ 2.500,  3.750) = 6479 
    [ 3.750,  5.000) = 469 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.632 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      5.105 ms/op
     p(99.9000) =     14.233 ms/op
     p(99.9900) =     15.272 ms/op
     p(99.9990) =     15.286 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 2.953 ±(99.9%) 0.054 ms/op
Iteration   1: 1.799 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.437 ms/op
                 existUser·p0.50:   1.696 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.470 ms/op
                 existUser·p0.99:   3.073 ms/op
                 existUser·p0.999:  5.071 ms/op
                 existUser·p0.9999: 6.066 ms/op
                 existUser·p1.00:   6.365 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17767
  mean =      1.799 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 3 
    [0.500, 1.000) = 72 
    [1.000, 1.500) = 3455 
    [1.500, 2.000) = 9684 
    [2.000, 2.500) = 3803 
    [2.500, 3.000) = 557 
    [3.000, 3.500) = 79 
    [3.500, 4.000) = 24 
    [4.000, 4.500) = 39 
    [4.500, 5.000) = 29 
    [5.000, 5.500) = 18 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.696 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.470 ms/op
     p(99.0000) =      3.073 ms/op
     p(99.9000) =      5.071 ms/op
     p(99.9900) =      6.066 ms/op
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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ±(99.9%) 0.096 ms/op
Iteration   1: 2.849 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   2.810 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.772 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  13.169 ms/op
                 getUser·p0.9999: 13.351 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11226
  mean =      2.849 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 20 
    [ 1.250,  2.500) = 3282 
    [ 2.500,  3.750) = 7337 
    [ 3.750,  5.000) = 455 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     13.169 ms/op
     p(99.9900) =     13.351 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 12.878 ±(99.9%) 0.429 ms/op
Iteration   1: 8.594 ±(99.9%) 0.370 ms/op
                 listUser·p0.00:   1.978 ms/op
                 listUser·p0.50:   7.660 ms/op
                 listUser·p0.90:   10.977 ms/op
                 listUser·p0.95:   12.091 ms/op
                 listUser·p0.99:   41.202 ms/op
                 listUser·p0.999:  96.243 ms/op
                 listUser·p0.9999: 96.993 ms/op
                 listUser·p1.00:   96.993 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3725
  mean =      8.594 ±(99.9%) 0.370 ms/op

  Histogram, ms/op:
    [  0.000,  10.000) = 3046 
    [ 10.000,  20.000) = 626 
    [ 20.000,  30.000) = 5 
    [ 30.000,  40.000) = 7 
    [ 40.000,  50.000) = 11 
    [ 50.000,  60.000) = 7 
    [ 60.000,  70.000) = 10 
    [ 70.000,  80.000) = 1 
    [ 80.000,  90.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.978 ms/op
     p(50.0000) =      7.660 ms/op
     p(90.0000) =     10.977 ms/op
     p(95.0000) =     12.091 ms/op
     p(99.0000) =     41.202 ms/op
     p(99.9000) =     96.243 ms/op
     p(99.9900) =     96.993 ms/op
     p(99.9990) =     96.993 ms/op
     p(99.9999) =     96.993 ms/op
    p(100.0000) =     96.993 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.207          ops/ms
Client.existUser                       thrpt         12.345          ops/ms
Client.getUser                         thrpt          9.173          ops/ms
Client.listUser                        thrpt          3.941          ops/ms
Client.createUser                       avgt          3.213           ms/op
Client.existUser                        avgt          1.960           ms/op
Client.getUser                          avgt          3.197           ms/op
Client.listUser                         avgt          7.483           ms/op
Client.createUser                     sample  11280   2.798 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          0.634           ms/op
Client.createUser:createUser·p0.50    sample          2.632           ms/op
Client.createUser:createUser·p0.90    sample          3.469           ms/op
Client.createUser:createUser·p0.95    sample          3.797           ms/op
Client.createUser:createUser·p0.99    sample          5.105           ms/op
Client.createUser:createUser·p0.999   sample         14.233           ms/op
Client.createUser:createUser·p0.9999  sample         15.272           ms/op
Client.createUser:createUser·p1.00    sample         15.286           ms/op
Client.existUser                      sample  17767   1.799 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.437           ms/op
Client.existUser:existUser·p0.50      sample          1.696           ms/op
Client.existUser:existUser·p0.90      sample          2.302           ms/op
Client.existUser:existUser·p0.95      sample          2.470           ms/op
Client.existUser:existUser·p0.99      sample          3.073           ms/op
Client.existUser:existUser·p0.999     sample          5.071           ms/op
Client.existUser:existUser·p0.9999    sample          6.066           ms/op
Client.existUser:existUser·p1.00      sample          6.365           ms/op
Client.getUser                        sample  11226   2.849 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.951           ms/op
Client.getUser:getUser·p0.50          sample          2.810           ms/op
Client.getUser:getUser·p0.90          sample          3.482           ms/op
Client.getUser:getUser·p0.95          sample          3.772           ms/op
Client.getUser:getUser·p0.99          sample          5.538           ms/op
Client.getUser:getUser·p0.999         sample         13.169           ms/op
Client.getUser:getUser·p0.9999        sample         13.351           ms/op
Client.getUser:getUser·p1.00          sample         13.353           ms/op
Client.listUser                       sample   3725   8.594 ± 0.370   ms/op
Client.listUser:listUser·p0.00        sample          1.978           ms/op
Client.listUser:listUser·p0.50        sample          7.660           ms/op
Client.listUser:listUser·p0.90        sample         10.977           ms/op
Client.listUser:listUser·p0.95        sample         12.091           ms/op
Client.listUser:listUser·p0.99        sample         41.202           ms/op
Client.listUser:listUser·p0.999       sample         96.243           ms/op
Client.listUser:listUser·p0.9999      sample         96.993           ms/op
Client.listUser:listUser·p1.00        sample         96.993           ms/op
