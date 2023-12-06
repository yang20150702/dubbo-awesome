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
# Warmup Iteration   1: 1.963 ops/ms
Iteration   1: 5.374 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.374 ops/ms


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
# Warmup Iteration   1: 5.647 ops/ms
Iteration   1: 11.574 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.574 ops/ms


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
# Warmup Iteration   1: 3.494 ops/ms
Iteration   1: 7.650 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.650 ops/ms


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
# Warmup Iteration   1: 1.715 ops/ms
Iteration   1: 3.254 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.254 ops/ms


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
# Warmup Iteration   1: 6.056 ±(99.9%) 0.094 ms/op
Iteration   1: 3.073 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.073 ms/op


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
# Warmup Iteration   1: 3.178 ±(99.9%) 0.044 ms/op
Iteration   1: 2.010 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.010 ms/op


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
# Warmup Iteration   1: 5.000 ±(99.9%) 0.060 ms/op
Iteration   1: 3.122 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.122 ms/op


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
# Warmup Iteration   1: 11.100 ±(99.9%) 0.141 ms/op
Iteration   1: 8.131 ±(99.9%) 0.079 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.131 ms/op


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
# Warmup Iteration   1: 5.310 ±(99.9%) 0.145 ms/op
Iteration   1: 3.777 ±(99.9%) 0.111 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.202 ms/op
                 createUser·p0.99:   19.664 ms/op
                 createUser·p0.999:  37.159 ms/op
                 createUser·p0.9999: 46.006 ms/op
                 createUser·p1.00:   46.006 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 8542
  mean =      3.777 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8021 
    [ 5.000, 10.000) = 366 
    [10.000, 15.000) = 61 
    [15.000, 20.000) = 9 
    [20.000, 25.000) = 21 
    [25.000, 30.000) = 1 
    [30.000, 35.000) = 37 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.202 ms/op
     p(99.0000) =     19.664 ms/op
     p(99.9000) =     37.159 ms/op
     p(99.9900) =     46.006 ms/op
     p(99.9990) =     46.006 ms/op
     p(99.9999) =     46.006 ms/op
    p(100.0000) =     46.006 ms/op


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
# Warmup Iteration   1: 3.106 ±(99.9%) 0.070 ms/op
Iteration   1: 1.963 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   1.886 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   3.166 ms/op
                 existUser·p0.999:  4.155 ms/op
                 existUser·p0.9999: 6.726 ms/op
                 existUser·p1.00:   7.717 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16301
  mean =      1.963 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 28 
    [1.000, 1.500) = 823 
    [1.500, 2.000) = 9941 
    [2.000, 2.500) = 4056 
    [2.500, 3.000) = 1181 
    [3.000, 3.500) = 219 
    [3.500, 4.000) = 36 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 6 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      1.886 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      3.166 ms/op
     p(99.9000) =      4.155 ms/op
     p(99.9900) =      6.726 ms/op
     p(99.9990) =      7.717 ms/op
     p(99.9999) =      7.717 ms/op
    p(100.0000) =      7.717 ms/op


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
# Warmup Iteration   1: 4.834 ±(99.9%) 0.131 ms/op
Iteration   1: 3.380 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.824 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.791 ms/op
                 getUser·p0.99:   5.957 ms/op
                 getUser·p0.999:  9.807 ms/op
                 getUser·p0.9999: 13.173 ms/op
                 getUser·p1.00:   13.173 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9482
  mean =      3.380 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1199 
    [ 2.500,  3.750) = 5543 
    [ 3.750,  5.000) = 2359 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.791 ms/op
     p(99.0000) =      5.957 ms/op
     p(99.9000) =      9.807 ms/op
     p(99.9900) =     13.173 ms/op
     p(99.9990) =     13.173 ms/op
     p(99.9999) =     13.173 ms/op
    p(100.0000) =     13.173 ms/op


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
# Warmup Iteration   1: 11.148 ±(99.9%) 0.373 ms/op
Iteration   1: 8.419 ±(99.9%) 0.150 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   7.930 ms/op
                 listUser·p0.90:   10.895 ms/op
                 listUser·p0.95:   12.373 ms/op
                 listUser·p0.99:   22.050 ms/op
                 listUser·p0.999:  27.754 ms/op
                 listUser·p0.9999: 30.605 ms/op
                 listUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3835
  mean =      8.419 ±(99.9%) 0.150 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1402 
    [ 7.500, 10.000) = 1687 
    [10.000, 12.500) = 449 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      7.930 ms/op
     p(90.0000) =     10.895 ms/op
     p(95.0000) =     12.373 ms/op
     p(99.0000) =     22.050 ms/op
     p(99.9000) =     27.754 ms/op
     p(99.9900) =     30.605 ms/op
     p(99.9990) =     30.605 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.374          ops/ms
Client.existUser                       thrpt         11.574          ops/ms
Client.getUser                         thrpt          7.650          ops/ms
Client.listUser                        thrpt          3.254          ops/ms
Client.createUser                       avgt          3.073           ms/op
Client.existUser                        avgt          2.010           ms/op
Client.getUser                          avgt          3.122           ms/op
Client.listUser                         avgt          8.131           ms/op
Client.createUser                     sample   8542   3.777 ± 0.111   ms/op
Client.createUser:createUser·p0.00    sample          1.137           ms/op
Client.createUser:createUser·p0.50    sample          3.346           ms/op
Client.createUser:createUser·p0.90    sample          4.538           ms/op
Client.createUser:createUser·p0.95    sample          5.202           ms/op
Client.createUser:createUser·p0.99    sample         19.664           ms/op
Client.createUser:createUser·p0.999   sample         37.159           ms/op
Client.createUser:createUser·p0.9999  sample         46.006           ms/op
Client.createUser:createUser·p1.00    sample         46.006           ms/op
Client.existUser                      sample  16301   1.963 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.643           ms/op
Client.existUser:existUser·p0.50      sample          1.886           ms/op
Client.existUser:existUser·p0.90      sample          2.466           ms/op
Client.existUser:existUser·p0.95      sample          2.654           ms/op
Client.existUser:existUser·p0.99      sample          3.166           ms/op
Client.existUser:existUser·p0.999     sample          4.155           ms/op
Client.existUser:existUser·p0.9999    sample          6.726           ms/op
Client.existUser:existUser·p1.00      sample          7.717           ms/op
Client.getUser                        sample   9482   3.380 ± 0.030   ms/op
Client.getUser:getUser·p0.00          sample          0.824           ms/op
Client.getUser:getUser·p0.50          sample          3.305           ms/op
Client.getUser:getUser·p0.90          sample          4.268           ms/op
Client.getUser:getUser·p0.95          sample          4.791           ms/op
Client.getUser:getUser·p0.99          sample          5.957           ms/op
Client.getUser:getUser·p0.999         sample          9.807           ms/op
Client.getUser:getUser·p0.9999        sample         13.173           ms/op
Client.getUser:getUser·p1.00          sample         13.173           ms/op
Client.listUser                       sample   3835   8.419 ± 0.150   ms/op
Client.listUser:listUser·p0.00        sample          1.616           ms/op
Client.listUser:listUser·p0.50        sample          7.930           ms/op
Client.listUser:listUser·p0.90        sample         10.895           ms/op
Client.listUser:listUser·p0.95        sample         12.373           ms/op
Client.listUser:listUser·p0.99        sample         22.050           ms/op
Client.listUser:listUser·p0.999       sample         27.754           ms/op
Client.listUser:listUser·p0.9999      sample         30.605           ms/op
Client.listUser:listUser·p1.00        sample         30.605           ms/op
