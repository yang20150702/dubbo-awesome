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
# Warmup Iteration   1: 2.199 ops/ms
Iteration   1: 5.643 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.643 ops/ms


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
# Warmup Iteration   1: 5.828 ops/ms
Iteration   1: 12.216 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.216 ops/ms


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
# Warmup Iteration   1: 4.040 ops/ms
Iteration   1: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.141 ops/ms


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
# Warmup Iteration   1: 2.193 ops/ms
Iteration   1: 3.834 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.834 ops/ms


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
# Warmup Iteration   1: 5.340 ±(99.9%) 0.070 ms/op
Iteration   1: 3.004 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.004 ms/op


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
# Warmup Iteration   1: 3.305 ±(99.9%) 0.037 ms/op
Iteration   1: 1.864 ±(99.9%) 0.020 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.065 ±(99.9%) 0.050 ms/op
Iteration   1: 3.316 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.316 ms/op


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
# Warmup Iteration   1: 11.874 ±(99.9%) 0.282 ms/op
Iteration   1: 7.420 ±(99.9%) 0.063 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.420 ms/op


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.105 ms/op
Iteration   1: 3.158 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   1.434 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.993 ms/op
                 createUser·p0.99:   5.423 ms/op
                 createUser·p0.999:  8.927 ms/op
                 createUser·p0.9999: 10.393 ms/op
                 createUser·p1.00:   10.404 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10124
  mean =      3.158 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 71 
    [ 2.000,  3.000) = 3845 
    [ 3.000,  4.000) = 5710 
    [ 4.000,  5.000) = 364 
    [ 5.000,  6.000) = 69 
    [ 6.000,  7.000) = 45 
    [ 7.000,  8.000) = 5 
    [ 8.000,  9.000) = 8 
    [ 9.000, 10.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.434 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.993 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.927 ms/op
     p(99.9900) =     10.393 ms/op
     p(99.9990) =     10.404 ms/op
     p(99.9999) =     10.404 ms/op
    p(100.0000) =     10.404 ms/op


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
# Warmup Iteration   1: 2.987 ±(99.9%) 0.062 ms/op
Iteration   1: 1.783 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   1.595 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.630 ms/op
                 existUser·p0.99:   3.334 ms/op
                 existUser·p0.999:  19.169 ms/op
                 existUser·p0.9999: 19.438 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17927
  mean =      1.783 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 564 
    [ 1.250,  2.500) = 16123 
    [ 2.500,  3.750) = 1124 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.540 ms/op
     p(50.0000) =      1.595 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.630 ms/op
     p(99.0000) =      3.334 ms/op
     p(99.9000) =     19.169 ms/op
     p(99.9900) =     19.438 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.614 ±(99.9%) 0.103 ms/op
Iteration   1: 3.046 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.997 ms/op
                 getUser·p0.999:  5.726 ms/op
                 getUser·p0.9999: 7.777 ms/op
                 getUser·p1.00:   7.807 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10506
  mean =      3.046 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 4 
    [1.000, 1.500) = 26 
    [1.500, 2.000) = 308 
    [2.000, 2.500) = 1727 
    [2.500, 3.000) = 3076 
    [3.000, 3.500) = 2946 
    [3.500, 4.000) = 1785 
    [4.000, 4.500) = 425 
    [4.500, 5.000) = 105 
    [5.000, 5.500) = 76 
    [5.500, 6.000) = 23 
    [6.000, 6.500) = 2 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      5.726 ms/op
     p(99.9900) =      7.777 ms/op
     p(99.9990) =      7.807 ms/op
     p(99.9999) =      7.807 ms/op
    p(100.0000) =      7.807 ms/op


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
# Warmup Iteration   1: 12.525 ±(99.9%) 0.447 ms/op
Iteration   1: 7.441 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.466 ms/op
                 listUser·p0.50:   6.980 ms/op
                 listUser·p0.90:   10.174 ms/op
                 listUser·p0.95:   12.274 ms/op
                 listUser·p0.99:   15.713 ms/op
                 listUser·p0.999:  19.196 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4298
  mean =      7.441 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 297 
    [ 5.000,  7.500) = 2396 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 248 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.466 ms/op
     p(50.0000) =      6.980 ms/op
     p(90.0000) =     10.174 ms/op
     p(95.0000) =     12.274 ms/op
     p(99.0000) =     15.713 ms/op
     p(99.9000) =     19.196 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.643          ops/ms
Client.existUser                       thrpt         12.216          ops/ms
Client.getUser                         thrpt          8.141          ops/ms
Client.listUser                        thrpt          3.834          ops/ms
Client.createUser                       avgt          3.004           ms/op
Client.existUser                        avgt          1.864           ms/op
Client.getUser                          avgt          3.316           ms/op
Client.listUser                         avgt          7.420           ms/op
Client.createUser                     sample  10124   3.158 ± 0.019   ms/op
Client.createUser:createUser·p0.00    sample          1.434           ms/op
Client.createUser:createUser·p0.50    sample          3.092           ms/op
Client.createUser:createUser·p0.90    sample          3.678           ms/op
Client.createUser:createUser·p0.95    sample          3.993           ms/op
Client.createUser:createUser·p0.99    sample          5.423           ms/op
Client.createUser:createUser·p0.999   sample          8.927           ms/op
Client.createUser:createUser·p0.9999  sample         10.393           ms/op
Client.createUser:createUser·p1.00    sample         10.404           ms/op
Client.existUser                      sample  17927   1.783 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.540           ms/op
Client.existUser:existUser·p0.50      sample          1.595           ms/op
Client.existUser:existUser·p0.90      sample          2.359           ms/op
Client.existUser:existUser·p0.95      sample          2.630           ms/op
Client.existUser:existUser·p0.99      sample          3.334           ms/op
Client.existUser:existUser·p0.999     sample         19.169           ms/op
Client.existUser:existUser·p0.9999    sample         19.438           ms/op
Client.existUser:existUser·p1.00      sample         19.464           ms/op
Client.getUser                        sample  10506   3.046 ± 0.020   ms/op
Client.getUser:getUser·p0.00          sample          0.896           ms/op
Client.getUser:getUser·p0.50          sample          3.015           ms/op
Client.getUser:getUser·p0.90          sample          3.826           ms/op
Client.getUser:getUser·p0.95          sample          4.067           ms/op
Client.getUser:getUser·p0.99          sample          4.997           ms/op
Client.getUser:getUser·p0.999         sample          5.726           ms/op
Client.getUser:getUser·p0.9999        sample          7.777           ms/op
Client.getUser:getUser·p1.00          sample          7.807           ms/op
Client.listUser                       sample   4298   7.441 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.466           ms/op
Client.listUser:listUser·p0.50        sample          6.980           ms/op
Client.listUser:listUser·p0.90        sample         10.174           ms/op
Client.listUser:listUser·p0.95        sample         12.274           ms/op
Client.listUser:listUser·p0.99        sample         15.713           ms/op
Client.listUser:listUser·p0.999       sample         19.196           ms/op
Client.listUser:listUser·p0.9999      sample         21.135           ms/op
Client.listUser:listUser·p1.00        sample         21.135           ms/op
