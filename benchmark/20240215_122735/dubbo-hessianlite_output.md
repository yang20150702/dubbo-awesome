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
# Warmup Iteration   1: 1.998 ops/ms
Iteration   1: 5.466 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.466 ops/ms


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
# Warmup Iteration   1: 5.764 ops/ms
Iteration   1: 11.440 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.440 ops/ms


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
# Warmup Iteration   1: 3.844 ops/ms
Iteration   1: 7.356 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.356 ops/ms


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
# Warmup Iteration   1: 2.011 ops/ms
Iteration   1: 3.775 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.775 ops/ms


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
# Warmup Iteration   1: 5.330 ±(99.9%) 0.075 ms/op
Iteration   1: 3.294 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.294 ms/op


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.049 ms/op
Iteration   1: 2.064 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.064 ms/op


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
# Warmup Iteration   1: 5.277 ±(99.9%) 0.060 ms/op
Iteration   1: 3.173 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.173 ms/op


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
# Warmup Iteration   1: 13.971 ±(99.9%) 0.353 ms/op
Iteration   1: 9.139 ±(99.9%) 0.126 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.139 ms/op


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
# Warmup Iteration   1: 5.665 ±(99.9%) 0.190 ms/op
Iteration   1: 3.057 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.065 ms/op
                 createUser·p0.50:   2.900 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.667 ms/op
                 createUser·p0.999:  17.039 ms/op
                 createUser·p0.9999: 18.525 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10561
  mean =      3.057 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2940 
    [ 2.500,  3.750) = 6349 
    [ 3.750,  5.000) = 991 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 14 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      6.667 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     18.525 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.216 ±(99.9%) 0.116 ms/op
Iteration   1: 1.859 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   1.729 ms/op
                 existUser·p0.90:   2.355 ms/op
                 existUser·p0.95:   2.617 ms/op
                 existUser·p0.99:   3.987 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17234
  mean =      1.859 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 411 
    [ 1.250,  2.500) = 15646 
    [ 2.500,  3.750) = 968 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      1.729 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.617 ms/op
     p(99.0000) =      3.987 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.285 ms/op
     p(99.9990) =     18.285 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.434 ±(99.9%) 0.284 ms/op
Iteration   1: 2.996 ±(99.9%) 0.046 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   2.826 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   6.320 ms/op
                 getUser·p0.999:  25.722 ms/op
                 getUser·p0.9999: 26.243 ms/op
                 getUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10675
  mean =      2.996 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3444 
    [ 2.500,  5.000) = 7016 
    [ 5.000,  7.500) = 145 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.958 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.320 ms/op
     p(99.9000) =     25.722 ms/op
     p(99.9900) =     26.243 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 11.917 ±(99.9%) 0.391 ms/op
Iteration   1: 9.323 ±(99.9%) 0.184 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   8.634 ms/op
                 listUser·p0.90:   12.337 ms/op
                 listUser·p0.95:   13.985 ms/op
                 listUser·p0.99:   24.290 ms/op
                 listUser·p0.999:  33.029 ms/op
                 listUser·p0.9999: 33.948 ms/op
                 listUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3433
  mean =      9.323 ±(99.9%) 0.184 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 38 
    [ 5.000,  7.500) = 853 
    [ 7.500, 10.000) = 1526 
    [10.000, 12.500) = 706 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.466 ms/op
     p(50.0000) =      8.634 ms/op
     p(90.0000) =     12.337 ms/op
     p(95.0000) =     13.985 ms/op
     p(99.0000) =     24.290 ms/op
     p(99.9000) =     33.029 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     33.948 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.466          ops/ms
Client.existUser                       thrpt         11.440          ops/ms
Client.getUser                         thrpt          7.356          ops/ms
Client.listUser                        thrpt          3.775          ops/ms
Client.createUser                       avgt          3.294           ms/op
Client.existUser                        avgt          2.064           ms/op
Client.getUser                          avgt          3.173           ms/op
Client.listUser                         avgt          9.139           ms/op
Client.createUser                     sample  10561   3.057 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.065           ms/op
Client.createUser:createUser·p0.50    sample          2.900           ms/op
Client.createUser:createUser·p0.90    sample          3.912           ms/op
Client.createUser:createUser·p0.95    sample          4.596           ms/op
Client.createUser:createUser·p0.99    sample          6.667           ms/op
Client.createUser:createUser·p0.999   sample         17.039           ms/op
Client.createUser:createUser·p0.9999  sample         18.525           ms/op
Client.createUser:createUser·p1.00    sample         18.547           ms/op
Client.existUser                      sample  17234   1.859 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.465           ms/op
Client.existUser:existUser·p0.50      sample          1.729           ms/op
Client.existUser:existUser·p0.90      sample          2.355           ms/op
Client.existUser:existUser·p0.95      sample          2.617           ms/op
Client.existUser:existUser·p0.99      sample          3.987           ms/op
Client.existUser:existUser·p0.999     sample         18.219           ms/op
Client.existUser:existUser·p0.9999    sample         18.285           ms/op
Client.existUser:existUser·p1.00      sample         18.285           ms/op
Client.getUser                        sample  10675   2.996 ± 0.046   ms/op
Client.getUser:getUser·p0.00          sample          0.958           ms/op
Client.getUser:getUser·p0.50          sample          2.826           ms/op
Client.getUser:getUser·p0.90          sample          3.727           ms/op
Client.getUser:getUser·p0.95          sample          4.096           ms/op
Client.getUser:getUser·p0.99          sample          6.320           ms/op
Client.getUser:getUser·p0.999         sample         25.722           ms/op
Client.getUser:getUser·p0.9999        sample         26.243           ms/op
Client.getUser:getUser·p1.00          sample         26.247           ms/op
Client.listUser                       sample   3433   9.323 ± 0.184   ms/op
Client.listUser:listUser·p0.00        sample          2.466           ms/op
Client.listUser:listUser·p0.50        sample          8.634           ms/op
Client.listUser:listUser·p0.90        sample         12.337           ms/op
Client.listUser:listUser·p0.95        sample         13.985           ms/op
Client.listUser:listUser·p0.99        sample         24.290           ms/op
Client.listUser:listUser·p0.999       sample         33.029           ms/op
Client.listUser:listUser·p0.9999      sample         33.948           ms/op
Client.listUser:listUser·p1.00        sample         33.948           ms/op
