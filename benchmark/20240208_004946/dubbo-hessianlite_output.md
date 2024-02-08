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
# Warmup Iteration   1: 2.352 ops/ms
Iteration   1: 6.443 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.443 ops/ms


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
# Warmup Iteration   1: 6.712 ops/ms
Iteration   1: 13.718 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.718 ops/ms


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
# Warmup Iteration   1: 4.738 ops/ms
Iteration   1: 9.393 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.393 ops/ms


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
# Warmup Iteration   1: 2.178 ops/ms
Iteration   1: 3.708 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.708 ops/ms


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
# Warmup Iteration   1: 5.096 ±(99.9%) 0.067 ms/op
Iteration   1: 3.072 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.072 ms/op


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
# Warmup Iteration   1: 3.579 ±(99.9%) 0.043 ms/op
Iteration   1: 1.827 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.827 ms/op


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.046 ms/op
Iteration   1: 3.082 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.082 ms/op


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
# Warmup Iteration   1: 12.199 ±(99.9%) 0.291 ms/op
Iteration   1: 7.874 ±(99.9%) 0.066 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.874 ms/op


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.114 ms/op
Iteration   1: 3.390 ±(99.9%) 0.187 ms/op
                 createUser·p0.00:   1.319 ms/op
                 createUser·p0.50:   2.810 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.455 ms/op
                 createUser·p0.99:   9.388 ms/op
                 createUser·p0.999:  95.949 ms/op
                 createUser·p0.9999: 112.460 ms/op
                 createUser·p1.00:   112.460 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9482
  mean =      3.390 ±(99.9%) 0.187 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 9411 
    [ 12.500,  25.000) = 39 
    [ 25.000,  37.500) = 0 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 31 
    [100.000, 112.500) = 1 
    [112.500, 125.000) = 0 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.455 ms/op
     p(99.0000) =      9.388 ms/op
     p(99.9000) =     95.949 ms/op
     p(99.9900) =    112.460 ms/op
     p(99.9990) =    112.460 ms/op
     p(99.9999) =    112.460 ms/op
    p(100.0000) =    112.460 ms/op


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
# Warmup Iteration   1: 2.593 ±(99.9%) 0.055 ms/op
Iteration   1: 1.868 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   1.759 ms/op
                 existUser·p0.90:   2.314 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   3.080 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 15.291 ms/op
                 existUser·p1.00:   15.303 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17107
  mean =      1.868 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 16137 
    [ 2.500,  3.750) = 650 
    [ 3.750,  5.000) = 65 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 7 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.314 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      3.080 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     15.291 ms/op
     p(99.9990) =     15.303 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 4.334 ±(99.9%) 0.104 ms/op
Iteration   1: 3.095 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  6.545 ms/op
                 getUser·p0.9999: 6.799 ms/op
                 getUser·p1.00:   6.799 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10328
  mean =      3.095 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 19 
    [1.500, 2.000) = 84 
    [2.000, 2.500) = 1364 
    [2.500, 3.000) = 3911 
    [3.000, 3.500) = 2557 
    [3.500, 4.000) = 1522 
    [4.000, 4.500) = 549 
    [4.500, 5.000) = 208 
    [5.000, 5.500) = 37 
    [5.500, 6.000) = 19 
    [6.000, 6.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.071 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =      6.799 ms/op
     p(99.9990) =      6.799 ms/op
     p(99.9999) =      6.799 ms/op
    p(100.0000) =      6.799 ms/op


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
# Warmup Iteration   1: 12.319 ±(99.9%) 0.402 ms/op
Iteration   1: 7.667 ±(99.9%) 0.121 ms/op
                 listUser·p0.00:   1.462 ms/op
                 listUser·p0.50:   7.291 ms/op
                 listUser·p0.90:   9.830 ms/op
                 listUser·p0.95:   10.999 ms/op
                 listUser·p0.99:   19.768 ms/op
                 listUser·p0.999:  24.835 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4236
  mean =      7.667 ±(99.9%) 0.121 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 164 
    [ 5.000,  7.500) = 2187 
    [ 7.500, 10.000) = 1494 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.462 ms/op
     p(50.0000) =      7.291 ms/op
     p(90.0000) =      9.830 ms/op
     p(95.0000) =     10.999 ms/op
     p(99.0000) =     19.768 ms/op
     p(99.9000) =     24.835 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     26.345 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt    Score   Error   Units
Client.createUser                      thrpt           6.443          ops/ms
Client.existUser                       thrpt          13.718          ops/ms
Client.getUser                         thrpt           9.393          ops/ms
Client.listUser                        thrpt           3.708          ops/ms
Client.createUser                       avgt           3.072           ms/op
Client.existUser                        avgt           1.827           ms/op
Client.getUser                          avgt           3.082           ms/op
Client.listUser                         avgt           7.874           ms/op
Client.createUser                     sample   9482    3.390 ± 0.187   ms/op
Client.createUser:createUser·p0.00    sample           1.319           ms/op
Client.createUser:createUser·p0.50    sample           2.810           ms/op
Client.createUser:createUser·p0.90    sample           4.018           ms/op
Client.createUser:createUser·p0.95    sample           4.455           ms/op
Client.createUser:createUser·p0.99    sample           9.388           ms/op
Client.createUser:createUser·p0.999   sample          95.949           ms/op
Client.createUser:createUser·p0.9999  sample         112.460           ms/op
Client.createUser:createUser·p1.00    sample         112.460           ms/op
Client.existUser                      sample  17107    1.868 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample           0.577           ms/op
Client.existUser:existUser·p0.50      sample           1.759           ms/op
Client.existUser:existUser·p0.90      sample           2.314           ms/op
Client.existUser:existUser·p0.95      sample           2.466           ms/op
Client.existUser:existUser·p0.99      sample           3.080           ms/op
Client.existUser:existUser·p0.999     sample          14.893           ms/op
Client.existUser:existUser·p0.9999    sample          15.291           ms/op
Client.existUser:existUser·p1.00      sample          15.303           ms/op
Client.getUser                        sample  10328    3.095 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample           0.621           ms/op
Client.getUser:getUser·p0.50          sample           2.953           ms/op
Client.getUser:getUser·p0.90          sample           3.920           ms/op
Client.getUser:getUser·p0.95          sample           4.276           ms/op
Client.getUser:getUser·p0.99          sample           5.071           ms/op
Client.getUser:getUser·p0.999         sample           6.545           ms/op
Client.getUser:getUser·p0.9999        sample           6.799           ms/op
Client.getUser:getUser·p1.00          sample           6.799           ms/op
Client.listUser                       sample   4236    7.667 ± 0.121   ms/op
Client.listUser:listUser·p0.00        sample           1.462           ms/op
Client.listUser:listUser·p0.50        sample           7.291           ms/op
Client.listUser:listUser·p0.90        sample           9.830           ms/op
Client.listUser:listUser·p0.95        sample          10.999           ms/op
Client.listUser:listUser·p0.99        sample          19.768           ms/op
Client.listUser:listUser·p0.999       sample          24.835           ms/op
Client.listUser:listUser·p0.9999      sample          26.345           ms/op
Client.listUser:listUser·p1.00        sample          26.345           ms/op
