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
# Warmup Iteration   1: 2.288 ops/ms
Iteration   1: 5.988 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.988 ops/ms


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
# Warmup Iteration   1: 5.580 ops/ms
Iteration   1: 14.272 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.272 ops/ms


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
# Warmup Iteration   1: 4.619 ops/ms
Iteration   1: 8.601 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.601 ops/ms


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
# Warmup Iteration   1: 2.058 ops/ms
Iteration   1: 3.259 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.259 ops/ms


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
# Warmup Iteration   1: 5.395 ±(99.9%) 0.079 ms/op
Iteration   1: 3.396 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.396 ms/op


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
# Warmup Iteration   1: 3.078 ±(99.9%) 0.030 ms/op
Iteration   1: 1.976 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.976 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.063 ms/op
Iteration   1: 3.007 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.007 ms/op


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
# Warmup Iteration   1: 11.577 ±(99.9%) 0.228 ms/op
Iteration   1: 8.924 ±(99.9%) 0.073 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.924 ms/op


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
# Warmup Iteration   1: 5.153 ±(99.9%) 0.113 ms/op
Iteration   1: 3.246 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  14.632 ms/op
                 createUser·p0.9999: 16.024 ms/op
                 createUser·p1.00:   16.024 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9954
  mean =      3.246 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 2077 
    [ 2.500,  3.750) = 5658 
    [ 3.750,  5.000) = 1887 
    [ 5.000,  6.250) = 248 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     14.632 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     16.024 ms/op
     p(99.9999) =     16.024 ms/op
    p(100.0000) =     16.024 ms/op


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
# Warmup Iteration   1: 3.232 ±(99.9%) 0.078 ms/op
Iteration   1: 2.018 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   1.942 ms/op
                 existUser·p0.90:   2.519 ms/op
                 existUser·p0.95:   2.847 ms/op
                 existUser·p0.99:   3.570 ms/op
                 existUser·p0.999:  16.335 ms/op
                 existUser·p0.9999: 17.391 ms/op
                 existUser·p1.00:   17.564 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15847
  mean =      2.018 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 617 
    [ 1.250,  2.500) = 13555 
    [ 2.500,  3.750) = 1554 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      1.942 ms/op
     p(90.0000) =      2.519 ms/op
     p(95.0000) =      2.847 ms/op
     p(99.0000) =      3.570 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     17.391 ms/op
     p(99.9990) =     17.564 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.110 ms/op
Iteration   1: 2.790 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.686 ms/op
                 getUser·p0.50:   2.716 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.655 ms/op
                 getUser·p0.99:   4.738 ms/op
                 getUser·p0.999:  7.299 ms/op
                 getUser·p0.9999: 8.062 ms/op
                 getUser·p1.00:   8.143 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11454
  mean =      2.790 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 13 
    [1.000, 1.500) = 43 
    [1.500, 2.000) = 331 
    [2.000, 2.500) = 2839 
    [2.500, 3.000) = 5156 
    [3.000, 3.500) = 2131 
    [3.500, 4.000) = 674 
    [4.000, 4.500) = 138 
    [4.500, 5.000) = 52 
    [5.000, 5.500) = 42 
    [5.500, 6.000) = 7 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 19 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.716 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.655 ms/op
     p(99.0000) =      4.738 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =      8.062 ms/op
     p(99.9990) =      8.143 ms/op
     p(99.9999) =      8.143 ms/op
    p(100.0000) =      8.143 ms/op


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
# Warmup Iteration   1: 12.770 ±(99.9%) 0.414 ms/op
Iteration   1: 8.967 ±(99.9%) 0.175 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   8.569 ms/op
                 listUser·p0.90:   11.451 ms/op
                 listUser·p0.95:   12.534 ms/op
                 listUser·p0.99:   17.647 ms/op
                 listUser·p0.999:  39.074 ms/op
                 listUser·p0.9999: 40.501 ms/op
                 listUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3590
  mean =      8.967 ±(99.9%) 0.175 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 81 
    [ 5.000, 10.000) = 2690 
    [10.000, 15.000) = 743 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 2 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 17 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.347 ms/op
     p(50.0000) =      8.569 ms/op
     p(90.0000) =     11.451 ms/op
     p(95.0000) =     12.534 ms/op
     p(99.0000) =     17.647 ms/op
     p(99.9000) =     39.074 ms/op
     p(99.9900) =     40.501 ms/op
     p(99.9990) =     40.501 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.988          ops/ms
Client.existUser                       thrpt         14.272          ops/ms
Client.getUser                         thrpt          8.601          ops/ms
Client.listUser                        thrpt          3.259          ops/ms
Client.createUser                       avgt          3.396           ms/op
Client.existUser                        avgt          1.976           ms/op
Client.getUser                          avgt          3.007           ms/op
Client.listUser                         avgt          8.924           ms/op
Client.createUser                     sample   9954   3.246 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          1.044           ms/op
Client.createUser:createUser·p0.50    sample          3.105           ms/op
Client.createUser:createUser·p0.90    sample          4.108           ms/op
Client.createUser:createUser·p0.95    sample          4.448           ms/op
Client.createUser:createUser·p0.99    sample          5.980           ms/op
Client.createUser:createUser·p0.999   sample         14.632           ms/op
Client.createUser:createUser·p0.9999  sample         16.024           ms/op
Client.createUser:createUser·p1.00    sample         16.024           ms/op
Client.existUser                      sample  15847   2.018 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.606           ms/op
Client.existUser:existUser·p0.50      sample          1.942           ms/op
Client.existUser:existUser·p0.90      sample          2.519           ms/op
Client.existUser:existUser·p0.95      sample          2.847           ms/op
Client.existUser:existUser·p0.99      sample          3.570           ms/op
Client.existUser:existUser·p0.999     sample         16.335           ms/op
Client.existUser:existUser·p0.9999    sample         17.391           ms/op
Client.existUser:existUser·p1.00      sample         17.564           ms/op
Client.getUser                        sample  11454   2.790 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          0.686           ms/op
Client.getUser:getUser·p0.50          sample          2.716           ms/op
Client.getUser:getUser·p0.90          sample          3.432           ms/op
Client.getUser:getUser·p0.95          sample          3.655           ms/op
Client.getUser:getUser·p0.99          sample          4.738           ms/op
Client.getUser:getUser·p0.999         sample          7.299           ms/op
Client.getUser:getUser·p0.9999        sample          8.062           ms/op
Client.getUser:getUser·p1.00          sample          8.143           ms/op
Client.listUser                       sample   3590   8.967 ± 0.175   ms/op
Client.listUser:listUser·p0.00        sample          2.347           ms/op
Client.listUser:listUser·p0.50        sample          8.569           ms/op
Client.listUser:listUser·p0.90        sample         11.451           ms/op
Client.listUser:listUser·p0.95        sample         12.534           ms/op
Client.listUser:listUser·p0.99        sample         17.647           ms/op
Client.listUser:listUser·p0.999       sample         39.074           ms/op
Client.listUser:listUser·p0.9999      sample         40.501           ms/op
Client.listUser:listUser·p1.00        sample         40.501           ms/op
