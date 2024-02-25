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
# Warmup Iteration   1: 2.363 ops/ms
Iteration   1: 6.433 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.433 ops/ms


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
# Warmup Iteration   1: 6.231 ops/ms
Iteration   1: 12.004 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.004 ops/ms


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
# Warmup Iteration   1: 3.336 ops/ms
Iteration   1: 7.973 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.973 ops/ms


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
# Warmup Iteration   1: 2.227 ops/ms
Iteration   1: 3.739 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.739 ops/ms


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
# Warmup Iteration   1: 4.920 ±(99.9%) 0.057 ms/op
Iteration   1: 2.861 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.861 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.029 ms/op
Iteration   1: 2.068 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.068 ms/op


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
# Warmup Iteration   1: 5.061 ±(99.9%) 0.061 ms/op
Iteration   1: 3.235 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.235 ms/op


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
# Warmup Iteration   1: 11.513 ±(99.9%) 0.193 ms/op
Iteration   1: 8.746 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.746 ms/op


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
# Warmup Iteration   1: 5.074 ±(99.9%) 0.109 ms/op
Iteration   1: 2.975 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   2.785 ms/op
                 createUser·p0.90:   3.887 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.893 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 10.759 ms/op
                 createUser·p1.00:   10.764 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10750
  mean =      2.975 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 434 
    [ 2.000,  3.000) = 5873 
    [ 3.000,  4.000) = 3500 
    [ 4.000,  5.000) = 683 
    [ 5.000,  6.000) = 104 
    [ 6.000,  7.000) = 53 
    [ 7.000,  8.000) = 39 
    [ 8.000,  9.000) = 32 
    [ 9.000, 10.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      2.785 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.893 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     10.759 ms/op
     p(99.9990) =     10.764 ms/op
     p(99.9999) =     10.764 ms/op
    p(100.0000) =     10.764 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.063 ms/op
Iteration   1: 1.737 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.518 ms/op
                 existUser·p0.50:   1.667 ms/op
                 existUser·p0.90:   2.150 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   3.494 ms/op
                 existUser·p0.999:  15.499 ms/op
                 existUser·p0.9999: 16.312 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18402
  mean =      1.737 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2750 
    [ 1.250,  2.500) = 14958 
    [ 2.500,  3.750) = 529 
    [ 3.750,  5.000) = 38 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.518 ms/op
     p(50.0000) =      1.667 ms/op
     p(90.0000) =      2.150 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      3.494 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     16.312 ms/op
     p(99.9990) =     16.450 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.104 ms/op
Iteration   1: 3.165 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.447 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  10.550 ms/op
                 getUser·p0.9999: 11.396 ms/op
                 getUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10103
  mean =      3.165 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 17 
    [ 1.250,  2.500) = 1879 
    [ 2.500,  3.750) = 6899 
    [ 3.750,  5.000) = 1103 
    [ 5.000,  6.250) = 124 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     10.550 ms/op
     p(99.9900) =     11.396 ms/op
     p(99.9990) =     11.403 ms/op
     p(99.9999) =     11.403 ms/op
    p(100.0000) =     11.403 ms/op


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
# Warmup Iteration   1: 12.242 ±(99.9%) 0.389 ms/op
Iteration   1: 8.020 ±(99.9%) 0.116 ms/op
                 listUser·p0.00:   2.961 ms/op
                 listUser·p0.50:   7.684 ms/op
                 listUser·p0.90:   10.541 ms/op
                 listUser·p0.95:   11.895 ms/op
                 listUser·p0.99:   14.977 ms/op
                 listUser·p0.999:  22.348 ms/op
                 listUser·p0.9999: 22.938 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3985
  mean =      8.020 ±(99.9%) 0.116 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 128 
    [ 5.000,  7.500) = 1657 
    [ 7.500, 10.000) = 1666 
    [10.000, 12.500) = 401 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.961 ms/op
     p(50.0000) =      7.684 ms/op
     p(90.0000) =     10.541 ms/op
     p(95.0000) =     11.895 ms/op
     p(99.0000) =     14.977 ms/op
     p(99.9000) =     22.348 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.433          ops/ms
Client.existUser                       thrpt         12.004          ops/ms
Client.getUser                         thrpt          7.973          ops/ms
Client.listUser                        thrpt          3.739          ops/ms
Client.createUser                       avgt          2.861           ms/op
Client.existUser                        avgt          2.068           ms/op
Client.getUser                          avgt          3.235           ms/op
Client.listUser                         avgt          8.746           ms/op
Client.createUser                     sample  10750   2.975 ± 0.030   ms/op
Client.createUser:createUser·p0.00    sample          1.094           ms/op
Client.createUser:createUser·p0.50    sample          2.785           ms/op
Client.createUser:createUser·p0.90    sample          3.887           ms/op
Client.createUser:createUser·p0.95    sample          4.399           ms/op
Client.createUser:createUser·p0.99    sample          6.893           ms/op
Client.createUser:createUser·p0.999   sample         10.469           ms/op
Client.createUser:createUser·p0.9999  sample         10.759           ms/op
Client.createUser:createUser·p1.00    sample         10.764           ms/op
Client.existUser                      sample  18402   1.737 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.518           ms/op
Client.existUser:existUser·p0.50      sample          1.667           ms/op
Client.existUser:existUser·p0.90      sample          2.150           ms/op
Client.existUser:existUser·p0.95      sample          2.388           ms/op
Client.existUser:existUser·p0.99      sample          3.494           ms/op
Client.existUser:existUser·p0.999     sample         15.499           ms/op
Client.existUser:existUser·p0.9999    sample         16.312           ms/op
Client.existUser:existUser·p1.00      sample         16.450           ms/op
Client.getUser                        sample  10103   3.165 ± 0.028   ms/op
Client.getUser:getUser·p0.00          sample          0.447           ms/op
Client.getUser:getUser·p0.50          sample          3.138           ms/op
Client.getUser:getUser·p0.90          sample          3.850           ms/op
Client.getUser:getUser·p0.95          sample          4.350           ms/op
Client.getUser:getUser·p0.99          sample          5.652           ms/op
Client.getUser:getUser·p0.999         sample         10.550           ms/op
Client.getUser:getUser·p0.9999        sample         11.396           ms/op
Client.getUser:getUser·p1.00          sample         11.403           ms/op
Client.listUser                       sample   3985   8.020 ± 0.116   ms/op
Client.listUser:listUser·p0.00        sample          2.961           ms/op
Client.listUser:listUser·p0.50        sample          7.684           ms/op
Client.listUser:listUser·p0.90        sample         10.541           ms/op
Client.listUser:listUser·p0.95        sample         11.895           ms/op
Client.listUser:listUser·p0.99        sample         14.977           ms/op
Client.listUser:listUser·p0.999       sample         22.348           ms/op
Client.listUser:listUser·p0.9999      sample         22.938           ms/op
Client.listUser:listUser·p1.00        sample         22.938           ms/op
