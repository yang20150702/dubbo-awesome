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
# Warmup Iteration   1: 2.515 ops/ms
Iteration   1: 6.275 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.275 ops/ms


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
# Warmup Iteration   1: 6.429 ops/ms
Iteration   1: 12.843 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.843 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.979 ops/ms
Iteration   1: 8.970 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.970 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.290 ops/ms
Iteration   1: 3.249 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.249 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.570 ±(99.9%) 0.092 ms/op
Iteration   1: 2.900 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.900 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.470 ±(99.9%) 0.041 ms/op
Iteration   1: 1.864 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.864 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.848 ±(99.9%) 0.067 ms/op
Iteration   1: 2.888 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.888 ms/op


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
# Warmup Iteration   1: 13.106 ±(99.9%) 0.237 ms/op
Iteration   1: 9.537 ±(99.9%) 0.117 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  9.537 ms/op


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
# Warmup Iteration   1: 5.009 ±(99.9%) 0.088 ms/op
Iteration   1: 3.372 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  14.196 ms/op
                 createUser·p0.9999: 14.467 ms/op
                 createUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9541
  mean =      3.372 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 725 
    [ 2.500,  3.750) = 6357 
    [ 3.750,  5.000) = 2224 
    [ 5.000,  6.250) = 113 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.196 ms/op
     p(99.9900) =     14.467 ms/op
     p(99.9990) =     14.467 ms/op
     p(99.9999) =     14.467 ms/op
    p(100.0000) =     14.467 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.881 ±(99.9%) 0.050 ms/op
Iteration   1: 1.876 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.687 ms/op
                 existUser·p0.50:   1.731 ms/op
                 existUser·p0.90:   2.200 ms/op
                 existUser·p0.95:   2.519 ms/op
                 existUser·p0.99:   5.370 ms/op
                 existUser·p0.999:  10.961 ms/op
                 existUser·p0.9999: 10.998 ms/op
                 existUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17151
  mean =      1.876 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 16108 
    [ 2.500,  3.750) = 596 
    [ 3.750,  5.000) = 118 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      1.731 ms/op
     p(90.0000) =      2.200 ms/op
     p(95.0000) =      2.519 ms/op
     p(99.0000) =      5.370 ms/op
     p(99.9000) =     10.961 ms/op
     p(99.9900) =     10.998 ms/op
     p(99.9990) =     11.010 ms/op
     p(99.9999) =     11.010 ms/op
    p(100.0000) =     11.010 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.369 ±(99.9%) 0.087 ms/op
Iteration   1: 2.948 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.549 ms/op
                 getUser·p0.50:   2.851 ms/op
                 getUser·p0.90:   3.721 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  15.647 ms/op
                 getUser·p0.9999: 15.940 ms/op
                 getUser·p1.00:   15.942 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10965
  mean =      2.948 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 3708 
    [ 2.500,  3.750) = 6159 
    [ 3.750,  5.000) = 855 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.721 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     15.647 ms/op
     p(99.9900) =     15.940 ms/op
     p(99.9990) =     15.942 ms/op
     p(99.9999) =     15.942 ms/op
    p(100.0000) =     15.942 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.068 ±(99.9%) 0.351 ms/op
Iteration   1: 8.664 ±(99.9%) 0.134 ms/op
                 listUser·p0.00:   2.888 ms/op
                 listUser·p0.50:   8.200 ms/op
                 listUser·p0.90:   11.616 ms/op
                 listUser·p0.95:   13.036 ms/op
                 listUser·p0.99:   16.515 ms/op
                 listUser·p0.999:  22.107 ms/op
                 listUser·p0.9999: 23.167 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3666
  mean =      8.664 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 91 
    [ 5.000,  7.500) = 1208 
    [ 7.500, 10.000) = 1418 
    [10.000, 12.500) = 719 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.888 ms/op
     p(50.0000) =      8.200 ms/op
     p(90.0000) =     11.616 ms/op
     p(95.0000) =     13.036 ms/op
     p(99.0000) =     16.515 ms/op
     p(99.9000) =     22.107 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     23.167 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.275          ops/ms
Client.existUser                       thrpt         12.843          ops/ms
Client.getUser                         thrpt          8.970          ops/ms
Client.listUser                        thrpt          3.249          ops/ms
Client.createUser                       avgt          2.900           ms/op
Client.existUser                        avgt          1.864           ms/op
Client.getUser                          avgt          2.888           ms/op
Client.listUser                         avgt          9.537           ms/op
Client.createUser                     sample   9541   3.372 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          1.137           ms/op
Client.createUser:createUser·p0.50    sample          3.211           ms/op
Client.createUser:createUser·p0.90    sample          4.194           ms/op
Client.createUser:createUser·p0.95    sample          4.456           ms/op
Client.createUser:createUser·p0.99    sample          6.496           ms/op
Client.createUser:createUser·p0.999   sample         14.196           ms/op
Client.createUser:createUser·p0.9999  sample         14.467           ms/op
Client.createUser:createUser·p1.00    sample         14.467           ms/op
Client.existUser                      sample  17151   1.876 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.687           ms/op
Client.existUser:existUser·p0.50      sample          1.731           ms/op
Client.existUser:existUser·p0.90      sample          2.200           ms/op
Client.existUser:existUser·p0.95      sample          2.519           ms/op
Client.existUser:existUser·p0.99      sample          5.370           ms/op
Client.existUser:existUser·p0.999     sample         10.961           ms/op
Client.existUser:existUser·p0.9999    sample         10.998           ms/op
Client.existUser:existUser·p1.00      sample         11.010           ms/op
Client.getUser                        sample  10965   2.948 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.549           ms/op
Client.getUser:getUser·p0.50          sample          2.851           ms/op
Client.getUser:getUser·p0.90          sample          3.721           ms/op
Client.getUser:getUser·p0.95          sample          4.141           ms/op
Client.getUser:getUser·p0.99          sample          6.373           ms/op
Client.getUser:getUser·p0.999         sample         15.647           ms/op
Client.getUser:getUser·p0.9999        sample         15.940           ms/op
Client.getUser:getUser·p1.00          sample         15.942           ms/op
Client.listUser                       sample   3666   8.664 ± 0.134   ms/op
Client.listUser:listUser·p0.00        sample          2.888           ms/op
Client.listUser:listUser·p0.50        sample          8.200           ms/op
Client.listUser:listUser·p0.90        sample         11.616           ms/op
Client.listUser:listUser·p0.95        sample         13.036           ms/op
Client.listUser:listUser·p0.99        sample         16.515           ms/op
Client.listUser:listUser·p0.999       sample         22.107           ms/op
Client.listUser:listUser·p0.9999      sample         23.167           ms/op
Client.listUser:listUser·p1.00        sample         23.167           ms/op
