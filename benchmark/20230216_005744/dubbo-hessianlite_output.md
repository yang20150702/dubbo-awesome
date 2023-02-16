# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.097 ops/ms
Iteration   1: 2.239 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.239 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.768 ops/ms
Iteration   1: 7.123 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.123 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.122 ops/ms
Iteration   1: 5.157 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.157 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.887 ops/ms
Iteration   1: 1.251 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.251 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 20.910 ±(99.9%) 0.302 ms/op
Iteration   1: 7.950 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.950 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.641 ±(99.9%) 0.089 ms/op
Iteration   1: 4.209 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.209 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.362 ±(99.9%) 0.141 ms/op
Iteration   1: 5.533 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 29.770 ±(99.9%) 0.651 ms/op
Iteration   1: 18.264 ±(99.9%) 0.095 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.264 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.619 ±(99.9%) 0.448 ms/op
Iteration   1: 7.699 ±(99.9%) 0.167 ms/op
                 createUser·p0.00:   2.716 ms/op
                 createUser·p0.50:   7.193 ms/op
                 createUser·p0.90:   8.389 ms/op
                 createUser·p0.95:   10.040 ms/op
                 createUser·p0.99:   21.806 ms/op
                 createUser·p0.999:  41.222 ms/op
                 createUser·p0.9999: 41.550 ms/op
                 createUser·p1.00:   41.550 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4153
  mean =      7.699 ±(99.9%) 0.167 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 133 
    [ 5.000, 10.000) = 3812 
    [10.000, 15.000) = 143 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 28 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      2.716 ms/op
     p(50.0000) =      7.193 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =     10.040 ms/op
     p(99.0000) =     21.806 ms/op
     p(99.9000) =     41.222 ms/op
     p(99.9900) =     41.550 ms/op
     p(99.9990) =     41.550 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.597 ±(99.9%) 0.215 ms/op
Iteration   1: 4.663 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.038 ms/op
                 existUser·p0.99:   12.911 ms/op
                 existUser·p0.999:  14.977 ms/op
                 existUser·p0.9999: 15.008 ms/op
                 existUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 6865
  mean =      4.663 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 45 
    [ 2.500,  3.750) = 450 
    [ 3.750,  5.000) = 5990 
    [ 5.000,  6.250) = 188 
    [ 6.250,  7.500) = 27 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =     12.911 ms/op
     p(99.9000) =     14.977 ms/op
     p(99.9900) =     15.008 ms/op
     p(99.9990) =     15.008 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.185 ±(99.9%) 0.313 ms/op
Iteration   1: 4.778 ±(99.9%) 0.072 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   4.555 ms/op
                 getUser·p0.90:   5.541 ms/op
                 getUser·p0.95:   6.563 ms/op
                 getUser·p0.99:   15.423 ms/op
                 getUser·p0.999:  20.813 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6915
  mean =      4.778 ±(99.9%) 0.072 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 5287 
    [ 5.000,  7.500) = 1412 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.542 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.541 ms/op
     p(95.0000) =      6.563 ms/op
     p(99.0000) =     15.423 ms/op
     p(99.9000) =     20.813 ms/op
     p(99.9900) =     21.398 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 28.745 ±(99.9%) 0.843 ms/op
Iteration   1: 19.266 ±(99.9%) 1.172 ms/op
                 listUser·p0.00:   6.119 ms/op
                 listUser·p0.50:   17.809 ms/op
                 listUser·p0.90:   20.922 ms/op
                 listUser·p0.95:   27.533 ms/op
                 listUser·p0.99:   115.868 ms/op
                 listUser·p0.999:  134.751 ms/op
                 listUser·p0.9999: 135.266 ms/op
                 listUser·p1.00:   135.266 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1654
  mean =     19.266 ±(99.9%) 1.172 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 44 
    [ 12.500,  25.000) = 1489 
    [ 25.000,  37.500) = 89 
    [ 37.500,  50.000) = 0 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 0 
    [100.000, 112.500) = 12 
    [112.500, 125.000) = 11 
    [125.000, 137.500) = 9 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.119 ms/op
     p(50.0000) =     17.809 ms/op
     p(90.0000) =     20.922 ms/op
     p(95.0000) =     27.533 ms/op
     p(99.0000) =    115.868 ms/op
     p(99.9000) =    134.751 ms/op
     p(99.9900) =    135.266 ms/op
     p(99.9990) =    135.266 ms/op
     p(99.9999) =    135.266 ms/op
    p(100.0000) =    135.266 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          2.239          ops/ms
Client.existUser                       thrpt          7.123          ops/ms
Client.getUser                         thrpt          5.157          ops/ms
Client.listUser                        thrpt          1.251          ops/ms
Client.createUser                       avgt          7.950           ms/op
Client.existUser                        avgt          4.209           ms/op
Client.getUser                          avgt          5.533           ms/op
Client.listUser                         avgt         18.264           ms/op
Client.createUser                     sample  4153    7.699 ± 0.167   ms/op
Client.createUser:createUser·p0.00    sample          2.716           ms/op
Client.createUser:createUser·p0.50    sample          7.193           ms/op
Client.createUser:createUser·p0.90    sample          8.389           ms/op
Client.createUser:createUser·p0.95    sample         10.040           ms/op
Client.createUser:createUser·p0.99    sample         21.806           ms/op
Client.createUser:createUser·p0.999   sample         41.222           ms/op
Client.createUser:createUser·p0.9999  sample         41.550           ms/op
Client.createUser:createUser·p1.00    sample         41.550           ms/op
Client.existUser                      sample  6865    4.663 ± 0.048   ms/op
Client.existUser:existUser·p0.00      sample          1.446           ms/op
Client.existUser:existUser·p0.50      sample          4.604           ms/op
Client.existUser:existUser·p0.90      sample          4.932           ms/op
Client.existUser:existUser·p0.95      sample          5.038           ms/op
Client.existUser:existUser·p0.99      sample         12.911           ms/op
Client.existUser:existUser·p0.999     sample         14.977           ms/op
Client.existUser:existUser·p0.9999    sample         15.008           ms/op
Client.existUser:existUser·p1.00      sample         15.008           ms/op
Client.getUser                        sample  6915    4.778 ± 0.072   ms/op
Client.getUser:getUser·p0.00          sample          1.542           ms/op
Client.getUser:getUser·p0.50          sample          4.555           ms/op
Client.getUser:getUser·p0.90          sample          5.541           ms/op
Client.getUser:getUser·p0.95          sample          6.563           ms/op
Client.getUser:getUser·p0.99          sample         15.423           ms/op
Client.getUser:getUser·p0.999         sample         20.813           ms/op
Client.getUser:getUser·p0.9999        sample         21.398           ms/op
Client.getUser:getUser·p1.00          sample         21.398           ms/op
Client.listUser                       sample  1654   19.266 ± 1.172   ms/op
Client.listUser:listUser·p0.00        sample          6.119           ms/op
Client.listUser:listUser·p0.50        sample         17.809           ms/op
Client.listUser:listUser·p0.90        sample         20.922           ms/op
Client.listUser:listUser·p0.95        sample         27.533           ms/op
Client.listUser:listUser·p0.99        sample        115.868           ms/op
Client.listUser:listUser·p0.999       sample        134.751           ms/op
Client.listUser:listUser·p0.9999      sample        135.266           ms/op
Client.listUser:listUser·p1.00        sample        135.266           ms/op
