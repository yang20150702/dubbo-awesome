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
# Warmup Iteration   1: 2.168 ops/ms
Iteration   1: 6.598 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.598 ops/ms


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
# Warmup Iteration   1: 6.462 ops/ms
Iteration   1: 11.574 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.574 ops/ms


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
# Warmup Iteration   1: 3.670 ops/ms
Iteration   1: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.522 ops/ms


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
# Warmup Iteration   1: 2.300 ops/ms
Iteration   1: 3.555 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.555 ops/ms


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
# Warmup Iteration   1: 5.810 ±(99.9%) 0.075 ms/op
Iteration   1: 3.129 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.129 ms/op


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
# Warmup Iteration   1: 3.582 ±(99.9%) 0.035 ms/op
Iteration   1: 2.129 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.129 ms/op


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
# Warmup Iteration   1: 4.673 ±(99.9%) 0.077 ms/op
Iteration   1: 3.141 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.141 ms/op


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
# Warmup Iteration   1: 10.952 ±(99.9%) 0.216 ms/op
Iteration   1: 8.099 ±(99.9%) 0.090 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.099 ms/op


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
# Warmup Iteration   1: 5.068 ±(99.9%) 0.152 ms/op
Iteration   1: 3.201 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   4.262 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   7.133 ms/op
                 createUser·p0.999:  16.761 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10236
  mean =      3.201 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2153 
    [ 2.500,  3.750) = 6284 
    [ 3.750,  5.000) = 1407 
    [ 5.000,  6.250) = 278 
    [ 6.250,  7.500) = 41 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.262 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.133 ms/op
     p(99.9000) =     16.761 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 3.204 ±(99.9%) 0.073 ms/op
Iteration   1: 1.866 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   1.796 ms/op
                 existUser·p0.90:   2.413 ms/op
                 existUser·p0.95:   2.613 ms/op
                 existUser·p0.99:   3.191 ms/op
                 existUser·p0.999:  11.549 ms/op
                 existUser·p0.9999: 11.998 ms/op
                 existUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17091
  mean =      1.866 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 931 
    [ 1.250,  2.500) = 14974 
    [ 2.500,  3.750) = 1123 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.413 ms/op
     p(95.0000) =      2.613 ms/op
     p(99.0000) =      3.191 ms/op
     p(99.9000) =     11.549 ms/op
     p(99.9900) =     11.998 ms/op
     p(99.9990) =     12.009 ms/op
     p(99.9999) =     12.009 ms/op
    p(100.0000) =     12.009 ms/op


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
# Warmup Iteration   1: 4.996 ±(99.9%) 0.125 ms/op
Iteration   1: 2.900 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   2.839 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.140 ms/op
                 getUser·p0.99:   5.470 ms/op
                 getUser·p0.999:  6.685 ms/op
                 getUser·p0.9999: 11.193 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11126
  mean =      2.900 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3357 
    [ 2.500,  3.750) = 6748 
    [ 3.750,  5.000) = 845 
    [ 5.000,  6.250) = 148 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.140 ms/op
     p(99.0000) =      5.470 ms/op
     p(99.9000) =      6.685 ms/op
     p(99.9900) =     11.193 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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
# Warmup Iteration   1: 11.625 ±(99.9%) 0.411 ms/op
Iteration   1: 7.923 ±(99.9%) 0.158 ms/op
                 listUser·p0.00:   1.853 ms/op
                 listUser·p0.50:   7.561 ms/op
                 listUser·p0.90:   10.170 ms/op
                 listUser·p0.95:   11.434 ms/op
                 listUser·p0.99:   22.207 ms/op
                 listUser·p0.999:  37.066 ms/op
                 listUser·p0.9999: 39.191 ms/op
                 listUser·p1.00:   39.191 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4082
  mean =      7.923 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 215 
    [ 5.000,  7.500) = 1760 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 333 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.853 ms/op
     p(50.0000) =      7.561 ms/op
     p(90.0000) =     10.170 ms/op
     p(95.0000) =     11.434 ms/op
     p(99.0000) =     22.207 ms/op
     p(99.9000) =     37.066 ms/op
     p(99.9900) =     39.191 ms/op
     p(99.9990) =     39.191 ms/op
     p(99.9999) =     39.191 ms/op
    p(100.0000) =     39.191 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.598          ops/ms
Client.existUser                       thrpt         11.574          ops/ms
Client.getUser                         thrpt          7.522          ops/ms
Client.listUser                        thrpt          3.555          ops/ms
Client.createUser                       avgt          3.129           ms/op
Client.existUser                        avgt          2.129           ms/op
Client.getUser                          avgt          3.141           ms/op
Client.listUser                         avgt          8.099           ms/op
Client.createUser                     sample  10236   3.201 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.419           ms/op
Client.createUser:createUser·p0.50    sample          3.015           ms/op
Client.createUser:createUser·p0.90    sample          4.262           ms/op
Client.createUser:createUser·p0.95    sample          4.817           ms/op
Client.createUser:createUser·p0.99    sample          7.133           ms/op
Client.createUser:createUser·p0.999   sample         16.761           ms/op
Client.createUser:createUser·p0.9999  sample         16.843           ms/op
Client.createUser:createUser·p1.00    sample         16.843           ms/op
Client.existUser                      sample  17091   1.866 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.538           ms/op
Client.existUser:existUser·p0.50      sample          1.796           ms/op
Client.existUser:existUser·p0.90      sample          2.413           ms/op
Client.existUser:existUser·p0.95      sample          2.613           ms/op
Client.existUser:existUser·p0.99      sample          3.191           ms/op
Client.existUser:existUser·p0.999     sample         11.549           ms/op
Client.existUser:existUser·p0.9999    sample         11.998           ms/op
Client.existUser:existUser·p1.00      sample         12.009           ms/op
Client.getUser                        sample  11126   2.900 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.286           ms/op
Client.getUser:getUser·p0.50          sample          2.839           ms/op
Client.getUser:getUser·p0.90          sample          3.682           ms/op
Client.getUser:getUser·p0.95          sample          4.140           ms/op
Client.getUser:getUser·p0.99          sample          5.470           ms/op
Client.getUser:getUser·p0.999         sample          6.685           ms/op
Client.getUser:getUser·p0.9999        sample         11.193           ms/op
Client.getUser:getUser·p1.00          sample         11.518           ms/op
Client.listUser                       sample   4082   7.923 ± 0.158   ms/op
Client.listUser:listUser·p0.00        sample          1.853           ms/op
Client.listUser:listUser·p0.50        sample          7.561           ms/op
Client.listUser:listUser·p0.90        sample         10.170           ms/op
Client.listUser:listUser·p0.95        sample         11.434           ms/op
Client.listUser:listUser·p0.99        sample         22.207           ms/op
Client.listUser:listUser·p0.999       sample         37.066           ms/op
Client.listUser:listUser·p0.9999      sample         39.191           ms/op
Client.listUser:listUser·p1.00        sample         39.191           ms/op
