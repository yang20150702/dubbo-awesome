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
# Warmup Iteration   1: 2.231 ops/ms
Iteration   1: 5.379 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.379 ops/ms


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
# Warmup Iteration   1: 5.713 ops/ms
Iteration   1: 11.445 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.445 ops/ms


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
# Warmup Iteration   1: 5.048 ops/ms
Iteration   1: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  10.578 ops/ms


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
# Warmup Iteration   1: 2.149 ops/ms
Iteration   1: 3.719 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.719 ops/ms


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
# Warmup Iteration   1: 5.342 ±(99.9%) 0.079 ms/op
Iteration   1: 2.847 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.847 ms/op


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
# Warmup Iteration   1: 2.910 ±(99.9%) 0.033 ms/op
Iteration   1: 1.848 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.848 ms/op


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.068 ms/op
Iteration   1: 2.954 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.954 ms/op


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
# Warmup Iteration   1: 12.976 ±(99.9%) 0.244 ms/op
Iteration   1: 7.485 ±(99.9%) 0.091 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.485 ms/op


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
# Warmup Iteration   1: 4.642 ±(99.9%) 0.101 ms/op
Iteration   1: 2.954 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.728 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   9.241 ms/op
                 createUser·p0.999:  14.877 ms/op
                 createUser·p0.9999: 15.581 ms/op
                 createUser·p1.00:   15.598 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10863
  mean =      2.954 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 14 
    [ 1.250,  2.500) = 2338 
    [ 2.500,  3.750) = 7632 
    [ 3.750,  5.000) = 579 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 8 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.728 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     15.598 ms/op
     p(99.9999) =     15.598 ms/op
    p(100.0000) =     15.598 ms/op


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
# Warmup Iteration   1: 3.028 ±(99.9%) 0.067 ms/op
Iteration   1: 1.912 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.389 ms/op
                 existUser·p0.50:   1.821 ms/op
                 existUser·p0.90:   2.515 ms/op
                 existUser·p0.95:   2.679 ms/op
                 existUser·p0.99:   3.138 ms/op
                 existUser·p0.999:  4.964 ms/op
                 existUser·p0.9999: 5.804 ms/op
                 existUser·p1.00:   5.980 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16724
  mean =      1.912 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 1 
    [0.500, 1.000) = 99 
    [1.000, 1.500) = 2022 
    [1.500, 2.000) = 8568 
    [2.000, 2.500) = 4263 
    [2.500, 3.000) = 1494 
    [3.000, 3.500) = 210 
    [3.500, 4.000) = 34 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 11 
    [5.000, 5.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.389 ms/op
     p(50.0000) =      1.821 ms/op
     p(90.0000) =      2.515 ms/op
     p(95.0000) =      2.679 ms/op
     p(99.0000) =      3.138 ms/op
     p(99.9000) =      4.964 ms/op
     p(99.9900) =      5.804 ms/op
     p(99.9990) =      5.980 ms/op
     p(99.9999) =      5.980 ms/op
    p(100.0000) =      5.980 ms/op


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.091 ms/op
Iteration   1: 3.056 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   5.001 ms/op
                 getUser·p0.999:  6.517 ms/op
                 getUser·p0.9999: 8.233 ms/op
                 getUser·p1.00:   8.249 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10474
  mean =      3.056 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 39 
    [1.500, 2.000) = 205 
    [2.000, 2.500) = 2194 
    [2.500, 3.000) = 2660 
    [3.000, 3.500) = 3008 
    [3.500, 4.000) = 1621 
    [4.000, 4.500) = 500 
    [4.500, 5.000) = 143 
    [5.000, 5.500) = 63 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 17 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      5.001 ms/op
     p(99.9000) =      6.517 ms/op
     p(99.9900) =      8.233 ms/op
     p(99.9990) =      8.249 ms/op
     p(99.9999) =      8.249 ms/op
    p(100.0000) =      8.249 ms/op


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
# Warmup Iteration   1: 12.931 ±(99.9%) 0.451 ms/op
Iteration   1: 8.846 ±(99.9%) 0.139 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   8.454 ms/op
                 listUser·p0.90:   11.798 ms/op
                 listUser·p0.95:   13.404 ms/op
                 listUser·p0.99:   17.285 ms/op
                 listUser·p0.999:  23.320 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3648
  mean =      8.846 ±(99.9%) 0.139 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 58 
    [ 5.000,  7.500) = 1133 
    [ 7.500, 10.000) = 1506 
    [10.000, 12.500) = 703 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      8.454 ms/op
     p(90.0000) =     11.798 ms/op
     p(95.0000) =     13.404 ms/op
     p(99.0000) =     17.285 ms/op
     p(99.9000) =     23.320 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     27.525 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.379          ops/ms
Client.existUser                       thrpt         11.445          ops/ms
Client.getUser                         thrpt         10.578          ops/ms
Client.listUser                        thrpt          3.719          ops/ms
Client.createUser                       avgt          2.847           ms/op
Client.existUser                        avgt          1.848           ms/op
Client.getUser                          avgt          2.954           ms/op
Client.listUser                         avgt          7.485           ms/op
Client.createUser                     sample  10863   2.954 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          0.695           ms/op
Client.createUser:createUser·p0.50    sample          2.728           ms/op
Client.createUser:createUser·p0.90    sample          3.527           ms/op
Client.createUser:createUser·p0.95    sample          4.325           ms/op
Client.createUser:createUser·p0.99    sample          9.241           ms/op
Client.createUser:createUser·p0.999   sample         14.877           ms/op
Client.createUser:createUser·p0.9999  sample         15.581           ms/op
Client.createUser:createUser·p1.00    sample         15.598           ms/op
Client.existUser                      sample  16724   1.912 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.389           ms/op
Client.existUser:existUser·p0.50      sample          1.821           ms/op
Client.existUser:existUser·p0.90      sample          2.515           ms/op
Client.existUser:existUser·p0.95      sample          2.679           ms/op
Client.existUser:existUser·p0.99      sample          3.138           ms/op
Client.existUser:existUser·p0.999     sample          4.964           ms/op
Client.existUser:existUser·p0.9999    sample          5.804           ms/op
Client.existUser:existUser·p1.00      sample          5.980           ms/op
Client.getUser                        sample  10474   3.056 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          1.065           ms/op
Client.getUser:getUser·p0.50          sample          3.031           ms/op
Client.getUser:getUser·p0.90          sample          3.838           ms/op
Client.getUser:getUser·p0.95          sample          4.153           ms/op
Client.getUser:getUser·p0.99          sample          5.001           ms/op
Client.getUser:getUser·p0.999         sample          6.517           ms/op
Client.getUser:getUser·p0.9999        sample          8.233           ms/op
Client.getUser:getUser·p1.00          sample          8.249           ms/op
Client.listUser                       sample   3648   8.846 ± 0.139   ms/op
Client.listUser:listUser·p0.00        sample          1.724           ms/op
Client.listUser:listUser·p0.50        sample          8.454           ms/op
Client.listUser:listUser·p0.90        sample         11.798           ms/op
Client.listUser:listUser·p0.95        sample         13.404           ms/op
Client.listUser:listUser·p0.99        sample         17.285           ms/op
Client.listUser:listUser·p0.999       sample         23.320           ms/op
Client.listUser:listUser·p0.9999      sample         27.525           ms/op
Client.listUser:listUser·p1.00        sample         27.525           ms/op
