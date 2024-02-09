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
# Warmup Iteration   1: 2.259 ops/ms
Iteration   1: 5.314 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.314 ops/ms


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
# Warmup Iteration   1: 5.564 ops/ms
Iteration   1: 13.457 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.457 ops/ms


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
# Warmup Iteration   1: 3.912 ops/ms
Iteration   1: 8.977 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.977 ops/ms


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
# Warmup Iteration   1: 1.829 ops/ms
Iteration   1: 3.449 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.449 ops/ms


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
# Warmup Iteration   1: 5.721 ±(99.9%) 0.101 ms/op
Iteration   1: 3.155 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.155 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.044 ms/op
Iteration   1: 1.956 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.956 ms/op


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
# Warmup Iteration   1: 4.713 ±(99.9%) 0.054 ms/op
Iteration   1: 3.243 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.243 ms/op


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
# Warmup Iteration   1: 14.245 ±(99.9%) 0.248 ms/op
Iteration   1: 9.312 ±(99.9%) 0.135 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.312 ms/op


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
# Warmup Iteration   1: 5.288 ±(99.9%) 0.117 ms/op
Iteration   1: 3.462 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.524 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   7.438 ms/op
                 createUser·p0.999:  9.486 ms/op
                 createUser·p0.9999: 12.386 ms/op
                 createUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9239
  mean =      3.462 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 415 
    [ 2.500,  3.750) = 6702 
    [ 3.750,  5.000) = 1827 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 55 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      7.438 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     12.386 ms/op
     p(99.9990) =     12.386 ms/op
     p(99.9999) =     12.386 ms/op
    p(100.0000) =     12.386 ms/op


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
# Warmup Iteration   1: 2.986 ±(99.9%) 0.065 ms/op
Iteration   1: 1.860 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.875 ms/op
                 existUser·p0.99:   3.563 ms/op
                 existUser·p0.999:  5.030 ms/op
                 existUser·p0.9999: 5.941 ms/op
                 existUser·p1.00:   6.791 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17205
  mean =      1.860 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 72 
    [1.000, 1.500) = 5193 
    [1.500, 2.000) = 6296 
    [2.000, 2.500) = 3633 
    [2.500, 3.000) = 1345 
    [3.000, 3.500) = 465 
    [3.500, 4.000) = 122 
    [4.000, 4.500) = 20 
    [4.500, 5.000) = 38 
    [5.000, 5.500) = 17 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      3.563 ms/op
     p(99.9000) =      5.030 ms/op
     p(99.9900) =      5.941 ms/op
     p(99.9990) =      6.791 ms/op
     p(99.9999) =      6.791 ms/op
    p(100.0000) =      6.791 ms/op


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
# Warmup Iteration   1: 4.842 ±(99.9%) 0.126 ms/op
Iteration   1: 2.966 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.190 ms/op
                 getUser·p0.50:   2.871 ms/op
                 getUser·p0.90:   3.642 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.015 ms/op
                 getUser·p0.999:  6.321 ms/op
                 getUser·p0.9999: 7.220 ms/op
                 getUser·p1.00:   7.242 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10778
  mean =      2.966 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 7 
    [1.500, 2.000) = 136 
    [2.000, 2.500) = 2049 
    [2.500, 3.000) = 4016 
    [3.000, 3.500) = 2964 
    [3.500, 4.000) = 1091 
    [4.000, 4.500) = 262 
    [4.500, 5.000) = 145 
    [5.000, 5.500) = 56 
    [5.500, 6.000) = 12 
    [6.000, 6.500) = 37 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.190 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.642 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.015 ms/op
     p(99.9000) =      6.321 ms/op
     p(99.9900) =      7.220 ms/op
     p(99.9990) =      7.242 ms/op
     p(99.9999) =      7.242 ms/op
    p(100.0000) =      7.242 ms/op


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
# Warmup Iteration   1: 14.832 ±(99.9%) 0.681 ms/op
Iteration   1: 8.167 ±(99.9%) 0.170 ms/op
                 listUser·p0.00:   2.728 ms/op
                 listUser·p0.50:   7.602 ms/op
                 listUser·p0.90:   10.879 ms/op
                 listUser·p0.95:   12.269 ms/op
                 listUser·p0.99:   24.559 ms/op
                 listUser·p0.999:  31.528 ms/op
                 listUser·p0.9999: 59.638 ms/op
                 listUser·p1.00:   59.638 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3922
  mean =      8.167 ±(99.9%) 0.170 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221 
    [ 5.000, 10.000) = 3120 
    [10.000, 15.000) = 491 
    [15.000, 20.000) = 28 
    [20.000, 25.000) = 24 
    [25.000, 30.000) = 27 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.728 ms/op
     p(50.0000) =      7.602 ms/op
     p(90.0000) =     10.879 ms/op
     p(95.0000) =     12.269 ms/op
     p(99.0000) =     24.559 ms/op
     p(99.9000) =     31.528 ms/op
     p(99.9900) =     59.638 ms/op
     p(99.9990) =     59.638 ms/op
     p(99.9999) =     59.638 ms/op
    p(100.0000) =     59.638 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.314          ops/ms
