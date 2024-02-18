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
# Warmup Iteration   1: 2.514 ops/ms
Iteration   1: 6.510 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.510 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.476 ops/ms
Iteration   1: 12.398 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.398 ops/ms


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
# Warmup Iteration   1: 5.012 ops/ms
Iteration   1: 9.213 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.213 ops/ms


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
# Warmup Iteration   1: 2.302 ops/ms
Iteration   1: 3.363 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.363 ops/ms


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
# Warmup Iteration   1: 5.646 ±(99.9%) 0.090 ms/op
Iteration   1: 3.000 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.000 ms/op


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
# Warmup Iteration   1: 3.057 ±(99.9%) 0.033 ms/op
Iteration   1: 1.925 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.925 ms/op


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
# Warmup Iteration   1: 4.568 ±(99.9%) 0.042 ms/op
Iteration   1: 3.068 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.068 ms/op


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
# Warmup Iteration   1: 12.669 ±(99.9%) 0.268 ms/op
Iteration   1: 10.552 ±(99.9%) 0.134 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.552 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.111 ms/op
Iteration   1: 2.993 ±(99.9%) 0.044 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   2.789 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   4.182 ms/op
                 createUser·p0.99:   10.273 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 18.741 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10715
  mean =      2.993 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 2897 
    [ 2.500,  3.750) = 6924 
    [ 3.750,  5.000) = 560 
    [ 5.000,  6.250) = 70 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      2.789 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      4.182 ms/op
     p(99.0000) =     10.273 ms/op
     p(99.9000) =     17.826 ms/op
     p(99.9900) =     18.741 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 3.240 ±(99.9%) 0.073 ms/op
Iteration   1: 1.947 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   1.888 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.822 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  5.376 ms/op
                 existUser·p0.9999: 8.296 ms/op
                 existUser·p1.00:   10.273 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16400
  mean =      1.947 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 73 
    [ 1.000,  2.000) = 9649 
    [ 2.000,  3.000) = 6175 
    [ 3.000,  4.000) = 423 
    [ 4.000,  5.000) = 50 
    [ 5.000,  6.000) = 23 
    [ 6.000,  7.000) = 4 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =      5.376 ms/op
     p(99.9900) =      8.296 ms/op
     p(99.9990) =     10.273 ms/op
     p(99.9999) =     10.273 ms/op
    p(100.0000) =     10.273 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.093 ms/op
Iteration   1: 2.957 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.037 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.086 ms/op
                 getUser·p0.999:  7.865 ms/op
                 getUser·p0.9999: 8.012 ms/op
                 getUser·p1.00:   8.012 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10813
  mean =      2.957 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 57 
    [1.500, 2.000) = 707 
    [2.000, 2.500) = 2111 
    [2.500, 3.000) = 2709 
    [3.000, 3.500) = 3276 
    [3.500, 4.000) = 1469 
    [4.000, 4.500) = 308 
    [4.500, 5.000) = 64 
    [5.000, 5.500) = 34 
    [5.500, 6.000) = 26 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 19 
    [7.500, 8.000) = 7 
    [8.000, 8.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.037 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.086 ms/op
     p(99.9000) =      7.865 ms/op
     p(99.9900) =      8.012 ms/op
     p(99.9990) =      8.012 ms/op
     p(99.9999) =      8.012 ms/op
    p(100.0000) =      8.012 ms/op


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
# Warmup Iteration   1: 12.800 ±(99.9%) 0.437 ms/op
Iteration   1: 8.834 ±(99.9%) 0.120 ms/op
                 listUser·p0.00:   2.691 ms/op
                 listUser·p0.50:   8.503 ms/op
                 listUser·p0.90:   11.829 ms/op
                 listUser·p0.95:   13.042 ms/op
                 listUser·p0.99:   15.610 ms/op
                 listUser·p0.999:  18.161 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3625
  mean =      8.834 ±(99.9%) 0.120 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 3 
    [ 3.750,  5.000) = 44 
    [ 5.000,  6.250) = 240 
    [ 6.250,  7.500) = 787 
    [ 7.500,  8.750) = 920 
    [ 8.750, 10.000) = 727 
    [10.000, 11.250) = 404 
    [11.250, 12.500) = 250 
    [12.500, 13.750) = 154 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.691 ms/op
     p(50.0000) =      8.503 ms/op
     p(90.0000) =     11.829 ms/op
     p(95.0000) =     13.042 ms/op
     p(99.0000) =     15.610 ms/op
     p(99.9000) =     18.161 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.510          ops/ms
Client.existUser                       thrpt         12.398          ops/ms
Client.getUser                         thrpt          9.213          ops/ms
Client.listUser                        thrpt          3.363          ops/ms
Client.createUser                       avgt          3.000           ms/op
Client.existUser                        avgt          1.925           ms/op
Client.getUser                          avgt          3.068           ms/op
Client.listUser                         avgt         10.552           ms/op
Client.createUser                     sample  10715   2.993 ± 0.044   ms/op
Client.createUser:createUser·p0.00    sample          1.112           ms/op
Client.createUser:createUser·p0.50    sample          2.789           ms/op
Client.createUser:createUser·p0.90    sample          3.572           ms/op
Client.createUser:createUser·p0.95    sample          4.182           ms/op
Client.createUser:createUser·p0.99    sample         10.273           ms/op
Client.createUser:createUser·p0.999   sample         17.826           ms/op
Client.createUser:createUser·p0.9999  sample         18.741           ms/op
Client.createUser:createUser·p1.00    sample         18.743           ms/op
Client.existUser                      sample  16400   1.947 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.671           ms/op
Client.existUser:existUser·p0.50      sample          1.888           ms/op
Client.existUser:existUser·p0.90      sample          2.580           ms/op
Client.existUser:existUser·p0.95      sample          2.822           ms/op
Client.existUser:existUser·p0.99      sample          3.658           ms/op
Client.existUser:existUser·p0.999     sample          5.376           ms/op
Client.existUser:existUser·p0.9999    sample          8.296           ms/op
Client.existUser:existUser·p1.00      sample         10.273           ms/op
Client.getUser                        sample  10813   2.957 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.037           ms/op
Client.getUser:getUser·p0.50          sample          2.966           ms/op
Client.getUser:getUser·p0.90          sample          3.723           ms/op
Client.getUser:getUser·p0.95          sample          3.973           ms/op
Client.getUser:getUser·p0.99          sample          5.086           ms/op
Client.getUser:getUser·p0.999         sample          7.865           ms/op
Client.getUser:getUser·p0.9999        sample          8.012           ms/op
Client.getUser:getUser·p1.00          sample          8.012           ms/op
Client.listUser                       sample   3625   8.834 ± 0.120   ms/op
Client.listUser:listUser·p0.00        sample          2.691           ms/op
Client.listUser:listUser·p0.50        sample          8.503           ms/op
Client.listUser:listUser·p0.90        sample         11.829           ms/op
Client.listUser:listUser·p0.95        sample         13.042           ms/op
Client.listUser:listUser·p0.99        sample         15.610           ms/op
Client.listUser:listUser·p0.999       sample         18.161           ms/op
Client.listUser:listUser·p0.9999      sample         18.481           ms/op
Client.listUser:listUser·p1.00        sample         18.481           ms/op
