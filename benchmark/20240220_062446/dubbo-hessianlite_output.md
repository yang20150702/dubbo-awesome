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
# Warmup Iteration   1: 2.335 ops/ms
Iteration   1: 5.777 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.777 ops/ms


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
# Warmup Iteration   1: 5.975 ops/ms
Iteration   1: 12.017 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.017 ops/ms


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
# Warmup Iteration   1: 3.714 ops/ms
Iteration   1: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.179 ops/ms


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
# Warmup Iteration   1: 2.280 ops/ms
Iteration   1: 4.051 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.051 ops/ms


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
# Warmup Iteration   1: 5.677 ±(99.9%) 0.070 ms/op
Iteration   1: 2.901 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.901 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.043 ms/op
Iteration   1: 2.032 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.032 ms/op


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
# Warmup Iteration   1: 4.445 ±(99.9%) 0.044 ms/op
Iteration   1: 2.927 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.927 ms/op


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
# Warmup Iteration   1: 12.293 ±(99.9%) 0.195 ms/op
Iteration   1: 8.293 ±(99.9%) 0.070 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.293 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.123 ms/op
Iteration   1: 2.895 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   10.773 ms/op
                 createUser·p0.999:  14.369 ms/op
                 createUser·p0.9999: 15.805 ms/op
                 createUser·p1.00:   15.958 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11045
  mean =      2.895 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 11 
    [ 1.250,  2.500) = 4527 
    [ 2.500,  3.750) = 5145 
    [ 3.750,  5.000) = 1065 
    [ 5.000,  6.250) = 116 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =     10.773 ms/op
     p(99.9000) =     14.369 ms/op
     p(99.9900) =     15.805 ms/op
     p(99.9990) =     15.958 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 3.198 ±(99.9%) 0.069 ms/op
Iteration   1: 1.882 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.231 ms/op
                 existUser·p0.50:   1.708 ms/op
                 existUser·p0.90:   2.486 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   3.871 ms/op
                 existUser·p0.999:  22.873 ms/op
                 existUser·p0.9999: 23.944 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16980
  mean =      1.882 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15350 
    [ 2.500,  5.000) = 1527 
    [ 5.000,  7.500) = 67 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.231 ms/op
     p(50.0000) =      1.708 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      3.871 ms/op
     p(99.9000) =     22.873 ms/op
     p(99.9900) =     23.944 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 4.823 ±(99.9%) 0.311 ms/op
Iteration   1: 3.265 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  9.260 ms/op
                 getUser·p0.9999: 10.732 ms/op
                 getUser·p1.00:   10.732 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9827
  mean =      3.265 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 100 
    [ 2.000,  3.000) = 3632 
    [ 3.000,  4.000) = 5114 
    [ 4.000,  5.000) = 627 
    [ 5.000,  6.000) = 168 
    [ 6.000,  7.000) = 148 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 16 
    [ 9.000, 10.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      6.332 ms/op
     p(99.9000) =      9.260 ms/op
     p(99.9900) =     10.732 ms/op
     p(99.9990) =     10.732 ms/op
     p(99.9999) =     10.732 ms/op
    p(100.0000) =     10.732 ms/op


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
# Warmup Iteration   1: 13.463 ±(99.9%) 0.526 ms/op
Iteration   1: 8.551 ±(99.9%) 0.162 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   7.963 ms/op
                 listUser·p0.90:   11.469 ms/op
                 listUser·p0.95:   12.501 ms/op
                 listUser·p0.99:   20.423 ms/op
                 listUser·p0.999:  32.585 ms/op
                 listUser·p0.9999: 34.144 ms/op
                 listUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3745
  mean =      8.551 ±(99.9%) 0.162 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 85 
    [ 5.000,  7.500) = 1357 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 585 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.718 ms/op
     p(50.0000) =      7.963 ms/op
     p(90.0000) =     11.469 ms/op
     p(95.0000) =     12.501 ms/op
     p(99.0000) =     20.423 ms/op
     p(99.9000) =     32.585 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.777          ops/ms
Client.existUser                       thrpt         12.017          ops/ms
Client.getUser                         thrpt          8.179          ops/ms
Client.listUser                        thrpt          4.051          ops/ms
Client.createUser                       avgt          2.901           ms/op
Client.existUser                        avgt          2.032           ms/op
Client.getUser                          avgt          2.927           ms/op
Client.listUser                         avgt          8.293           ms/op
Client.createUser                     sample  11045   2.895 ± 0.039   ms/op
Client.createUser:createUser·p0.00    sample          0.835           ms/op
Client.createUser:createUser·p0.50    sample          2.576           ms/op
Client.createUser:createUser·p0.90    sample          3.887           ms/op
Client.createUser:createUser·p0.95    sample          4.243           ms/op
Client.createUser:createUser·p0.99    sample         10.773           ms/op
Client.createUser:createUser·p0.999   sample         14.369           ms/op
Client.createUser:createUser·p0.9999  sample         15.805           ms/op
Client.createUser:createUser·p1.00    sample         15.958           ms/op
Client.existUser                      sample  16980   1.882 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.231           ms/op
Client.existUser:existUser·p0.50      sample          1.708           ms/op
Client.existUser:existUser·p0.90      sample          2.486           ms/op
Client.existUser:existUser·p0.95      sample          2.724           ms/op
Client.existUser:existUser·p0.99      sample          3.871           ms/op
Client.existUser:existUser·p0.999     sample         22.873           ms/op
Client.existUser:existUser·p0.9999    sample         23.944           ms/op
Client.existUser:existUser·p1.00      sample         24.150           ms/op
Client.getUser                        sample   9827   3.265 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.208           ms/op
Client.getUser:getUser·p0.50          sample          3.178           ms/op
Client.getUser:getUser·p0.90          sample          3.998           ms/op
Client.getUser:getUser·p0.95          sample          4.661           ms/op
Client.getUser:getUser·p0.99          sample          6.332           ms/op
Client.getUser:getUser·p0.999         sample          9.260           ms/op
Client.getUser:getUser·p0.9999        sample         10.732           ms/op
Client.getUser:getUser·p1.00          sample         10.732           ms/op
Client.listUser                       sample   3745   8.551 ± 0.162   ms/op
Client.listUser:listUser·p0.00        sample          1.718           ms/op
Client.listUser:listUser·p0.50        sample          7.963           ms/op
Client.listUser:listUser·p0.90        sample         11.469           ms/op
Client.listUser:listUser·p0.95        sample         12.501           ms/op
Client.listUser:listUser·p0.99        sample         20.423           ms/op
Client.listUser:listUser·p0.999       sample         32.585           ms/op
Client.listUser:listUser·p0.9999      sample         34.144           ms/op
Client.listUser:listUser·p1.00        sample         34.144           ms/op
