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
# Warmup Iteration   1: 2.102 ops/ms
Iteration   1: 5.993 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.993 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.031 ops/ms
Iteration   1: 12.413 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.413 ops/ms


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
# Warmup Iteration   1: 4.104 ops/ms
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
# Warmup Iteration   1: 2.019 ops/ms
Iteration   1: 3.536 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.536 ops/ms


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
# Warmup Iteration   1: 6.301 ±(99.9%) 0.105 ms/op
Iteration   1: 3.172 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
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
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.167 ±(99.9%) 0.032 ms/op
Iteration   1: 1.831 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.831 ms/op


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.078 ms/op
Iteration   1: 3.515 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.515 ms/op


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
# Warmup Iteration   1: 12.319 ±(99.9%) 0.290 ms/op
Iteration   1: 8.809 ±(99.9%) 0.083 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.809 ms/op


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
# Warmup Iteration   1: 5.232 ±(99.9%) 0.124 ms/op
Iteration   1: 3.246 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.307 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   4.080 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   8.131 ms/op
                 createUser·p0.999:  15.748 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9844
  mean =      3.246 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1308 
    [ 2.500,  3.750) = 6709 
    [ 3.750,  5.000) = 1587 
    [ 5.000,  6.250) = 106 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      8.131 ms/op
     p(99.9000) =     15.748 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     17.400 ms/op
     p(99.9999) =     17.400 ms/op
    p(100.0000) =     17.400 ms/op


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
# Warmup Iteration   1: 3.218 ±(99.9%) 0.087 ms/op
Iteration   1: 1.905 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   1.817 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.457 ms/op
                 existUser·p0.99:   3.683 ms/op
                 existUser·p0.999:  24.026 ms/op
                 existUser·p0.9999: 24.280 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16781
  mean =      1.905 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16029 
    [ 2.500,  5.000) = 671 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.817 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.457 ms/op
     p(99.0000) =      3.683 ms/op
     p(99.9000) =     24.026 ms/op
     p(99.9900) =     24.280 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.113 ms/op
Iteration   1: 3.422 ±(99.9%) 0.148 ms/op
                 getUser·p0.00:   0.611 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.516 ms/op
                 getUser·p0.999:  76.580 ms/op
                 getUser·p0.9999: 87.032 ms/op
                 getUser·p1.00:   87.032 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9371
  mean =      3.422 ±(99.9%) 0.148 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 9169 
    [ 5.000, 10.000) = 163 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 
    [55.000, 60.000) = 0 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 15 
    [75.000, 80.000) = 13 
    [80.000, 85.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.516 ms/op
     p(99.9000) =     76.580 ms/op
     p(99.9900) =     87.032 ms/op
     p(99.9990) =     87.032 ms/op
     p(99.9999) =     87.032 ms/op
    p(100.0000) =     87.032 ms/op


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
# Warmup Iteration   1: 15.570 ±(99.9%) 0.690 ms/op
Iteration   1: 10.140 ±(99.9%) 0.192 ms/op
                 listUser·p0.00:   2.920 ms/op
                 listUser·p0.50:   9.617 ms/op
                 listUser·p0.90:   13.320 ms/op
                 listUser·p0.95:   14.680 ms/op
                 listUser·p0.99:   27.237 ms/op
                 listUser·p0.999:  33.986 ms/op
                 listUser·p0.9999: 36.110 ms/op
                 listUser·p1.00:   36.110 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3139
  mean =     10.140 ±(99.9%) 0.192 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 25 
    [ 5.000,  7.500) = 428 
    [ 7.500, 10.000) = 1306 
    [10.000, 12.500) = 870 
    [12.500, 15.000) = 377 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.920 ms/op
     p(50.0000) =      9.617 ms/op
     p(90.0000) =     13.320 ms/op
     p(95.0000) =     14.680 ms/op
     p(99.0000) =     27.237 ms/op
     p(99.9000) =     33.986 ms/op
     p(99.9900) =     36.110 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.993          ops/ms
Client.existUser                       thrpt         12.413          ops/ms
Client.getUser                         thrpt          8.354          ops/ms
Client.listUser                        thrpt          3.536          ops/ms
Client.createUser                       avgt          3.172           ms/op
Client.existUser                        avgt          1.831           ms/op
Client.getUser                          avgt          3.515           ms/op
Client.listUser                         avgt          8.809           ms/op
Client.createUser                     sample   9844   3.246 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.307           ms/op
Client.createUser:createUser·p0.50    sample          3.043           ms/op
Client.createUser:createUser·p0.90    sample          4.080           ms/op
Client.createUser:createUser·p0.95    sample          4.391           ms/op
Client.createUser:createUser·p0.99    sample          8.131           ms/op
Client.createUser:createUser·p0.999   sample         15.748           ms/op
Client.createUser:createUser·p0.9999  sample         17.400           ms/op
Client.createUser:createUser·p1.00    sample         17.400           ms/op
Client.existUser                      sample  16781   1.905 ± 0.027   ms/op
Client.existUser:existUser·p0.00      sample          0.705           ms/op
Client.existUser:existUser·p0.50      sample          1.817           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.457           ms/op
Client.existUser:existUser·p0.99      sample          3.683           ms/op
Client.existUser:existUser·p0.999     sample         24.026           ms/op
Client.existUser:existUser·p0.9999    sample         24.280           ms/op
Client.existUser:existUser·p1.00      sample         24.347           ms/op
Client.getUser                        sample   9371   3.422 ± 0.148   ms/op
Client.getUser:getUser·p0.00          sample          0.611           ms/op
Client.getUser:getUser·p0.50          sample          3.121           ms/op
Client.getUser:getUser·p0.90          sample          4.153           ms/op
Client.getUser:getUser·p0.95          sample          4.538           ms/op
Client.getUser:getUser·p0.99          sample          6.516           ms/op
Client.getUser:getUser·p0.999         sample         76.580           ms/op
Client.getUser:getUser·p0.9999        sample         87.032           ms/op
Client.getUser:getUser·p1.00          sample         87.032           ms/op
Client.listUser                       sample   3139  10.140 ± 0.192   ms/op
Client.listUser:listUser·p0.00        sample          2.920           ms/op
Client.listUser:listUser·p0.50        sample          9.617           ms/op
Client.listUser:listUser·p0.90        sample         13.320           ms/op
Client.listUser:listUser·p0.95        sample         14.680           ms/op
Client.listUser:listUser·p0.99        sample         27.237           ms/op
Client.listUser:listUser·p0.999       sample         33.986           ms/op
Client.listUser:listUser·p0.9999      sample         36.110           ms/op
Client.listUser:listUser·p1.00        sample         36.110           ms/op
