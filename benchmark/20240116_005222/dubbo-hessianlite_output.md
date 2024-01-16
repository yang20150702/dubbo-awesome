# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.398 ops/ms
Iteration   1: 5.876 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.876 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.157 ops/ms
Iteration   1: 11.111 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.111 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ops/ms
Iteration   1: 7.944 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.944 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
Iteration   1: 3.850 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.850 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ±(99.9%) 0.065 ms/op
Iteration   1: 3.402 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.402 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ±(99.9%) 0.027 ms/op
Iteration   1: 1.978 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.816 ±(99.9%) 0.057 ms/op
Iteration   1: 3.466 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.466 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.012 ±(99.9%) 0.289 ms/op
Iteration   1: 9.834 ±(99.9%) 0.112 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.834 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.060 ±(99.9%) 0.112 ms/op
Iteration   1: 2.922 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   2.724 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   6.663 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 12.390 ms/op
                 createUser·p1.00:   12.419 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11259
  mean =      2.922 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 2759 
    [ 2.500,  3.750) = 7300 
    [ 3.750,  5.000) = 897 
    [ 5.000,  6.250) = 109 
    [ 6.250,  7.500) = 85 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      2.724 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      6.663 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     12.390 ms/op
     p(99.9990) =     12.419 ms/op
     p(99.9999) =     12.419 ms/op
    p(100.0000) =     12.419 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ±(99.9%) 0.060 ms/op
Iteration   1: 1.734 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.569 ms/op
                 existUser·p0.50:   1.628 ms/op
                 existUser·p0.90:   2.159 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.060 ms/op
                 existUser·p0.999:  22.123 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18436
  mean =      1.734 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17927 
    [ 2.500,  5.000) = 477 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.569 ms/op
     p(50.0000) =      1.628 ms/op
     p(90.0000) =      2.159 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.060 ms/op
     p(99.9000) =     22.123 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.606 ±(99.9%) 0.106 ms/op
Iteration   1: 3.267 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  6.780 ms/op
                 getUser·p0.9999: 8.684 ms/op
                 getUser·p1.00:   8.684 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9846
  mean =      3.267 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 32 
    [1.500, 2.000) = 277 
    [2.000, 2.500) = 803 
    [2.500, 3.000) = 2538 
    [3.000, 3.500) = 2969 
    [3.500, 4.000) = 2032 
    [4.000, 4.500) = 748 
    [4.500, 5.000) = 149 
    [5.000, 5.500) = 130 
    [5.500, 6.000) = 102 
    [6.000, 6.500) = 50 
    [6.500, 7.000) = 10 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      6.780 ms/op
     p(99.9900) =      8.684 ms/op
     p(99.9990) =      8.684 ms/op
     p(99.9999) =      8.684 ms/op
    p(100.0000) =      8.684 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.318 ±(99.9%) 0.486 ms/op
Iteration   1: 9.072 ±(99.9%) 0.160 ms/op
                 listUser·p0.00:   2.056 ms/op
                 listUser·p0.50:   8.421 ms/op
                 listUser·p0.90:   12.681 ms/op
                 listUser·p0.95:   14.320 ms/op
                 listUser·p0.99:   19.452 ms/op
                 listUser·p0.999:  25.045 ms/op
                 listUser·p0.9999: 26.345 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3517
  mean =      9.072 ±(99.9%) 0.160 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 925 
    [ 7.500, 10.000) = 1465 
    [10.000, 12.500) = 621 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.056 ms/op
     p(50.0000) =      8.421 ms/op
     p(90.0000) =     12.681 ms/op
     p(95.0000) =     14.320 ms/op
     p(99.0000) =     19.452 ms/op
     p(99.9000) =     25.045 ms/op
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

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.876          ops/ms
Client.existUser                       thrpt         11.111          ops/ms
Client.getUser                         thrpt          7.944          ops/ms
Client.listUser                        thrpt          3.850          ops/ms
Client.createUser                       avgt          3.402           ms/op
Client.existUser                        avgt          1.978           ms/op
Client.getUser                          avgt          3.466           ms/op
Client.listUser                         avgt          9.834           ms/op
Client.createUser                     sample  11259   2.922 ± 0.027   ms/op
Client.createUser:createUser·p0.00    sample          1.075           ms/op
Client.createUser:createUser·p0.50    sample          2.724           ms/op
Client.createUser:createUser·p0.90    sample          3.768           ms/op
Client.createUser:createUser·p0.95    sample          4.137           ms/op
Client.createUser:createUser·p0.99    sample          6.663           ms/op
Client.createUser:createUser·p0.999   sample          9.388           ms/op
Client.createUser:createUser·p0.9999  sample         12.390           ms/op
Client.createUser:createUser·p1.00    sample         12.419           ms/op
Client.existUser                      sample  18436   1.734 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.569           ms/op
Client.existUser:existUser·p0.50      sample          1.628           ms/op
Client.existUser:existUser·p0.90      sample          2.159           ms/op
Client.existUser:existUser·p0.95      sample          2.335           ms/op
Client.existUser:existUser·p0.99      sample          3.060           ms/op
Client.existUser:existUser·p0.999     sample         22.123           ms/op
Client.existUser:existUser·p0.9999    sample         23.003           ms/op
Client.existUser:existUser·p1.00      sample         23.003           ms/op
Client.getUser                        sample   9846   3.267 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.880           ms/op
Client.getUser:getUser·p0.50          sample          3.191           ms/op
Client.getUser:getUser·p0.90          sample          4.088           ms/op
Client.getUser:getUser·p0.95          sample          4.424           ms/op
Client.getUser:getUser·p0.99          sample          5.825           ms/op
Client.getUser:getUser·p0.999         sample          6.780           ms/op
Client.getUser:getUser·p0.9999        sample          8.684           ms/op
Client.getUser:getUser·p1.00          sample          8.684           ms/op
Client.listUser                       sample   3517   9.072 ± 0.160   ms/op
Client.listUser:listUser·p0.00        sample          2.056           ms/op
Client.listUser:listUser·p0.50        sample          8.421           ms/op
Client.listUser:listUser·p0.90        sample         12.681           ms/op
Client.listUser:listUser·p0.95        sample         14.320           ms/op
Client.listUser:listUser·p0.99        sample         19.452           ms/op
Client.listUser:listUser·p0.999       sample         25.045           ms/op
Client.listUser:listUser·p0.9999      sample         26.345           ms/op
Client.listUser:listUser·p1.00        sample         26.345           ms/op
