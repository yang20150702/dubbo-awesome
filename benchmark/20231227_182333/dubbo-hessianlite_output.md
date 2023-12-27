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
# Warmup Iteration   1: 2.503 ops/ms
Iteration   1: 6.364 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.364 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.156 ops/ms
Iteration   1: 11.494 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.494 ops/ms


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
# Warmup Iteration   1: 4.043 ops/ms
Iteration   1: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.549 ops/ms


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
# Warmup Iteration   1: 1.877 ops/ms
Iteration   1: 3.384 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.384 ops/ms


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
# Warmup Iteration   1: 5.649 ±(99.9%) 0.101 ms/op
Iteration   1: 2.992 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.992 ms/op


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
# Warmup Iteration   1: 3.041 ±(99.9%) 0.030 ms/op
Iteration   1: 1.804 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.804 ms/op


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
# Warmup Iteration   1: 5.044 ±(99.9%) 0.058 ms/op
Iteration   1: 3.146 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.146 ms/op


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
# Warmup Iteration   1: 12.608 ±(99.9%) 0.168 ms/op
Iteration   1: 10.644 ±(99.9%) 0.175 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  10.644 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.099 ms/op
Iteration   1: 3.134 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   1.276 ms/op
                 createUser·p0.50:   2.806 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   9.191 ms/op
                 createUser·p0.999:  23.479 ms/op
                 createUser·p0.9999: 24.472 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10242
  mean =      3.134 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3025 
    [ 2.500,  5.000) = 6822 
    [ 5.000,  7.500) = 228 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      2.806 ms/op
     p(90.0000) =      3.858 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      9.191 ms/op
     p(99.9000) =     23.479 ms/op
     p(99.9900) =     24.472 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 2.924 ±(99.9%) 0.059 ms/op
Iteration   1: 1.772 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   1.636 ms/op
                 existUser·p0.90:   2.236 ms/op
                 existUser·p0.95:   2.429 ms/op
                 existUser·p0.99:   3.330 ms/op
                 existUser·p0.999:  13.550 ms/op
                 existUser·p0.9999: 13.582 ms/op
                 existUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18042
  mean =      1.772 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 16780 
    [ 2.500,  3.750) = 531 
    [ 3.750,  5.000) = 50 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      1.636 ms/op
     p(90.0000) =      2.236 ms/op
     p(95.0000) =      2.429 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     13.582 ms/op
     p(99.9999) =     13.582 ms/op
    p(100.0000) =     13.582 ms/op


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
# Warmup Iteration   1: 4.705 ±(99.9%) 0.137 ms/op
Iteration   1: 2.655 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.380 ms/op
                 getUser·p0.9999: 8.247 ms/op
                 getUser·p1.00:   8.421 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 12042
  mean =      2.655 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 43 
    [1.500, 2.000) = 532 
    [2.000, 2.500) = 5177 
    [2.500, 3.000) = 4015 
    [3.000, 3.500) = 1259 
    [3.500, 4.000) = 634 
    [4.000, 4.500) = 274 
    [4.500, 5.000) = 32 
    [5.000, 5.500) = 34 
    [5.500, 6.000) = 18 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 9 
    [7.000, 7.500) = 10 
    [7.500, 8.000) = 2 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.380 ms/op
     p(99.9900) =      8.247 ms/op
     p(99.9990) =      8.421 ms/op
     p(99.9999) =      8.421 ms/op
    p(100.0000) =      8.421 ms/op


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
# Warmup Iteration   1: 11.346 ±(99.9%) 0.346 ms/op
Iteration   1: 7.820 ±(99.9%) 0.095 ms/op
                 listUser·p0.00:   2.327 ms/op
                 listUser·p0.50:   7.627 ms/op
                 listUser·p0.90:   9.650 ms/op
                 listUser·p0.95:   10.387 ms/op
                 listUser·p0.99:   14.261 ms/op
                 listUser·p0.999:  21.296 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4072
  mean =      7.820 ±(99.9%) 0.095 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 111 
    [ 5.000,  7.500) = 1802 
    [ 7.500, 10.000) = 1882 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.327 ms/op
     p(50.0000) =      7.627 ms/op
     p(90.0000) =      9.650 ms/op
     p(95.0000) =     10.387 ms/op
     p(99.0000) =     14.261 ms/op
     p(99.9000) =     21.296 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     22.282 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.364          ops/ms
Client.existUser                       thrpt         11.494          ops/ms
Client.getUser                         thrpt          8.549          ops/ms
Client.listUser                        thrpt          3.384          ops/ms
Client.createUser                       avgt          2.992           ms/op
Client.existUser                        avgt          1.804           ms/op
Client.getUser                          avgt          3.146           ms/op
Client.listUser                         avgt         10.644           ms/op
Client.createUser                     sample  10242   3.134 ± 0.060   ms/op
Client.createUser:createUser·p0.00    sample          1.276           ms/op
Client.createUser:createUser·p0.50    sample          2.806           ms/op
Client.createUser:createUser·p0.90    sample          3.858           ms/op
Client.createUser:createUser·p0.95    sample          4.563           ms/op
Client.createUser:createUser·p0.99    sample          9.191           ms/op
Client.createUser:createUser·p0.999   sample         23.479           ms/op
Client.createUser:createUser·p0.9999  sample         24.472           ms/op
Client.createUser:createUser·p1.00    sample         24.478           ms/op
Client.existUser                      sample  18042   1.772 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.440           ms/op
Client.existUser:existUser·p0.50      sample          1.636           ms/op
Client.existUser:existUser·p0.90      sample          2.236           ms/op
Client.existUser:existUser·p0.95      sample          2.429           ms/op
Client.existUser:existUser·p0.99      sample          3.330           ms/op
Client.existUser:existUser·p0.999     sample         13.550           ms/op
Client.existUser:existUser·p0.9999    sample         13.582           ms/op
Client.existUser:existUser·p1.00      sample         13.582           ms/op
Client.getUser                        sample  12042   2.655 ± 0.017   ms/op
Client.getUser:getUser·p0.00          sample          0.902           ms/op
Client.getUser:getUser·p0.50          sample          2.523           ms/op
Client.getUser:getUser·p0.90          sample          3.391           ms/op
Client.getUser:getUser·p0.95          sample          3.768           ms/op
Client.getUser:getUser·p0.99          sample          4.440           ms/op
Client.getUser:getUser·p0.999         sample          7.380           ms/op
Client.getUser:getUser·p0.9999        sample          8.247           ms/op
Client.getUser:getUser·p1.00          sample          8.421           ms/op
Client.listUser                       sample   4072   7.820 ± 0.095   ms/op
Client.listUser:listUser·p0.00        sample          2.327           ms/op
Client.listUser:listUser·p0.50        sample          7.627           ms/op
Client.listUser:listUser·p0.90        sample          9.650           ms/op
Client.listUser:listUser·p0.95        sample         10.387           ms/op
Client.listUser:listUser·p0.99        sample         14.261           ms/op
Client.listUser:listUser·p0.999       sample         21.296           ms/op
Client.listUser:listUser·p0.9999      sample         22.282           ms/op
Client.listUser:listUser·p1.00        sample         22.282           ms/op
