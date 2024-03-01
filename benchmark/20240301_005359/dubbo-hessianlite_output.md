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
# Warmup Iteration   1: 2.224 ops/ms
Iteration   1: 6.552 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.552 ops/ms


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
# Warmup Iteration   1: 6.088 ops/ms
Iteration   1: 14.802 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.802 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ops/ms
Iteration   1: 8.374 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.374 ops/ms


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
# Warmup Iteration   1: 2.021 ops/ms
Iteration   1: 3.624 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.624 ops/ms


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
# Warmup Iteration   1: 5.443 ±(99.9%) 0.074 ms/op
Iteration   1: 3.226 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.226 ms/op


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
# Warmup Iteration   1: 3.288 ±(99.9%) 0.040 ms/op
Iteration   1: 1.879 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.879 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.048 ms/op
Iteration   1: 2.597 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.597 ms/op


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
# Warmup Iteration   1: 11.601 ±(99.9%) 0.262 ms/op
Iteration   1: 7.996 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.996 ms/op


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.117 ms/op
Iteration   1: 3.076 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   2.818 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  16.843 ms/op
                 createUser·p0.9999: 16.876 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10391
  mean =      3.076 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 2630 
    [ 2.500,  3.750) = 6419 
    [ 3.750,  5.000) = 984 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 2.842 ±(99.9%) 0.057 ms/op
Iteration   1: 1.955 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   1.779 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  24.805 ms/op
                 existUser·p0.9999: 24.915 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16414
  mean =      1.955 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15477 
    [ 2.500,  5.000) = 873 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      1.779 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      3.408 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     24.915 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.092 ms/op
Iteration   1: 3.075 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.097 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 9.171 ms/op
                 getUser·p1.00:   9.191 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10396
  mean =      3.075 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 172 
    [ 2.000,  3.000) = 5116 
    [ 3.000,  4.000) = 4487 
    [ 4.000,  5.000) = 515 
    [ 5.000,  6.000) = 61 
    [ 6.000,  7.000) = 34 
    [ 7.000,  8.000) = 4 
    [ 8.000,  9.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.097 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =      9.171 ms/op
     p(99.9990) =      9.191 ms/op
     p(99.9999) =      9.191 ms/op
    p(100.0000) =      9.191 ms/op


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
# Warmup Iteration   1: 11.991 ±(99.9%) 0.526 ms/op
Iteration   1: 7.305 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   6.881 ms/op
                 listUser·p0.90:   9.373 ms/op
                 listUser·p0.95:   10.503 ms/op
                 listUser·p0.99:   18.612 ms/op
                 listUser·p0.999:  38.981 ms/op
                 listUser·p0.9999: 43.778 ms/op
                 listUser·p1.00:   43.778 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4378
  mean =      7.305 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 412 
    [ 5.000, 10.000) = 3679 
    [10.000, 15.000) = 213 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 8 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.253 ms/op
     p(50.0000) =      6.881 ms/op
     p(90.0000) =      9.373 ms/op
     p(95.0000) =     10.503 ms/op
     p(99.0000) =     18.612 ms/op
     p(99.9000) =     38.981 ms/op
     p(99.9900) =     43.778 ms/op
     p(99.9990) =     43.778 ms/op
     p(99.9999) =     43.778 ms/op
    p(100.0000) =     43.778 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.552          ops/ms
Client.existUser                       thrpt         14.802          ops/ms
Client.getUser                         thrpt          8.374          ops/ms
Client.listUser                        thrpt          3.624          ops/ms
Client.createUser                       avgt          3.226           ms/op
Client.existUser                        avgt          1.879           ms/op
Client.getUser                          avgt          2.597           ms/op
Client.listUser                         avgt          7.996           ms/op
Client.createUser                     sample  10391   3.076 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.124           ms/op
Client.createUser:createUser·p0.50    sample          2.818           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.260           ms/op
Client.createUser:createUser·p0.99    sample          9.191           ms/op
Client.createUser:createUser·p0.999   sample         16.843           ms/op
Client.createUser:createUser·p0.9999  sample         16.876           ms/op
Client.createUser:createUser·p1.00    sample         16.876           ms/op
Client.existUser                      sample  16414   1.955 ± 0.034   ms/op
Client.existUser:existUser·p0.00      sample          0.663           ms/op
Client.existUser:existUser·p0.50      sample          1.779           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.523           ms/op
Client.existUser:existUser·p0.99      sample          3.408           ms/op
Client.existUser:existUser·p0.999     sample         24.805           ms/op
Client.existUser:existUser·p0.9999    sample         24.915           ms/op
Client.existUser:existUser·p1.00      sample         24.936           ms/op
Client.getUser                        sample  10396   3.075 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.598           ms/op
Client.getUser:getUser·p0.50          sample          2.982           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          4.097           ms/op
Client.getUser:getUser·p0.99          sample          4.981           ms/op
Client.getUser:getUser·p0.999         sample          6.988           ms/op
Client.getUser:getUser·p0.9999        sample          9.171           ms/op
Client.getUser:getUser·p1.00          sample          9.191           ms/op
Client.listUser                       sample   4378   7.305 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          2.253           ms/op
Client.listUser:listUser·p0.50        sample          6.881           ms/op
Client.listUser:listUser·p0.90        sample          9.373           ms/op
Client.listUser:listUser·p0.95        sample         10.503           ms/op
Client.listUser:listUser·p0.99        sample         18.612           ms/op
Client.listUser:listUser·p0.999       sample         38.981           ms/op
Client.listUser:listUser·p0.9999      sample         43.778           ms/op
Client.listUser:listUser·p1.00        sample         43.778           ms/op
