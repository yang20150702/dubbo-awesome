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
# Warmup Iteration   1: 2.129 ops/ms
Iteration   1: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.625 ops/ms


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
# Warmup Iteration   1: 5.831 ops/ms
Iteration   1: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.874 ops/ms


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
# Warmup Iteration   1: 3.553 ops/ms
Iteration   1: 8.709 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.709 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.821 ops/ms
Iteration   1: 3.492 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.492 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.116 ±(99.9%) 0.067 ms/op
Iteration   1: 3.180 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.180 ms/op


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
# Warmup Iteration   1: 3.463 ±(99.9%) 0.034 ms/op
Iteration   1: 2.032 ±(99.9%) 0.008 ms/op


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
# Warmup Iteration   1: 5.480 ±(99.9%) 0.086 ms/op
Iteration   1: 3.058 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.058 ms/op


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
# Warmup Iteration   1: 11.878 ±(99.9%) 0.172 ms/op
Iteration   1: 9.568 ±(99.9%) 0.105 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.568 ms/op


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
# Warmup Iteration   1: 5.054 ±(99.9%) 0.118 ms/op
Iteration   1: 3.094 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.761 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.869 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 22.113 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10336
  mean =      3.094 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3051 
    [ 2.500,  5.000) = 6820 
    [ 5.000,  7.500) = 334 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.965 ms/op
     p(50.0000) =      2.761 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.869 ms/op
     p(99.9000) =     20.840 ms/op
     p(99.9900) =     22.113 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.070 ms/op
Iteration   1: 1.869 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.599 ms/op
                 existUser·p0.50:   1.831 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   3.187 ms/op
                 existUser·p0.999:  4.042 ms/op
                 existUser·p0.9999: 5.546 ms/op
                 existUser·p1.00:   5.726 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17114
  mean =      1.869 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 87 
    [1.000, 1.500) = 2122 
    [1.500, 2.000) = 9455 
    [2.000, 2.500) = 4581 
    [2.500, 3.000) = 647 
    [3.000, 3.500) = 103 
    [3.500, 4.000) = 89 
    [4.000, 4.500) = 26 
    [4.500, 5.000) = 2 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      1.831 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      3.187 ms/op
     p(99.9000) =      4.042 ms/op
     p(99.9900) =      5.546 ms/op
     p(99.9990) =      5.726 ms/op
     p(99.9999) =      5.726 ms/op
    p(100.0000) =      5.726 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.146 ms/op
Iteration   1: 3.320 ±(99.9%) 0.058 ms/op
                 getUser·p0.00:   1.182 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   4.106 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.449 ms/op
                 getUser·p0.999:  31.523 ms/op
                 getUser·p0.9999: 32.473 ms/op
                 getUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9635
  mean =      3.320 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 979 
    [ 2.500,  5.000) = 8426 
    [ 5.000,  7.500) = 186 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.106 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.449 ms/op
     p(99.9000) =     31.523 ms/op
     p(99.9900) =     32.473 ms/op
     p(99.9990) =     32.473 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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
# Warmup Iteration   1: 13.802 ±(99.9%) 0.450 ms/op
Iteration   1: 8.372 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   8.069 ms/op
                 listUser·p0.90:   10.781 ms/op
                 listUser·p0.95:   11.977 ms/op
                 listUser·p0.99:   16.155 ms/op
                 listUser·p0.999:  20.706 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3822
  mean =      8.372 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 97 
    [ 5.000,  7.500) = 1279 
    [ 7.500, 10.000) = 1858 
    [10.000, 12.500) = 427 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      8.069 ms/op
     p(90.0000) =     10.781 ms/op
     p(95.0000) =     11.977 ms/op
     p(99.0000) =     16.155 ms/op
     p(99.9000) =     20.706 ms/op
     p(99.9900) =     21.758 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.625          ops/ms
Client.existUser                       thrpt         12.874          ops/ms
Client.getUser                         thrpt          8.709          ops/ms
Client.listUser                        thrpt          3.492          ops/ms
Client.createUser                       avgt          3.180           ms/op
Client.existUser                        avgt          2.032           ms/op
Client.getUser                          avgt          3.058           ms/op
Client.listUser                         avgt          9.568           ms/op
Client.createUser                     sample  10336   3.094 ± 0.047   ms/op
Client.createUser:createUser·p0.00    sample          0.965           ms/op
Client.createUser:createUser·p0.50    sample          2.761           ms/op
Client.createUser:createUser·p0.90    sample          4.178           ms/op
Client.createUser:createUser·p0.95    sample          4.874           ms/op
Client.createUser:createUser·p0.99    sample          7.869           ms/op
Client.createUser:createUser·p0.999   sample         20.840           ms/op
Client.createUser:createUser·p0.9999  sample         22.113           ms/op
Client.createUser:createUser·p1.00    sample         22.118           ms/op
Client.existUser                      sample  17114   1.869 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.599           ms/op
Client.existUser:existUser·p0.50      sample          1.831           ms/op
Client.existUser:existUser·p0.90      sample          2.314           ms/op
Client.existUser:existUser·p0.95      sample          2.507           ms/op
Client.existUser:existUser·p0.99      sample          3.187           ms/op
Client.existUser:existUser·p0.999     sample          4.042           ms/op
Client.existUser:existUser·p0.9999    sample          5.546           ms/op
Client.existUser:existUser·p1.00      sample          5.726           ms/op
Client.getUser                        sample   9635   3.320 ± 0.058   ms/op
Client.getUser:getUser·p0.00          sample          1.182           ms/op
Client.getUser:getUser·p0.50          sample          3.047           ms/op
Client.getUser:getUser·p0.90          sample          4.106           ms/op
Client.getUser:getUser·p0.95          sample          4.522           ms/op
Client.getUser:getUser·p0.99          sample          6.449           ms/op
Client.getUser:getUser·p0.999         sample         31.523           ms/op
Client.getUser:getUser·p0.9999        sample         32.473           ms/op
Client.getUser:getUser·p1.00          sample         32.473           ms/op
Client.listUser                       sample   3822   8.372 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          1.298           ms/op
Client.listUser:listUser·p0.50        sample          8.069           ms/op
Client.listUser:listUser·p0.90        sample         10.781           ms/op
Client.listUser:listUser·p0.95        sample         11.977           ms/op
Client.listUser:listUser·p0.99        sample         16.155           ms/op
Client.listUser:listUser·p0.999       sample         20.706           ms/op
Client.listUser:listUser·p0.9999      sample         21.758           ms/op
Client.listUser:listUser·p1.00        sample         21.758           ms/op
