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
# Warmup Iteration   1: 1.880 ops/ms
Iteration   1: 5.442 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.442 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.822 ops/ms
Iteration   1: 11.444 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.444 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.579 ops/ms
Iteration   1: 7.344 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.344 ops/ms


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
# Warmup Iteration   1: 1.558 ops/ms
Iteration   1: 2.920 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.920 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.734 ±(99.9%) 0.069 ms/op
Iteration   1: 3.485 ±(99.9%) 0.046 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.485 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.052 ms/op
Iteration   1: 2.162 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.162 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.804 ±(99.9%) 0.096 ms/op
Iteration   1: 3.808 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.808 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 15.802 ±(99.9%) 0.297 ms/op
Iteration   1: 10.178 ±(99.9%) 0.284 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.178 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.646 ±(99.9%) 0.164 ms/op
Iteration   1: 3.480 ±(99.9%) 0.081 ms/op
                 createUser·p0.00:   0.741 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   4.281 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   10.819 ms/op
                 createUser·p0.999:  38.863 ms/op
                 createUser·p0.9999: 40.501 ms/op
                 createUser·p1.00:   40.501 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9333
  mean =      3.480 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8873 
    [ 5.000, 10.000) = 347 
    [10.000, 15.000) = 81 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 31 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      4.281 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =     10.819 ms/op
     p(99.9000) =     38.863 ms/op
     p(99.9900) =     40.501 ms/op
     p(99.9990) =     40.501 ms/op
     p(99.9999) =     40.501 ms/op
    p(100.0000) =     40.501 ms/op


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
# Warmup Iteration   1: 3.415 ±(99.9%) 0.095 ms/op
Iteration   1: 2.102 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   1.980 ms/op
                 existUser·p0.90:   2.539 ms/op
                 existUser·p0.95:   2.793 ms/op
                 existUser·p0.99:   6.072 ms/op
                 existUser·p0.999:  20.218 ms/op
                 existUser·p0.9999: 30.182 ms/op
                 existUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15241
  mean =      2.102 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13545 
    [ 2.500,  5.000) = 1528 
    [ 5.000,  7.500) = 50 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.539 ms/op
     p(95.0000) =      2.793 ms/op
     p(99.0000) =      6.072 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     30.182 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.145 ms/op
Iteration   1: 3.894 ±(99.9%) 0.056 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.690 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.956 ms/op
                 getUser·p0.99:   9.216 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 21.168 ms/op
                 getUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 8225
  mean =      3.894 ±(99.9%) 0.056 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 471 
    [ 2.500,  5.000) = 6959 
    [ 5.000,  7.500) = 620 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      9.216 ms/op
     p(99.9000) =     20.972 ms/op
     p(99.9900) =     21.168 ms/op
     p(99.9990) =     21.168 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 14.083 ±(99.9%) 0.534 ms/op
Iteration   1: 9.209 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   3.310 ms/op
                 listUser·p0.50:   8.897 ms/op
                 listUser·p0.90:   12.419 ms/op
                 listUser·p0.95:   13.861 ms/op
                 listUser·p0.99:   16.712 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3478
  mean =      9.209 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 48 
    [ 5.000,  7.500) = 802 
    [ 7.500, 10.000) = 1564 
    [10.000, 12.500) = 733 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.310 ms/op
     p(50.0000) =      8.897 ms/op
     p(90.0000) =     12.419 ms/op
     p(95.0000) =     13.861 ms/op
     p(99.0000) =     16.712 ms/op
     p(99.9000) =     21.299 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.442          ops/ms
Client.existUser                       thrpt         11.444          ops/ms
Client.getUser                         thrpt          7.344          ops/ms
Client.listUser                        thrpt          2.920          ops/ms
Client.createUser                       avgt          3.485           ms/op
Client.existUser                        avgt          2.162           ms/op
Client.getUser                          avgt          3.808           ms/op
Client.listUser                         avgt         10.178           ms/op
Client.createUser                     sample   9333   3.480 ± 0.081   ms/op
Client.createUser:createUser·p0.00    sample          0.741           ms/op
Client.createUser:createUser·p0.50    sample          3.092           ms/op
Client.createUser:createUser·p0.90    sample          4.281           ms/op
Client.createUser:createUser·p0.95    sample          4.973           ms/op
Client.createUser:createUser·p0.99    sample         10.819           ms/op
Client.createUser:createUser·p0.999   sample         38.863           ms/op
Client.createUser:createUser·p0.9999  sample         40.501           ms/op
Client.createUser:createUser·p1.00    sample         40.501           ms/op
Client.existUser                      sample  15241   2.102 ± 0.032   ms/op
Client.existUser:existUser·p0.00      sample          0.641           ms/op
Client.existUser:existUser·p0.50      sample          1.980           ms/op
Client.existUser:existUser·p0.90      sample          2.539           ms/op
Client.existUser:existUser·p0.95      sample          2.793           ms/op
Client.existUser:existUser·p0.99      sample          6.072           ms/op
Client.existUser:existUser·p0.999     sample         20.218           ms/op
Client.existUser:existUser·p0.9999    sample         30.182           ms/op
Client.existUser:existUser·p1.00      sample         34.734           ms/op
Client.getUser                        sample   8225   3.894 ± 0.056   ms/op
Client.getUser:getUser·p0.00          sample          0.768           ms/op
Client.getUser:getUser·p0.50          sample          3.690           ms/op
Client.getUser:getUser·p0.90          sample          4.956           ms/op
Client.getUser:getUser·p0.95          sample          5.956           ms/op
Client.getUser:getUser·p0.99          sample          9.216           ms/op
Client.getUser:getUser·p0.999         sample         20.972           ms/op
Client.getUser:getUser·p0.9999        sample         21.168           ms/op
Client.getUser:getUser·p1.00          sample         21.168           ms/op
Client.listUser                       sample   3478   9.209 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          3.310           ms/op
Client.listUser:listUser·p0.50        sample          8.897           ms/op
Client.listUser:listUser·p0.90        sample         12.419           ms/op
Client.listUser:listUser·p0.95        sample         13.861           ms/op
Client.listUser:listUser·p0.99        sample         16.712           ms/op
Client.listUser:listUser·p0.999       sample         21.299           ms/op
Client.listUser:listUser·p0.9999      sample         25.625           ms/op
Client.listUser:listUser·p1.00        sample         25.625           ms/op