Client.existUser                       thrpt         13.457          ops/ms
Client.getUser                         thrpt          8.977          ops/ms
Client.listUser                        thrpt          3.449          ops/ms
Client.createUser                       avgt          3.155           ms/op
Client.existUser                        avgt          1.956           ms/op
Client.getUser                          avgt          3.243           ms/op
Client.listUser                         avgt          9.312           ms/op
Client.createUser                     sample   9239   3.462 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          1.524           ms/op
Client.createUser:createUser·p0.50    sample          3.387           ms/op
Client.createUser:createUser·p0.90    sample          4.133           ms/op
Client.createUser:createUser·p0.95    sample          4.637           ms/op
Client.createUser:createUser·p0.99    sample          7.438           ms/op
Client.createUser:createUser·p0.999   sample          9.486           ms/op
Client.createUser:createUser·p0.9999  sample         12.386           ms/op
Client.createUser:createUser·p1.00    sample         12.386           ms/op
Client.existUser                      sample  17205   1.860 ± 0.014   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          1.753           ms/op
Client.existUser:existUser·p0.90      sample          2.564           ms/op
Client.existUser:existUser·p0.95      sample          2.875           ms/op
Client.existUser:existUser·p0.99      sample          3.563           ms/op
Client.existUser:existUser·p0.999     sample          5.030           ms/op
Client.existUser:existUser·p0.9999    sample          5.941           ms/op
Client.existUser:existUser·p1.00      sample          6.791           ms/op
Client.getUser                        sample  10778   2.966 ± 0.019   ms/op
Client.getUser:getUser·p0.00          sample          1.190           ms/op
Client.getUser:getUser·p0.50          sample          2.871           ms/op
Client.getUser:getUser·p0.90          sample          3.642           ms/op
Client.getUser:getUser·p0.95          sample          3.965           ms/op
Client.getUser:getUser·p0.99          sample          5.015           ms/op
Client.getUser:getUser·p0.999         sample          6.321           ms/op
Client.getUser:getUser·p0.9999        sample          7.220           ms/op
Client.getUser:getUser·p1.00          sample          7.242           ms/op
Client.listUser                       sample   3922   8.167 ± 0.170   ms/op
Client.listUser:listUser·p0.00        sample          2.728           ms/op
Client.listUser:listUser·p0.50        sample          7.602           ms/op
Client.listUser:listUser·p0.90        sample         10.879           ms/op
Client.listUser:listUser·p0.95        sample         12.269           ms/op
Client.listUser:listUser·p0.99        sample         24.559           ms/op
Client.listUser:listUser·p0.999       sample         31.528           ms/op
Client.listUser:listUser·p0.9999      sample         59.638           ms/op
Client.listUser:listUser·p1.00        sample         59.638           ms/op
