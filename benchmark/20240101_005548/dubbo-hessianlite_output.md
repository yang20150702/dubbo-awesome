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
# Warmup Iteration   1: 2.464 ops/ms
Iteration   1: 5.253 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.253 ops/ms


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
# Warmup Iteration   1: 6.231 ops/ms
Iteration   1: 12.296 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.296 ops/ms


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
# Warmup Iteration   1: 3.681 ops/ms
Iteration   1: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.229 ops/ms


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
# Warmup Iteration   1: 2.284 ops/ms
Iteration   1: 3.729 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.729 ops/ms


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
# Warmup Iteration   1: 5.469 ±(99.9%) 0.076 ms/op
Iteration   1: 3.222 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.222 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.033 ms/op
Iteration   1: 1.916 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.916 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.061 ms/op
Iteration   1: 3.200 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.200 ms/op


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
# Warmup Iteration   1: 13.974 ±(99.9%) 0.305 ms/op
Iteration   1: 8.197 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.197 ms/op


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
# Warmup Iteration   1: 4.738 ±(99.9%) 0.096 ms/op
Iteration   1: 3.049 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   6.206 ms/op
                 createUser·p0.999:  15.687 ms/op
                 createUser·p0.9999: 16.477 ms/op
                 createUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10522
  mean =      3.049 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 2360 
    [ 2.500,  3.750) = 7135 
    [ 3.750,  5.000) = 840 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.206 ms/op
     p(99.9000) =     15.687 ms/op
     p(99.9900) =     16.477 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.085 ms/op
Iteration   1: 1.790 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.514 ms/op
                 existUser·p0.50:   1.747 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   3.658 ms/op
                 existUser·p0.999:  13.139 ms/op
                 existUser·p0.9999: 13.209 ms/op
                 existUser·p1.00:   13.222 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18070
  mean =      1.790 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1509 
    [ 1.250,  2.500) = 15965 
    [ 2.500,  3.750) = 425 
    [ 3.750,  5.000) = 71 
    [ 5.000,  6.250) = 35 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      1.747 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.658 ms/op
     p(99.9000) =     13.139 ms/op
     p(99.9900) =     13.209 ms/op
     p(99.9990) =     13.222 ms/op
     p(99.9999) =     13.222 ms/op
    p(100.0000) =     13.222 ms/op


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.119 ms/op
Iteration   1: 2.925 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.227 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  29.789 ms/op
                 getUser·p0.9999: 30.140 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10925
  mean =      2.925 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4361 
    [ 2.500,  5.000) = 6344 
    [ 5.000,  7.500) = 144 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     29.789 ms/op
     p(99.9900) =     30.140 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 13.809 ±(99.9%) 0.383 ms/op
Iteration   1: 8.918 ±(99.9%) 0.185 ms/op
                 listUser·p0.00:   2.486 ms/op
                 listUser·p0.50:   8.364 ms/op
                 listUser·p0.90:   11.783 ms/op
                 listUser·p0.95:   13.633 ms/op
                 listUser·p0.99:   24.237 ms/op
                 listUser·p0.999:  34.931 ms/op
                 listUser·p0.9999: 35.455 ms/op
                 listUser·p1.00:   35.455 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3577
  mean =      8.918 ±(99.9%) 0.185 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 83 
    [ 5.000,  7.500) = 1064 
    [ 7.500, 10.000) = 1566 
    [10.000, 12.500) = 612 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.486 ms/op
     p(50.0000) =      8.364 ms/op
     p(90.0000) =     11.783 ms/op
     p(95.0000) =     13.633 ms/op
     p(99.0000) =     24.237 ms/op
     p(99.9000) =     34.931 ms/op
     p(99.9900) =     35.455 ms/op
     p(99.9990) =     35.455 ms/op
     p(99.9999) =     35.455 ms/op
    p(100.0000) =     35.455 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.253          ops/ms
Client.existUser                       thrpt         12.296          ops/ms
Client.getUser                         thrpt          8.229          ops/ms
Client.listUser                        thrpt          3.729          ops/ms
Client.createUser                       avgt          3.222           ms/op
Client.existUser                        avgt          1.916           ms/op
Client.getUser                          avgt          3.200           ms/op
Client.listUser                         avgt          8.197           ms/op
Client.createUser                     sample  10522   3.049 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.057           ms/op
Client.createUser:createUser·p0.50    sample          2.990           ms/op
Client.createUser:createUser·p0.90    sample          3.731           ms/op
Client.createUser:createUser·p0.95    sample          4.051           ms/op
Client.createUser:createUser·p0.99    sample          6.206           ms/op
Client.createUser:createUser·p0.999   sample         15.687           ms/op
Client.createUser:createUser·p0.9999  sample         16.477           ms/op
Client.createUser:createUser·p1.00    sample         16.515           ms/op
Client.existUser                      sample  18070   1.790 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.514           ms/op
Client.existUser:existUser·p0.50      sample          1.747           ms/op
Client.existUser:existUser·p0.90      sample          2.208           ms/op
Client.existUser:existUser·p0.95      sample          2.384           ms/op
Client.existUser:existUser·p0.99      sample          3.658           ms/op
Client.existUser:existUser·p0.999     sample         13.139           ms/op
Client.existUser:existUser·p0.9999    sample         13.209           ms/op
Client.existUser:existUser·p1.00      sample         13.222           ms/op
Client.getUser                        sample  10925   2.925 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample          0.874           ms/op
Client.getUser:getUser·p0.50          sample          2.617           ms/op
Client.getUser:getUser·p0.90          sample          3.924           ms/op
Client.getUser:getUser·p0.95          sample          4.227           ms/op
Client.getUser:getUser·p0.99          sample          6.300           ms/op
Client.getUser:getUser·p0.999         sample         29.789           ms/op
Client.getUser:getUser·p0.9999        sample         30.140           ms/op
Client.getUser:getUser·p1.00          sample         30.147           ms/op
Client.listUser                       sample   3577   8.918 ± 0.185   ms/op
Client.listUser:listUser·p0.00        sample          2.486           ms/op
Client.listUser:listUser·p0.50        sample          8.364           ms/op
Client.listUser:listUser·p0.90        sample         11.783           ms/op
Client.listUser:listUser·p0.95        sample         13.633           ms/op
Client.listUser:listUser·p0.99        sample         24.237           ms/op
Client.listUser:listUser·p0.999       sample         34.931           ms/op
Client.listUser:listUser·p0.9999      sample         35.455           ms/op
Client.listUser:listUser·p1.00        sample         35.455           ms/op
