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
# Warmup Iteration   1: 2.261 ops/ms
Iteration   1: 5.886 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.886 ops/ms


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
# Warmup Iteration   1: 6.122 ops/ms
Iteration   1: 12.216 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.216 ops/ms


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
# Warmup Iteration   1: 4.059 ops/ms
Iteration   1: 8.735 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.735 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.842 ops/ms
Iteration   1: 3.303 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.303 ops/ms


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
# Warmup Iteration   1: 5.901 ±(99.9%) 0.078 ms/op
Iteration   1: 2.928 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.928 ms/op


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
# Warmup Iteration   1: 2.941 ±(99.9%) 0.042 ms/op
Iteration   1: 1.893 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.815 ±(99.9%) 0.061 ms/op
Iteration   1: 3.278 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.278 ms/op


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
# Warmup Iteration   1: 12.141 ±(99.9%) 0.228 ms/op
Iteration   1: 10.062 ±(99.9%) 0.196 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.062 ms/op


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
# Warmup Iteration   1: 4.854 ±(99.9%) 0.106 ms/op
Iteration   1: 3.263 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   4.033 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   9.568 ms/op
                 createUser·p0.999:  16.398 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9792
  mean =      3.263 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1032 
    [ 2.500,  3.750) = 7189 
    [ 3.750,  5.000) = 1269 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.033 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     16.398 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     17.105 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 3.114 ±(99.9%) 0.064 ms/op
Iteration   1: 1.845 ±(99.9%) 0.035 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   1.700 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.546 ms/op
                 existUser·p0.99:   3.644 ms/op
                 existUser·p0.999:  32.506 ms/op
                 existUser·p0.9999: 33.148 ms/op
                 existUser·p1.00:   33.292 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17327
  mean =      1.845 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16324 
    [ 2.500,  5.000) = 931 
    [ 5.000,  7.500) = 40 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      1.700 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.546 ms/op
     p(99.0000) =      3.644 ms/op
     p(99.9000) =     32.506 ms/op
     p(99.9900) =     33.148 ms/op
     p(99.9990) =     33.292 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.106 ms/op
Iteration   1: 2.890 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   2.761 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.040 ms/op
                 getUser·p0.99:   5.107 ms/op
                 getUser·p0.999:  7.207 ms/op
                 getUser·p0.9999: 7.667 ms/op
                 getUser·p1.00:   7.684 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11050
  mean =      2.890 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 53 
    [1.500, 2.000) = 412 
    [2.000, 2.500) = 2846 
    [2.500, 3.000) = 3743 
    [3.000, 3.500) = 2125 
    [3.500, 4.000) = 1260 
    [4.000, 4.500) = 375 
    [4.500, 5.000) = 111 
    [5.000, 5.500) = 38 
    [5.500, 6.000) = 30 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 19 
    [7.000, 7.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.791 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.040 ms/op
     p(99.0000) =      5.107 ms/op
     p(99.9000) =      7.207 ms/op
     p(99.9900) =      7.667 ms/op
     p(99.9990) =      7.684 ms/op
     p(99.9999) =      7.684 ms/op
    p(100.0000) =      7.684 ms/op


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
# Warmup Iteration   1: 12.869 ±(99.9%) 0.410 ms/op
Iteration   1: 8.200 ±(99.9%) 0.111 ms/op
                 listUser·p0.00:   3.191 ms/op
                 listUser·p0.50:   7.856 ms/op
                 listUser·p0.90:   11.071 ms/op
                 listUser·p0.95:   12.222 ms/op
                 listUser·p0.99:   14.499 ms/op
                 listUser·p0.999:  20.216 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4002
  mean =      8.200 ±(99.9%) 0.111 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 103 
    [ 5.000,  7.500) = 1563 
    [ 7.500, 10.000) = 1692 
    [10.000, 12.500) = 468 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.191 ms/op
     p(50.0000) =      7.856 ms/op
     p(90.0000) =     11.071 ms/op
     p(95.0000) =     12.222 ms/op
     p(99.0000) =     14.499 ms/op
     p(99.9000) =     20.216 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.886          ops/ms
Client.existUser                       thrpt         12.216          ops/ms
Client.getUser                         thrpt          8.735          ops/ms
Client.listUser                        thrpt          3.303          ops/ms
Client.createUser                       avgt          2.928           ms/op
Client.existUser                        avgt          1.893           ms/op
Client.getUser                          avgt          3.278           ms/op
Client.listUser                         avgt         10.062           ms/op
Client.createUser                     sample   9792   3.263 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.167           ms/op
Client.createUser:createUser·p0.50    sample          2.961           ms/op
Client.createUser:createUser·p0.90    sample          4.033           ms/op
Client.createUser:createUser·p0.95    sample          4.440           ms/op
Client.createUser:createUser·p0.99    sample          9.568           ms/op
Client.createUser:createUser·p0.999   sample         16.398           ms/op
Client.createUser:createUser·p0.9999  sample         17.105           ms/op
Client.createUser:createUser·p1.00    sample         17.105           ms/op
Client.existUser                      sample  17327   1.845 ± 0.035   ms/op
Client.existUser:existUser·p0.00      sample          0.634           ms/op
Client.existUser:existUser·p0.50      sample          1.700           ms/op
Client.existUser:existUser·p0.90      sample          2.359           ms/op
Client.existUser:existUser·p0.95      sample          2.546           ms/op
Client.existUser:existUser·p0.99      sample          3.644           ms/op
Client.existUser:existUser·p0.999     sample         32.506           ms/op
Client.existUser:existUser·p0.9999    sample         33.148           ms/op
Client.existUser:existUser·p1.00      sample         33.292           ms/op
Client.getUser                        sample  11050   2.890 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.791           ms/op
Client.getUser:getUser·p0.50          sample          2.761           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.040           ms/op
Client.getUser:getUser·p0.99          sample          5.107           ms/op
Client.getUser:getUser·p0.999         sample          7.207           ms/op
Client.getUser:getUser·p0.9999        sample          7.667           ms/op
Client.getUser:getUser·p1.00          sample          7.684           ms/op
Client.listUser                       sample   4002   8.200 ± 0.111   ms/op
Client.listUser:listUser·p0.00        sample          3.191           ms/op
Client.listUser:listUser·p0.50        sample          7.856           ms/op
Client.listUser:listUser·p0.90        sample         11.071           ms/op
Client.listUser:listUser·p0.95        sample         12.222           ms/op
Client.listUser:listUser·p0.99        sample         14.499           ms/op
Client.listUser:listUser·p0.999       sample         20.216           ms/op
Client.listUser:listUser·p0.9999      sample         23.429           ms/op
Client.listUser:listUser·p1.00        sample         23.429           ms/op
