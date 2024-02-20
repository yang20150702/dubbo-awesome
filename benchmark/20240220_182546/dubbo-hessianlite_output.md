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
# Warmup Iteration   1: 2.532 ops/ms
Iteration   1: 6.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.911 ops/ms


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
# Warmup Iteration   1: 6.047 ops/ms
Iteration   1: 13.015 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.015 ops/ms


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
# Warmup Iteration   1: 4.090 ops/ms
Iteration   1: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.298 ops/ms


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
# Warmup Iteration   1: 2.277 ops/ms
Iteration   1: 3.543 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.543 ops/ms


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
# Warmup Iteration   1: 5.284 ±(99.9%) 0.061 ms/op
Iteration   1: 2.831 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.831 ms/op


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
# Warmup Iteration   1: 2.921 ±(99.9%) 0.031 ms/op
Iteration   1: 1.824 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 4.551 ±(99.9%) 0.064 ms/op
Iteration   1: 3.043 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.043 ms/op


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
# Warmup Iteration   1: 12.230 ±(99.9%) 0.217 ms/op
Iteration   1: 7.746 ±(99.9%) 0.100 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.746 ms/op


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
# Warmup Iteration   1: 4.701 ±(99.9%) 0.105 ms/op
Iteration   1: 3.209 ±(99.9%) 0.072 ms/op
                 createUser·p0.00:   0.597 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.212 ms/op
                 createUser·p0.99:   6.344 ms/op
                 createUser·p0.999:  38.404 ms/op
                 createUser·p0.9999: 38.601 ms/op
                 createUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9975
  mean =      3.209 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1799 
    [ 2.500,  5.000) = 7975 
    [ 5.000,  7.500) = 123 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.597 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.212 ms/op
     p(99.0000) =      6.344 ms/op
     p(99.9000) =     38.404 ms/op
     p(99.9900) =     38.601 ms/op
     p(99.9990) =     38.601 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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
# Warmup Iteration   1: 3.159 ±(99.9%) 0.063 ms/op
Iteration   1: 1.873 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.547 ms/op
                 existUser·p0.50:   1.681 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  7.517 ms/op
                 existUser·p0.9999: 12.085 ms/op
                 existUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17122
  mean =      1.873 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 315 
    [ 1.250,  2.500) = 15121 
    [ 2.500,  3.750) = 1428 
    [ 3.750,  5.000) = 189 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      1.681 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.517 ms/op
     p(99.9900) =     12.085 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.113 ms/op
Iteration   1: 3.077 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  7.053 ms/op
                 getUser·p0.9999: 7.689 ms/op
                 getUser·p1.00:   7.700 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10395
  mean =      3.077 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 305 
    [2.000, 2.500) = 1859 
    [2.500, 3.000) = 2928 
    [3.000, 3.500) = 2822 
    [3.500, 4.000) = 1665 
    [4.000, 4.500) = 546 
    [4.500, 5.000) = 125 
    [5.000, 5.500) = 45 
    [5.500, 6.000) = 3 
    [6.000, 6.500) = 26 
    [6.500, 7.000) = 41 
    [7.000, 7.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.251 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =      7.689 ms/op
     p(99.9990) =      7.700 ms/op
     p(99.9999) =      7.700 ms/op
    p(100.0000) =      7.700 ms/op


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
# Warmup Iteration   1: 12.420 ±(99.9%) 0.458 ms/op
Iteration   1: 8.509 ±(99.9%) 0.127 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   8.290 ms/op
                 listUser·p0.90:   11.387 ms/op
                 listUser·p0.95:   12.417 ms/op
                 listUser·p0.99:   15.174 ms/op
                 listUser·p0.999:  25.968 ms/op
                 listUser·p0.9999: 30.638 ms/op
                 listUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3742
  mean =      8.509 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 129 
    [ 5.000,  7.500) = 1161 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 698 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      8.290 ms/op
     p(90.0000) =     11.387 ms/op
     p(95.0000) =     12.417 ms/op
     p(99.0000) =     15.174 ms/op
     p(99.9000) =     25.968 ms/op
     p(99.9900) =     30.638 ms/op
     p(99.9990) =     30.638 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.911          ops/ms
Client.existUser                       thrpt         13.015          ops/ms
Client.getUser                         thrpt          8.298          ops/ms
Client.listUser                        thrpt          3.543          ops/ms
Client.createUser                       avgt          2.831           ms/op
Client.existUser                        avgt          1.824           ms/op
Client.getUser                          avgt          3.043           ms/op
Client.listUser                         avgt          7.746           ms/op
Client.createUser                     sample   9975   3.209 ± 0.072   ms/op
Client.createUser:createUser·p0.00    sample          0.597           ms/op
Client.createUser:createUser·p0.50    sample          2.978           ms/op
Client.createUser:createUser·p0.90    sample          3.895           ms/op
Client.createUser:createUser·p0.95    sample          4.212           ms/op
Client.createUser:createUser·p0.99    sample          6.344           ms/op
Client.createUser:createUser·p0.999   sample         38.404           ms/op
Client.createUser:createUser·p0.9999  sample         38.601           ms/op
Client.createUser:createUser·p1.00    sample         38.601           ms/op
Client.existUser                      sample  17122   1.873 ± 0.015   ms/op
Client.existUser:existUser·p0.00      sample          0.547           ms/op
Client.existUser:existUser·p0.50      sample          1.681           ms/op
Client.existUser:existUser·p0.90      sample          2.499           ms/op
Client.existUser:existUser·p0.95      sample          2.724           ms/op
Client.existUser:existUser·p0.99      sample          4.358           ms/op
Client.existUser:existUser·p0.999     sample          7.517           ms/op
Client.existUser:existUser·p0.9999    sample         12.085           ms/op
Client.existUser:existUser·p1.00      sample         12.190           ms/op
Client.getUser                        sample  10395   3.077 ± 0.023   ms/op
Client.getUser:getUser·p0.00          sample          1.186           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          3.883           ms/op
Client.getUser:getUser·p0.95          sample          4.178           ms/op
Client.getUser:getUser·p0.99          sample          5.251           ms/op
Client.getUser:getUser·p0.999         sample          7.053           ms/op
Client.getUser:getUser·p0.9999        sample          7.689           ms/op
Client.getUser:getUser·p1.00          sample          7.700           ms/op
Client.listUser                       sample   3742   8.509 ± 0.127   ms/op
Client.listUser:listUser·p0.00        sample          1.794           ms/op
Client.listUser:listUser·p0.50        sample          8.290           ms/op
Client.listUser:listUser·p0.90        sample         11.387           ms/op
Client.listUser:listUser·p0.95        sample         12.417           ms/op
Client.listUser:listUser·p0.99        sample         15.174           ms/op
Client.listUser:listUser·p0.999       sample         25.968           ms/op
Client.listUser:listUser·p0.9999      sample         30.638           ms/op
Client.listUser:listUser·p1.00        sample         30.638           ms/op
