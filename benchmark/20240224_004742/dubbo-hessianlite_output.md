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
# Warmup Iteration   1: 1.870 ops/ms
Iteration   1: 5.761 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.761 ops/ms


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
# Warmup Iteration   1: 5.538 ops/ms
Iteration   1: 12.570 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.570 ops/ms


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
# Warmup Iteration   1: 4.515 ops/ms
Iteration   1: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.354 ops/ms


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
# Warmup Iteration   1: 2.292 ops/ms
Iteration   1: 3.627 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.627 ops/ms


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
# Warmup Iteration   1: 5.327 ±(99.9%) 0.085 ms/op
Iteration   1: 3.167 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.167 ms/op


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
# Warmup Iteration   1: 3.209 ±(99.9%) 0.034 ms/op
Iteration   1: 1.743 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.743 ms/op


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.056 ms/op
Iteration   1: 3.172 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.172 ms/op


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
# Warmup Iteration   1: 13.022 ±(99.9%) 0.195 ms/op
Iteration   1: 8.307 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.307 ms/op


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
# Warmup Iteration   1: 5.271 ±(99.9%) 0.126 ms/op
Iteration   1: 2.865 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   2.679 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   6.922 ms/op
                 createUser·p0.999:  11.625 ms/op
                 createUser·p0.9999: 12.826 ms/op
                 createUser·p1.00:   12.829 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11460
  mean =      2.865 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3468 
    [ 2.500,  3.750) = 6889 
    [ 3.750,  5.000) = 833 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      2.679 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     11.625 ms/op
     p(99.9900) =     12.826 ms/op
     p(99.9990) =     12.829 ms/op
     p(99.9999) =     12.829 ms/op
    p(100.0000) =     12.829 ms/op


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
# Warmup Iteration   1: 3.146 ±(99.9%) 0.066 ms/op
Iteration   1: 2.108 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   1.933 ms/op
                 existUser·p0.90:   2.720 ms/op
                 existUser·p0.95:   2.994 ms/op
                 existUser·p0.99:   4.044 ms/op
                 existUser·p0.999:  15.218 ms/op
                 existUser·p0.9999: 23.036 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15173
  mean =      2.108 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12905 
    [ 2.500,  5.000) = 2166 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.720 ms/op
     p(95.0000) =      2.994 ms/op
     p(99.0000) =      4.044 ms/op
     p(99.9000) =     15.218 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.094 ms/op
Iteration   1: 3.291 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.831 ms/op
                 getUser·p0.999:  12.669 ms/op
                 getUser·p0.9999: 15.925 ms/op
                 getUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9725
  mean =      3.291 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 21 
    [ 1.250,  2.500) = 1564 
    [ 2.500,  3.750) = 6049 
    [ 3.750,  5.000) = 1838 
    [ 5.000,  6.250) = 177 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.831 ms/op
     p(99.9000) =     12.669 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     15.925 ms/op
     p(99.9999) =     15.925 ms/op
    p(100.0000) =     15.925 ms/op


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
# Warmup Iteration   1: 13.753 ±(99.9%) 0.499 ms/op
Iteration   1: 8.291 ±(99.9%) 0.113 ms/op
                 listUser·p0.00:   3.023 ms/op
                 listUser·p0.50:   7.856 ms/op
                 listUser·p0.90:   10.718 ms/op
                 listUser·p0.95:   12.059 ms/op
                 listUser·p0.99:   16.337 ms/op
                 listUser·p0.999:  21.581 ms/op
                 listUser·p0.9999: 22.970 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3837
  mean =      8.291 ±(99.9%) 0.113 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 53 
    [ 5.000,  7.500) = 1419 
    [ 7.500, 10.000) = 1804 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.023 ms/op
     p(50.0000) =      7.856 ms/op
     p(90.0000) =     10.718 ms/op
     p(95.0000) =     12.059 ms/op
     p(99.0000) =     16.337 ms/op
     p(99.9000) =     21.581 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     22.970 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.761          ops/ms
Client.existUser                       thrpt         12.570          ops/ms
Client.getUser                         thrpt          8.354          ops/ms
Client.listUser                        thrpt          3.627          ops/ms
Client.createUser                       avgt          3.167           ms/op
Client.existUser                        avgt          1.743           ms/op
Client.getUser                          avgt          3.172           ms/op
Client.listUser                         avgt          8.307           ms/op
Client.createUser                     sample  11460   2.865 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.362           ms/op
Client.createUser:createUser·p0.50    sample          2.679           ms/op
Client.createUser:createUser·p0.90    sample          3.703           ms/op
Client.createUser:createUser·p0.95    sample          4.366           ms/op
Client.createUser:createUser·p0.99    sample          6.922           ms/op
Client.createUser:createUser·p0.999   sample         11.625           ms/op
Client.createUser:createUser·p0.9999  sample         12.826           ms/op
Client.createUser:createUser·p1.00    sample         12.829           ms/op
Client.existUser                      sample  15173   2.108 ± 0.029   ms/op
Client.existUser:existUser·p0.00      sample          0.647           ms/op
Client.existUser:existUser·p0.50      sample          1.933           ms/op
Client.existUser:existUser·p0.90      sample          2.720           ms/op
Client.existUser:existUser·p0.95      sample          2.994           ms/op
Client.existUser:existUser·p0.99      sample          4.044           ms/op
Client.existUser:existUser·p0.999     sample         15.218           ms/op
Client.existUser:existUser·p0.9999    sample         23.036           ms/op
Client.existUser:existUser·p1.00      sample         23.036           ms/op
Client.getUser                        sample   9725   3.291 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          0.898           ms/op
Client.getUser:getUser·p0.50          sample          3.260           ms/op
Client.getUser:getUser·p0.90          sample          4.133           ms/op
Client.getUser:getUser·p0.95          sample          4.571           ms/op
Client.getUser:getUser·p0.99          sample          5.831           ms/op
Client.getUser:getUser·p0.999         sample         12.669           ms/op
Client.getUser:getUser·p0.9999        sample         15.925           ms/op
Client.getUser:getUser·p1.00          sample         15.925           ms/op
Client.listUser                       sample   3837   8.291 ± 0.113   ms/op
Client.listUser:listUser·p0.00        sample          3.023           ms/op
Client.listUser:listUser·p0.50        sample          7.856           ms/op
Client.listUser:listUser·p0.90        sample         10.718           ms/op
Client.listUser:listUser·p0.95        sample         12.059           ms/op
Client.listUser:listUser·p0.99        sample         16.337           ms/op
Client.listUser:listUser·p0.999       sample         21.581           ms/op
Client.listUser:listUser·p0.9999      sample         22.970           ms/op
Client.listUser:listUser·p1.00        sample         22.970           ms/op
