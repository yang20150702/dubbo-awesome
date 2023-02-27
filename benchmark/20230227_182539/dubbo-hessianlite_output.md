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
# Warmup Iteration   1: 1.235 ops/ms
Iteration   1: 2.531 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.531 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 2.861 ops/ms
Iteration   1: 7.965 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.965 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.751 ops/ms
Iteration   1: 5.134 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.134 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.988 ops/ms
Iteration   1: 1.377 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.377 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 12.337 ±(99.9%) 0.148 ms/op
Iteration   1: 6.131 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.131 ms/op


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
# Warmup Iteration   1: 6.093 ±(99.9%) 0.067 ms/op
Iteration   1: 3.604 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.604 ms/op


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
# Warmup Iteration   1: 10.011 ±(99.9%) 0.166 ms/op
Iteration   1: 4.536 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.536 ms/op


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
# Warmup Iteration   1: 29.343 ±(99.9%) 0.355 ms/op
Iteration   1: 17.654 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  17.654 ms/op


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
# Warmup Iteration   1: 9.787 ±(99.9%) 0.323 ms/op
Iteration   1: 6.017 ±(99.9%) 0.098 ms/op
                 createUser·p0.00:   2.916 ms/op
                 createUser·p0.50:   5.415 ms/op
                 createUser·p0.90:   6.996 ms/op
                 createUser·p0.95:   10.912 ms/op
                 createUser·p0.99:   15.811 ms/op
                 createUser·p0.999:  19.071 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5452
  mean =      6.017 ±(99.9%) 0.098 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 13 
    [ 3.750,  5.000) = 468 
    [ 5.000,  6.250) = 4348 
    [ 6.250,  7.500) = 138 
    [ 7.500,  8.750) = 66 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 163 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.916 ms/op
     p(50.0000) =      5.415 ms/op
     p(90.0000) =      6.996 ms/op
     p(95.0000) =     10.912 ms/op
     p(99.0000) =     15.811 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     19.071 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 6.164 ±(99.9%) 0.191 ms/op
Iteration   1: 3.259 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.744 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   6.963 ms/op
                 existUser·p0.99:   12.485 ms/op
                 existUser·p0.999:  28.213 ms/op
                 existUser·p0.9999: 28.246 ms/op
                 existUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9933
  mean =      3.259 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1937 
    [ 2.500,  5.000) = 7293 
    [ 5.000,  7.500) = 238 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.744 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =     12.485 ms/op
     p(99.9000) =     28.213 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     28.246 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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
# Warmup Iteration   1: 9.255 ±(99.9%) 0.402 ms/op
Iteration   1: 4.346 ±(99.9%) 0.101 ms/op
                 getUser·p0.00:   1.350 ms/op
                 getUser·p0.50:   4.059 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.705 ms/op
                 getUser·p0.99:   13.619 ms/op
                 getUser·p0.999:  34.807 ms/op
                 getUser·p0.9999: 47.579 ms/op
                 getUser·p1.00:   47.579 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7376
  mean =      4.346 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 6743 
    [ 5.000, 10.000) = 454 
    [10.000, 15.000) = 115 
    [15.000, 20.000) = 10 
    [20.000, 25.000) = 22 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 26 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.705 ms/op
     p(99.0000) =     13.619 ms/op
     p(99.9000) =     34.807 ms/op
     p(99.9900) =     47.579 ms/op
     p(99.9990) =     47.579 ms/op
     p(99.9999) =     47.579 ms/op
    p(100.0000) =     47.579 ms/op


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
# Warmup Iteration   1: 23.128 ±(99.9%) 0.577 ms/op
Iteration   1: 15.916 ±(99.9%) 0.288 ms/op
                 listUser·p0.00:   11.960 ms/op
                 listUser·p0.50:   14.434 ms/op
                 listUser·p0.90:   20.811 ms/op
                 listUser·p0.95:   26.134 ms/op
                 listUser·p0.99:   33.601 ms/op
                 listUser·p0.999:  39.200 ms/op
                 listUser·p0.9999: 39.322 ms/op
                 listUser·p1.00:   39.322 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 2028
  mean =     15.916 ±(99.9%) 0.288 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 1484 
    [15.000, 17.500) = 256 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =     11.960 ms/op
     p(50.0000) =     14.434 ms/op
     p(90.0000) =     20.811 ms/op
     p(95.0000) =     26.134 ms/op
     p(99.0000) =     33.601 ms/op
     p(99.9000) =     39.200 ms/op
     p(99.9900) =     39.322 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.322 ms/op
    p(100.0000) =     39.322 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.531          ops/ms
Client.existUser                       thrpt         7.965          ops/ms
Client.getUser                         thrpt         5.134          ops/ms
Client.listUser                        thrpt         1.377          ops/ms
Client.createUser                       avgt         6.131           ms/op
Client.existUser                        avgt         3.604           ms/op
Client.getUser                          avgt         4.536           ms/op
Client.listUser                         avgt        17.654           ms/op
Client.createUser                     sample  5452   6.017 ± 0.098   ms/op
Client.createUser:createUser·p0.00    sample         2.916           ms/op
Client.createUser:createUser·p0.50    sample         5.415           ms/op
Client.createUser:createUser·p0.90    sample         6.996           ms/op
Client.createUser:createUser·p0.95    sample        10.912           ms/op
Client.createUser:createUser·p0.99    sample        15.811           ms/op
Client.createUser:createUser·p0.999   sample        19.071           ms/op
Client.createUser:createUser·p0.9999  sample        19.071           ms/op
Client.createUser:createUser·p1.00    sample        19.071           ms/op
Client.existUser                      sample  9933   3.259 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample         0.758           ms/op
Client.existUser:existUser·p0.50      sample         2.744           ms/op
Client.existUser:existUser·p0.90      sample         3.768           ms/op
Client.existUser:existUser·p0.95      sample         6.963           ms/op
Client.existUser:existUser·p0.99      sample        12.485           ms/op
Client.existUser:existUser·p0.999     sample        28.213           ms/op
Client.existUser:existUser·p0.9999    sample        28.246           ms/op
Client.existUser:existUser·p1.00      sample        28.246           ms/op
Client.getUser                        sample  7376   4.346 ± 0.101   ms/op
Client.getUser:getUser·p0.00          sample         1.350           ms/op
Client.getUser:getUser·p0.50          sample         4.059           ms/op
Client.getUser:getUser·p0.90          sample         4.899           ms/op
Client.getUser:getUser·p0.95          sample         5.705           ms/op
Client.getUser:getUser·p0.99          sample        13.619           ms/op
Client.getUser:getUser·p0.999         sample        34.807           ms/op
Client.getUser:getUser·p0.9999        sample        47.579           ms/op
Client.getUser:getUser·p1.00          sample        47.579           ms/op
Client.listUser                       sample  2028  15.916 ± 0.288   ms/op
Client.listUser:listUser·p0.00        sample        11.960           ms/op
Client.listUser:listUser·p0.50        sample        14.434           ms/op
Client.listUser:listUser·p0.90        sample        20.811           ms/op
Client.listUser:listUser·p0.95        sample        26.134           ms/op
Client.listUser:listUser·p0.99        sample        33.601           ms/op
Client.listUser:listUser·p0.999       sample        39.200           ms/op
Client.listUser:listUser·p0.9999      sample        39.322           ms/op
Client.listUser:listUser·p1.00        sample        39.322           ms/op
