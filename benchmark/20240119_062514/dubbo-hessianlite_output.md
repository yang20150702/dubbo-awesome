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
# Warmup Iteration   1: 2.179 ops/ms
Iteration   1: 5.912 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.912 ops/ms


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
# Warmup Iteration   1: 6.468 ops/ms
Iteration   1: 11.772 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.772 ops/ms


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
# Warmup Iteration   1: 4.054 ops/ms
Iteration   1: 7.469 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.469 ops/ms


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
# Warmup Iteration   1: 1.979 ops/ms
Iteration   1: 3.431 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.431 ops/ms


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
# Warmup Iteration   1: 5.807 ±(99.9%) 0.077 ms/op
Iteration   1: 3.128 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.128 ms/op


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
# Warmup Iteration   1: 3.395 ±(99.9%) 0.030 ms/op
Iteration   1: 2.120 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.120 ms/op


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.051 ms/op
Iteration   1: 3.078 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.078 ms/op


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
# Warmup Iteration   1: 12.241 ±(99.9%) 0.212 ms/op
Iteration   1: 7.654 ±(99.9%) 0.084 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.654 ms/op


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
# Warmup Iteration   1: 5.496 ±(99.9%) 0.129 ms/op
Iteration   1: 3.158 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.036 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   4.105 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   8.334 ms/op
                 createUser·p0.999:  17.963 ms/op
                 createUser·p0.9999: 18.118 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10266
  mean =      3.158 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 6 
    [ 1.250,  2.500) = 1871 
    [ 2.500,  3.750) = 6516 
    [ 3.750,  5.000) = 1564 
    [ 5.000,  6.250) = 77 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      4.105 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      8.334 ms/op
     p(99.9000) =     17.963 ms/op
     p(99.9900) =     18.118 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 2.961 ±(99.9%) 0.080 ms/op
Iteration   1: 2.019 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.585 ms/op
                 existUser·p0.95:   2.764 ms/op
                 existUser·p0.99:   3.406 ms/op
                 existUser·p0.999:  5.359 ms/op
                 existUser·p0.9999: 6.919 ms/op
                 existUser·p1.00:   6.996 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15844
  mean =      2.019 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 28 
    [1.000, 1.500) = 1778 
    [1.500, 2.000) = 6497 
    [2.000, 2.500) = 5541 
    [2.500, 3.000) = 1604 
    [3.000, 3.500) = 264 
    [3.500, 4.000) = 34 
    [4.000, 4.500) = 45 
    [4.500, 5.000) = 11 
    [5.000, 5.500) = 32 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.764 ms/op
     p(99.0000) =      3.406 ms/op
     p(99.9000) =      5.359 ms/op
     p(99.9900) =      6.919 ms/op
     p(99.9990) =      6.996 ms/op
     p(99.9999) =      6.996 ms/op
    p(100.0000) =      6.996 ms/op


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.115 ms/op
Iteration   1: 3.292 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.409 ms/op
                 getUser·p0.99:   6.118 ms/op
                 getUser·p0.999:  14.968 ms/op
                 getUser·p0.9999: 16.663 ms/op
                 getUser·p1.00:   16.663 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9716
  mean =      3.292 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1160 
    [ 2.500,  3.750) = 6878 
    [ 3.750,  5.000) = 1450 
    [ 5.000,  6.250) = 133 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.409 ms/op
     p(99.0000) =      6.118 ms/op
     p(99.9000) =     14.968 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     16.663 ms/op
     p(99.9999) =     16.663 ms/op
    p(100.0000) =     16.663 ms/op


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
# Warmup Iteration   1: 12.741 ±(99.9%) 0.519 ms/op
Iteration   1: 9.349 ±(99.9%) 0.175 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   8.782 ms/op
                 listUser·p0.90:   12.698 ms/op
                 listUser·p0.95:   14.647 ms/op
                 listUser·p0.99:   20.447 ms/op
                 listUser·p0.999:  36.438 ms/op
                 listUser·p0.9999: 47.841 ms/op
                 listUser·p1.00:   47.841 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3375
  mean =      9.349 ±(99.9%) 0.175 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 45 
    [ 5.000, 10.000) = 2362 
    [10.000, 15.000) = 816 
    [15.000, 20.000) = 110 
    [20.000, 25.000) = 29 
    [25.000, 30.000) = 4 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.286 ms/op
     p(50.0000) =      8.782 ms/op
     p(90.0000) =     12.698 ms/op
     p(95.0000) =     14.647 ms/op
     p(99.0000) =     20.447 ms/op
     p(99.9000) =     36.438 ms/op
     p(99.9900) =     47.841 ms/op
     p(99.9990) =     47.841 ms/op
     p(99.9999) =     47.841 ms/op
    p(100.0000) =     47.841 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.912          ops/ms
Client.existUser                       thrpt         11.772          ops/ms
Client.getUser                         thrpt          7.469          ops/ms
Client.listUser                        thrpt          3.431          ops/ms
Client.createUser                       avgt          3.128           ms/op
Client.existUser                        avgt          2.120           ms/op
Client.getUser                          avgt          3.078           ms/op
Client.listUser                         avgt          7.654           ms/op
Client.createUser                     sample  10266   3.158 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.036           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          4.105           ms/op
Client.createUser:createUser·p0.95    sample          4.637           ms/op
Client.createUser:createUser·p0.99    sample          8.334           ms/op
Client.createUser:createUser·p0.999   sample         17.963           ms/op
Client.createUser:createUser·p0.9999  sample         18.118           ms/op
Client.createUser:createUser·p1.00    sample         18.121           ms/op
Client.existUser                      sample  15844   2.019 ± 0.013   ms/op
Client.existUser:existUser·p0.00      sample          0.727           ms/op
Client.existUser:existUser·p0.50      sample          1.974           ms/op
Client.existUser:existUser·p0.90      sample          2.585           ms/op
Client.existUser:existUser·p0.95      sample          2.764           ms/op
Client.existUser:existUser·p0.99      sample          3.406           ms/op
Client.existUser:existUser·p0.999     sample          5.359           ms/op
Client.existUser:existUser·p0.9999    sample          6.919           ms/op
Client.existUser:existUser·p1.00      sample          6.996           ms/op
Client.getUser                        sample   9716   3.292 ± 0.035   ms/op
Client.getUser:getUser·p0.00          sample          1.124           ms/op
Client.getUser:getUser·p0.50          sample          3.199           ms/op
Client.getUser:getUser·p0.90          sample          4.035           ms/op
Client.getUser:getUser·p0.95          sample          4.409           ms/op
Client.getUser:getUser·p0.99          sample          6.118           ms/op
Client.getUser:getUser·p0.999         sample         14.968           ms/op
Client.getUser:getUser·p0.9999        sample         16.663           ms/op
Client.getUser:getUser·p1.00          sample         16.663           ms/op
Client.listUser                       sample   3375   9.349 ± 0.175   ms/op
Client.listUser:listUser·p0.00        sample          2.286           ms/op
Client.listUser:listUser·p0.50        sample          8.782           ms/op
Client.listUser:listUser·p0.90        sample         12.698           ms/op
Client.listUser:listUser·p0.95        sample         14.647           ms/op
Client.listUser:listUser·p0.99        sample         20.447           ms/op
Client.listUser:listUser·p0.999       sample         36.438           ms/op
Client.listUser:listUser·p0.9999      sample         47.841           ms/op
Client.listUser:listUser·p1.00        sample         47.841           ms/op
