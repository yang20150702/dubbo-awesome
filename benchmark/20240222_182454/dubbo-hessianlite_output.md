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
# Warmup Iteration   1: 1.830 ops/ms
Iteration   1: 5.308 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.308 ops/ms


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
# Warmup Iteration   1: 5.550 ops/ms
Iteration   1: 12.677 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.677 ops/ms


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
# Warmup Iteration   1: 4.266 ops/ms
Iteration   1: 8.703 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.703 ops/ms


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
# Warmup Iteration   1: 1.751 ops/ms
Iteration   1: 3.205 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.205 ops/ms


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
# Warmup Iteration   1: 5.994 ±(99.9%) 0.093 ms/op
Iteration   1: 3.374 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.374 ms/op


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.055 ms/op
Iteration   1: 2.220 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.220 ms/op


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
# Warmup Iteration   1: 5.450 ±(99.9%) 0.081 ms/op
Iteration   1: 3.081 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.081 ms/op


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
# Warmup Iteration   1: 11.578 ±(99.9%) 0.232 ms/op
Iteration   1: 8.582 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.582 ms/op


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
# Warmup Iteration   1: 5.221 ±(99.9%) 0.129 ms/op
Iteration   1: 3.366 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   5.251 ms/op
                 createUser·p0.99:   7.980 ms/op
                 createUser·p0.999:  11.330 ms/op
                 createUser·p0.9999: 12.894 ms/op
                 createUser·p1.00:   12.894 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9489
  mean =      3.366 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1207 
    [ 2.500,  3.750) = 6345 
    [ 3.750,  5.000) = 1420 
    [ 5.000,  6.250) = 288 
    [ 6.250,  7.500) = 101 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      7.980 ms/op
     p(99.9000) =     11.330 ms/op
     p(99.9900) =     12.894 ms/op
     p(99.9990) =     12.894 ms/op
     p(99.9999) =     12.894 ms/op
    p(100.0000) =     12.894 ms/op


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
# Warmup Iteration   1: 3.205 ±(99.9%) 0.074 ms/op
Iteration   1: 1.783 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.463 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.175 ms/op
                 existUser·p0.95:   2.384 ms/op
                 existUser·p0.99:   3.730 ms/op
                 existUser·p0.999:  20.742 ms/op
                 existUser·p0.9999: 21.653 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18018
  mean =      1.783 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17392 
    [ 2.500,  5.000) = 553 
    [ 5.000,  7.500) = 41 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.175 ms/op
     p(95.0000) =      2.384 ms/op
     p(99.0000) =      3.730 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     21.653 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.339 ±(99.9%) 0.105 ms/op
Iteration   1: 3.323 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.402 ms/op
                 getUser·p0.999:  8.969 ms/op
                 getUser·p0.9999: 10.158 ms/op
                 getUser·p1.00:   10.158 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9653
  mean =      3.323 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 4 
    [ 1.000,  2.000) = 81 
    [ 2.000,  3.000) = 3831 
    [ 3.000,  4.000) = 4464 
    [ 4.000,  5.000) = 939 
    [ 5.000,  6.000) = 189 
    [ 6.000,  7.000) = 90 
    [ 7.000,  8.000) = 21 
    [ 8.000,  9.000) = 25 
    [ 9.000, 10.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      6.402 ms/op
     p(99.9000) =      8.969 ms/op
     p(99.9900) =     10.158 ms/op
     p(99.9990) =     10.158 ms/op
     p(99.9999) =     10.158 ms/op
    p(100.0000) =     10.158 ms/op


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
# Warmup Iteration   1: 11.841 ±(99.9%) 0.420 ms/op
Iteration   1: 9.173 ±(99.9%) 0.145 ms/op
                 listUser·p0.00:   3.072 ms/op
                 listUser·p0.50:   8.700 ms/op
                 listUser·p0.90:   12.075 ms/op
                 listUser·p0.95:   13.966 ms/op
                 listUser·p0.99:   18.353 ms/op
                 listUser·p0.999:  24.105 ms/op
                 listUser·p0.9999: 25.395 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3491
  mean =      9.173 ±(99.9%) 0.145 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 38 
    [ 5.000,  7.500) = 843 
    [ 7.500, 10.000) = 1612 
    [10.000, 12.500) = 734 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.072 ms/op
     p(50.0000) =      8.700 ms/op
     p(90.0000) =     12.075 ms/op
     p(95.0000) =     13.966 ms/op
     p(99.0000) =     18.353 ms/op
     p(99.9000) =     24.105 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     25.395 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.308          ops/ms
Client.existUser                       thrpt         12.677          ops/ms
Client.getUser                         thrpt          8.703          ops/ms
Client.listUser                        thrpt          3.205          ops/ms
Client.createUser                       avgt          3.374           ms/op
Client.existUser                        avgt          2.220           ms/op
Client.getUser                          avgt          3.081           ms/op
Client.listUser                         avgt          8.582           ms/op
Client.createUser                     sample   9489   3.366 ± 0.036   ms/op
Client.createUser:createUser·p0.00    sample          0.788           ms/op
Client.createUser:createUser·p0.50    sample          3.199           ms/op
Client.createUser:createUser·p0.90    sample          4.317           ms/op
Client.createUser:createUser·p0.95    sample          5.251           ms/op
Client.createUser:createUser·p0.99    sample          7.980           ms/op
Client.createUser:createUser·p0.999   sample         11.330           ms/op
Client.createUser:createUser·p0.9999  sample         12.894           ms/op
Client.createUser:createUser·p1.00    sample         12.894           ms/op
Client.existUser                      sample  18018   1.783 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.463           ms/op
Client.existUser:existUser·p0.50      sample          1.661           ms/op
Client.existUser:existUser·p0.90      sample          2.175           ms/op
Client.existUser:existUser·p0.95      sample          2.384           ms/op
Client.existUser:existUser·p0.99      sample          3.730           ms/op
Client.existUser:existUser·p0.999     sample         20.742           ms/op
Client.existUser:existUser·p0.9999    sample         21.653           ms/op
Client.existUser:existUser·p1.00      sample         21.889           ms/op
Client.getUser                        sample   9653   3.323 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.745           ms/op
Client.getUser:getUser·p0.50          sample          3.203           ms/op
Client.getUser:getUser·p0.90          sample          4.157           ms/op
Client.getUser:getUser·p0.95          sample          4.628           ms/op
Client.getUser:getUser·p0.99          sample          6.402           ms/op
Client.getUser:getUser·p0.999         sample          8.969           ms/op
Client.getUser:getUser·p0.9999        sample         10.158           ms/op
Client.getUser:getUser·p1.00          sample         10.158           ms/op
Client.listUser                       sample   3491   9.173 ± 0.145   ms/op
Client.listUser:listUser·p0.00        sample          3.072           ms/op
Client.listUser:listUser·p0.50        sample          8.700           ms/op
Client.listUser:listUser·p0.90        sample         12.075           ms/op
Client.listUser:listUser·p0.95        sample         13.966           ms/op
Client.listUser:listUser·p0.99        sample         18.353           ms/op
Client.listUser:listUser·p0.999       sample         24.105           ms/op
Client.listUser:listUser·p0.9999      sample         25.395           ms/op
Client.listUser:listUser·p1.00        sample         25.395           ms/op
