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
# Warmup Iteration   1: 2.199 ops/ms
Iteration   1: 5.173 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.173 ops/ms


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
# Warmup Iteration   1: 5.787 ops/ms
Iteration   1: 12.660 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.660 ops/ms


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
# Warmup Iteration   1: 3.948 ops/ms
Iteration   1: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.022 ops/ms


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
# Warmup Iteration   1: 2.295 ops/ms
Iteration   1: 3.076 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.076 ops/ms


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
# Warmup Iteration   1: 5.977 ±(99.9%) 0.095 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.444 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.034 ms/op
Iteration   1: 1.772 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.772 ms/op


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
# Warmup Iteration   1: 4.514 ±(99.9%) 0.054 ms/op
Iteration   1: 3.192 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.192 ms/op


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
# Warmup Iteration   1: 14.137 ±(99.9%) 0.267 ms/op
Iteration   1: 9.792 ±(99.9%) 0.162 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.792 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.104 ms/op
Iteration   1: 3.046 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.391 ms/op
                 createUser·p0.99:   6.996 ms/op
                 createUser·p0.999:  16.425 ms/op
                 createUser·p0.9999: 18.021 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10488
  mean =      3.046 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 2931 
    [ 2.500,  3.750) = 6303 
    [ 3.750,  5.000) = 982 
    [ 5.000,  6.250) = 127 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     16.425 ms/op
     p(99.9900) =     18.021 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 3.217 ±(99.9%) 0.073 ms/op
Iteration   1: 1.984 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.562 ms/op
                 existUser·p0.50:   1.880 ms/op
                 existUser·p0.90:   2.417 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   3.244 ms/op
                 existUser·p0.999:  19.460 ms/op
                 existUser·p0.9999: 20.223 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16126
  mean =      1.984 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14969 
    [ 2.500,  5.000) = 1111 
    [ 5.000,  7.500) = 14 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      1.880 ms/op
     p(90.0000) =      2.417 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.244 ms/op
     p(99.9000) =     19.460 ms/op
     p(99.9900) =     20.223 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.103 ms/op
Iteration   1: 3.375 ±(99.9%) 0.087 ms/op
                 getUser·p0.00:   1.319 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.998 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  35.586 ms/op
                 getUser·p0.9999: 38.273 ms/op
                 getUser·p1.00:   38.273 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9521
  mean =      3.375 ±(99.9%) 0.087 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1909 
    [ 2.500,  5.000) = 7365 
    [ 5.000,  7.500) = 164 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.319 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     35.586 ms/op
     p(99.9900) =     38.273 ms/op
     p(99.9990) =     38.273 ms/op
     p(99.9999) =     38.273 ms/op
    p(100.0000) =     38.273 ms/op


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
# Warmup Iteration   1: 13.154 ±(99.9%) 0.520 ms/op
Iteration   1: 8.892 ±(99.9%) 0.119 ms/op
                 listUser·p0.00:   2.318 ms/op
                 listUser·p0.50:   8.684 ms/op
                 listUser·p0.90:   11.375 ms/op
                 listUser·p0.95:   12.501 ms/op
                 listUser·p0.99:   15.679 ms/op
                 listUser·p0.999:  20.493 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3616
  mean =      8.892 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 64 
    [ 5.000,  7.500) = 814 
    [ 7.500, 10.000) = 1847 
    [10.000, 12.500) = 708 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.318 ms/op
     p(50.0000) =      8.684 ms/op
     p(90.0000) =     11.375 ms/op
     p(95.0000) =     12.501 ms/op
     p(99.0000) =     15.679 ms/op
     p(99.9000) =     20.493 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     20.873 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.173          ops/ms
Client.existUser                       thrpt         12.660          ops/ms
Client.getUser                         thrpt          8.022          ops/ms
Client.listUser                        thrpt          3.076          ops/ms
Client.createUser                       avgt          3.444           ms/op
Client.existUser                        avgt          1.772           ms/op
Client.getUser                          avgt          3.192           ms/op
Client.listUser                         avgt          9.792           ms/op
Client.createUser                     sample  10488   3.046 ± 0.038   ms/op
Client.createUser:createUser·p0.00    sample          1.031           ms/op
Client.createUser:createUser·p0.50    sample          2.908           ms/op
Client.createUser:createUser·p0.90    sample          3.912           ms/op
Client.createUser:createUser·p0.95    sample          4.391           ms/op
Client.createUser:createUser·p0.99    sample          6.996           ms/op
Client.createUser:createUser·p0.999   sample         16.425           ms/op
Client.createUser:createUser·p0.9999  sample         18.021           ms/op
Client.createUser:createUser·p1.00    sample         18.022           ms/op
Client.existUser                      sample  16126   1.984 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.562           ms/op
Client.existUser:existUser·p0.50      sample          1.880           ms/op
Client.existUser:existUser·p0.90      sample          2.417           ms/op
Client.existUser:existUser·p0.95      sample          2.601           ms/op
Client.existUser:existUser·p0.99      sample          3.244           ms/op
Client.existUser:existUser·p0.999     sample         19.460           ms/op
Client.existUser:existUser·p0.9999    sample         20.223           ms/op
Client.existUser:existUser·p1.00      sample         20.283           ms/op
Client.getUser                        sample   9521   3.375 ± 0.087   ms/op
Client.getUser:getUser·p0.00          sample          1.319           ms/op
Client.getUser:getUser·p0.50          sample          3.166           ms/op
Client.getUser:getUser·p0.90          sample          3.998           ms/op
Client.getUser:getUser·p0.95          sample          4.268           ms/op
Client.getUser:getUser·p0.99          sample          6.152           ms/op
Client.getUser:getUser·p0.999         sample         35.586           ms/op
Client.getUser:getUser·p0.9999        sample         38.273           ms/op
Client.getUser:getUser·p1.00          sample         38.273           ms/op
Client.listUser                       sample   3616   8.892 ± 0.119   ms/op
Client.listUser:listUser·p0.00        sample          2.318           ms/op
Client.listUser:listUser·p0.50        sample          8.684           ms/op
Client.listUser:listUser·p0.90        sample         11.375           ms/op
Client.listUser:listUser·p0.95        sample         12.501           ms/op
Client.listUser:listUser·p0.99        sample         15.679           ms/op
Client.listUser:listUser·p0.999       sample         20.493           ms/op
Client.listUser:listUser·p0.9999      sample         20.873           ms/op
Client.listUser:listUser·p1.00        sample         20.873           ms/op
