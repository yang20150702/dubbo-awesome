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
# Warmup Iteration   1: 2.374 ops/ms
Iteration   1: 5.914 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.914 ops/ms


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
# Warmup Iteration   1: 5.533 ops/ms
Iteration   1: 12.809 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.809 ops/ms


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
# Warmup Iteration   1: 4.510 ops/ms
Iteration   1: 9.281 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.281 ops/ms


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
# Warmup Iteration   1: 2.261 ops/ms
Iteration   1: 3.930 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.930 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.242 ±(99.9%) 0.068 ms/op
Iteration   1: 3.108 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.108 ms/op


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
# Warmup Iteration   1: 3.047 ±(99.9%) 0.032 ms/op
Iteration   1: 1.914 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.914 ms/op


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
# Warmup Iteration   1: 4.968 ±(99.9%) 0.063 ms/op
Iteration   1: 3.209 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.209 ms/op


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
# Warmup Iteration   1: 14.543 ±(99.9%) 0.309 ms/op
Iteration   1: 9.027 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.027 ms/op


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
# Warmup Iteration   1: 5.401 ±(99.9%) 0.124 ms/op
Iteration   1: 3.083 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   2.830 ms/op
                 createUser·p0.90:   4.186 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  15.067 ms/op
                 createUser·p0.9999: 16.122 ms/op
                 createUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10377
  mean =      3.083 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2680 
    [ 2.500,  3.750) = 6005 
    [ 3.750,  5.000) = 1474 
    [ 5.000,  6.250) = 72 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      8.315 ms/op
     p(99.9000) =     15.067 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     16.138 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 2.923 ±(99.9%) 0.078 ms/op
Iteration   1: 1.709 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.571 ms/op
                 existUser·p0.50:   1.608 ms/op
                 existUser·p0.90:   2.034 ms/op
                 existUser·p0.95:   2.261 ms/op
                 existUser·p0.99:   3.144 ms/op
                 existUser·p0.999:  16.433 ms/op
                 existUser·p0.9999: 17.257 ms/op
                 existUser·p1.00:   17.400 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18686
  mean =      1.709 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 452 
    [ 1.250,  2.500) = 17781 
    [ 2.500,  3.750) = 360 
    [ 3.750,  5.000) = 26 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      1.608 ms/op
     p(90.0000) =      2.034 ms/op
     p(95.0000) =      2.261 ms/op
     p(99.0000) =      3.144 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     17.257 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ±(99.9%) 0.104 ms/op
Iteration   1: 3.285 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   4.116 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  16.851 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9743
  mean =      3.285 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1593 
    [ 2.500,  3.750) = 5877 
    [ 3.750,  5.000) = 2064 
    [ 5.000,  6.250) = 130 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     16.851 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     17.203 ms/op
     p(99.9999) =     17.203 ms/op
    p(100.0000) =     17.203 ms/op


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
# Warmup Iteration   1: 12.954 ±(99.9%) 0.551 ms/op
Iteration   1: 8.727 ±(99.9%) 0.125 ms/op
                 listUser·p0.00:   2.138 ms/op
                 listUser·p0.50:   8.372 ms/op
                 listUser·p0.90:   11.207 ms/op
                 listUser·p0.95:   12.884 ms/op
                 listUser·p0.99:   18.523 ms/op
                 listUser·p0.999:  20.010 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3671
  mean =      8.727 ±(99.9%) 0.125 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 58 
    [ 5.000,  7.500) = 1023 
    [ 7.500, 10.000) = 1835 
    [10.000, 12.500) = 546 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.138 ms/op
     p(50.0000) =      8.372 ms/op
     p(90.0000) =     11.207 ms/op
     p(95.0000) =     12.884 ms/op
     p(99.0000) =     18.523 ms/op
     p(99.9000) =     20.010 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     21.561 ms/op
     p(99.9999) =     21.561 ms/op
    p(100.0000) =     21.561 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.914          ops/ms
Client.existUser                       thrpt         12.809          ops/ms
Client.getUser                         thrpt          9.281          ops/ms
Client.listUser                        thrpt          3.930          ops/ms
Client.createUser                       avgt          3.108           ms/op
Client.existUser                        avgt          1.914           ms/op
Client.getUser                          avgt          3.209           ms/op
Client.listUser                         avgt          9.027           ms/op
Client.createUser                     sample  10377   3.083 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.143           ms/op
Client.createUser:createUser·p0.50    sample          2.830           ms/op
Client.createUser:createUser·p0.90    sample          4.186           ms/op
Client.createUser:createUser·p0.95    sample          4.465           ms/op
Client.createUser:createUser·p0.99    sample          8.315           ms/op
Client.createUser:createUser·p0.999   sample         15.067           ms/op
Client.createUser:createUser·p0.9999  sample         16.122           ms/op
Client.createUser:createUser·p1.00    sample         16.138           ms/op
Client.existUser                      sample  18686   1.709 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.571           ms/op
Client.existUser:existUser·p0.50      sample          1.608           ms/op
Client.existUser:existUser·p0.90      sample          2.034           ms/op
Client.existUser:existUser·p0.95      sample          2.261           ms/op
Client.existUser:existUser·p0.99      sample          3.144           ms/op
Client.existUser:existUser·p0.999     sample         16.433           ms/op
Client.existUser:existUser·p0.9999    sample         17.257           ms/op
Client.existUser:existUser·p1.00      sample         17.400           ms/op
Client.getUser                        sample   9743   3.285 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          1.036           ms/op
Client.getUser:getUser·p0.50          sample          3.203           ms/op
Client.getUser:getUser·p0.90          sample          4.116           ms/op
Client.getUser:getUser·p0.95          sample          4.391           ms/op
Client.getUser:getUser·p0.99          sample          5.693           ms/op
Client.getUser:getUser·p0.999         sample         16.851           ms/op
Client.getUser:getUser·p0.9999        sample         17.203           ms/op
Client.getUser:getUser·p1.00          sample         17.203           ms/op
Client.listUser                       sample   3671   8.727 ± 0.125   ms/op
Client.listUser:listUser·p0.00        sample          2.138           ms/op
Client.listUser:listUser·p0.50        sample          8.372           ms/op
Client.listUser:listUser·p0.90        sample         11.207           ms/op
Client.listUser:listUser·p0.95        sample         12.884           ms/op
Client.listUser:listUser·p0.99        sample         18.523           ms/op
Client.listUser:listUser·p0.999       sample         20.010           ms/op
Client.listUser:listUser·p0.9999      sample         21.561           ms/op
Client.listUser:listUser·p1.00        sample         21.561           ms/op
