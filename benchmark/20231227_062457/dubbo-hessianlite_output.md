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
# Warmup Iteration   1: 2.126 ops/ms
Iteration   1: 5.695 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.695 ops/ms


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
# Warmup Iteration   1: 5.735 ops/ms
Iteration   1: 12.899 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.899 ops/ms


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
# Warmup Iteration   1: 4.117 ops/ms
Iteration   1: 8.438 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.438 ops/ms


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
# Warmup Iteration   1: 1.972 ops/ms
Iteration   1: 3.658 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.658 ops/ms


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
# Warmup Iteration   1: 5.724 ±(99.9%) 0.082 ms/op
Iteration   1: 3.065 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.065 ms/op


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
# Warmup Iteration   1: 3.320 ±(99.9%) 0.057 ms/op
Iteration   1: 2.149 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.149 ms/op


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
# Warmup Iteration   1: 4.994 ±(99.9%) 0.067 ms/op
Iteration   1: 2.993 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.993 ms/op


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
# Warmup Iteration   1: 12.525 ±(99.9%) 0.206 ms/op
Iteration   1: 8.642 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.642 ms/op


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
# Warmup Iteration   1: 5.341 ±(99.9%) 0.145 ms/op
Iteration   1: 3.152 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   6.668 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 12.714 ms/op
                 createUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10141
  mean =      3.152 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 24 
    [ 1.250,  2.500) = 589 
    [ 2.500,  3.750) = 8224 
    [ 3.750,  5.000) = 1098 
    [ 5.000,  6.250) = 92 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     12.714 ms/op
     p(99.9990) =     12.714 ms/op
     p(99.9999) =     12.714 ms/op
    p(100.0000) =     12.714 ms/op


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
# Warmup Iteration   1: 3.156 ±(99.9%) 0.080 ms/op
Iteration   1: 1.825 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.297 ms/op
                 existUser·p0.50:   1.679 ms/op
                 existUser·p0.90:   2.565 ms/op
                 existUser·p0.95:   2.818 ms/op
                 existUser·p0.99:   3.396 ms/op
                 existUser·p0.999:  5.550 ms/op
                 existUser·p0.9999: 6.859 ms/op
                 existUser·p1.00:   6.865 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17516
  mean =      1.825 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 4 
    [0.500, 1.000) = 102 
    [1.000, 1.500) = 5225 
    [1.500, 2.000) = 7157 
    [2.000, 2.500) = 2971 
    [2.500, 3.000) = 1637 
    [3.000, 3.500) = 287 
    [3.500, 4.000) = 58 
    [4.000, 4.500) = 39 
    [4.500, 5.000) = 4 
    [5.000, 5.500) = 14 
    [5.500, 6.000) = 13 
    [6.000, 6.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      1.679 ms/op
     p(90.0000) =      2.565 ms/op
     p(95.0000) =      2.818 ms/op
     p(99.0000) =      3.396 ms/op
     p(99.9000) =      5.550 ms/op
     p(99.9900) =      6.859 ms/op
     p(99.9990) =      6.865 ms/op
     p(99.9999) =      6.865 ms/op
    p(100.0000) =      6.865 ms/op


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.124 ms/op
Iteration   1: 3.353 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.680 ms/op
                 getUser·p0.999:  7.060 ms/op
                 getUser·p0.9999: 9.257 ms/op
                 getUser·p1.00:   9.257 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9528
  mean =      3.353 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 10 
    [ 1.500,  2.000) = 96 
    [ 2.000,  2.500) = 1176 
    [ 2.500,  3.000) = 2012 
    [ 3.000,  3.500) = 2399 
    [ 3.500,  4.000) = 2224 
    [ 4.000,  4.500) = 1021 
    [ 4.500,  5.000) = 347 
    [ 5.000,  5.500) = 139 
    [ 5.500,  6.000) = 20 
    [ 6.000,  6.500) = 15 
    [ 6.500,  7.000) = 54 
    [ 7.000,  7.500) = 13 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.680 ms/op
     p(99.9000) =      7.060 ms/op
     p(99.9900) =      9.257 ms/op
     p(99.9990) =      9.257 ms/op
     p(99.9999) =      9.257 ms/op
    p(100.0000) =      9.257 ms/op


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
# Warmup Iteration   1: 12.206 ±(99.9%) 0.405 ms/op
Iteration   1: 9.904 ±(99.9%) 0.153 ms/op
                 listUser·p0.00:   4.067 ms/op
                 listUser·p0.50:   9.339 ms/op
                 listUser·p0.90:   13.369 ms/op
                 listUser·p0.95:   14.909 ms/op
                 listUser·p0.99:   18.775 ms/op
                 listUser·p0.999:  23.130 ms/op
                 listUser·p0.9999: 25.199 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3225
  mean =      9.904 ±(99.9%) 0.153 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 4 
    [ 5.000,  7.500) = 418 
    [ 7.500, 10.000) = 1585 
    [10.000, 12.500) = 795 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      4.067 ms/op
     p(50.0000) =      9.339 ms/op
     p(90.0000) =     13.369 ms/op
     p(95.0000) =     14.909 ms/op
     p(99.0000) =     18.775 ms/op
     p(99.9000) =     23.130 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.695          ops/ms
Client.existUser                       thrpt         12.899          ops/ms
Client.getUser                         thrpt          8.438          ops/ms
Client.listUser                        thrpt          3.658          ops/ms
Client.createUser                       avgt          3.065           ms/op
Client.existUser                        avgt          2.149           ms/op
Client.getUser                          avgt          2.993           ms/op
Client.listUser                         avgt          8.642           ms/op
Client.createUser                     sample  10141   3.152 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          0.527           ms/op
Client.createUser:createUser·p0.50    sample          2.974           ms/op
Client.createUser:createUser·p0.90    sample          3.871           ms/op
Client.createUser:createUser·p0.95    sample          4.227           ms/op
Client.createUser:createUser·p0.99    sample          6.668           ms/op
Client.createUser:createUser·p0.999   sample         11.878           ms/op
Client.createUser:createUser·p0.9999  sample         12.714           ms/op
Client.createUser:createUser·p1.00    sample         12.714           ms/op
Client.existUser                      sample  17516   1.825 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.297           ms/op
Client.existUser:existUser·p0.50      sample          1.679           ms/op
Client.existUser:existUser·p0.90      sample          2.565           ms/op
Client.existUser:existUser·p0.95      sample          2.818           ms/op
Client.existUser:existUser·p0.99      sample          3.396           ms/op
Client.existUser:existUser·p0.999     sample          5.550           ms/op
Client.existUser:existUser·p0.9999    sample          6.859           ms/op
Client.existUser:existUser·p1.00      sample          6.865           ms/op
Client.getUser                        sample   9528   3.353 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          1.124           ms/op
Client.getUser:getUser·p0.50          sample          3.338           ms/op
Client.getUser:getUser·p0.90          sample          4.268           ms/op
Client.getUser:getUser·p0.95          sample          4.620           ms/op
Client.getUser:getUser·p0.99          sample          5.680           ms/op
Client.getUser:getUser·p0.999         sample          7.060           ms/op
Client.getUser:getUser·p0.9999        sample          9.257           ms/op
Client.getUser:getUser·p1.00          sample          9.257           ms/op
Client.listUser                       sample   3225   9.904 ± 0.153   ms/op
Client.listUser:listUser·p0.00        sample          4.067           ms/op
Client.listUser:listUser·p0.50        sample          9.339           ms/op
Client.listUser:listUser·p0.90        sample         13.369           ms/op
Client.listUser:listUser·p0.95        sample         14.909           ms/op
Client.listUser:listUser·p0.99        sample         18.775           ms/op
Client.listUser:listUser·p0.999       sample         23.130           ms/op
Client.listUser:listUser·p0.9999      sample         25.199           ms/op
Client.listUser:listUser·p1.00        sample         25.199           ms/op
