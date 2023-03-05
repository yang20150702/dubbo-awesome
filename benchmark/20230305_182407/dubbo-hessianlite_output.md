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
# Warmup Iteration   1: 1.007 ops/ms
Iteration   1: 2.058 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.058 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.836 ops/ms
Iteration   1: 6.293 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.293 ops/ms


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
# Warmup Iteration   1: 1.850 ops/ms
Iteration   1: 4.927 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.927 ops/ms


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
# Warmup Iteration   1: 0.858 ops/ms
Iteration   1: 1.530 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.530 ops/ms


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
# Warmup Iteration   1: 17.727 ±(99.9%) 0.354 ms/op
Iteration   1: 9.289 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.289 ms/op


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
# Warmup Iteration   1: 8.152 ±(99.9%) 0.096 ms/op
Iteration   1: 4.344 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.344 ms/op


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
# Warmup Iteration   1: 9.813 ±(99.9%) 0.181 ms/op
Iteration   1: 5.032 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.032 ms/op


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
# Warmup Iteration   1: 27.191 ±(99.9%) 0.448 ms/op
Iteration   1: 16.716 ±(99.9%) 0.096 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.716 ms/op


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
# Warmup Iteration   1: 11.880 ±(99.9%) 0.408 ms/op
Iteration   1: 6.858 ±(99.9%) 0.119 ms/op
                 createUser·p0.00:   5.243 ms/op
                 createUser·p0.50:   6.316 ms/op
                 createUser·p0.90:   7.793 ms/op
                 createUser·p0.95:   9.409 ms/op
                 createUser·p0.99:   20.152 ms/op
                 createUser·p0.999:  20.939 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4706
  mean =      6.858 ±(99.9%) 0.119 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 4114 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 3 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      5.243 ms/op
     p(50.0000) =      6.316 ms/op
     p(90.0000) =      7.793 ms/op
     p(95.0000) =      9.409 ms/op
     p(99.0000) =     20.152 ms/op
     p(99.9000) =     20.939 ms/op
     p(99.9900) =     27.394 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 6.960 ±(99.9%) 0.212 ms/op
Iteration   1: 3.639 ±(99.9%) 0.075 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   7.528 ms/op
                 existUser·p0.99:   13.726 ms/op
                 existUser·p0.999:  20.060 ms/op
                 existUser·p0.9999: 24.216 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8822
  mean =      3.639 ±(99.9%) 0.075 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 450 
    [ 2.500,  5.000) = 7545 
    [ 5.000,  7.500) = 365 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =     13.726 ms/op
     p(99.9000) =     20.060 ms/op
     p(99.9900) =     24.216 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 12.012 ±(99.9%) 0.384 ms/op
Iteration   1: 4.998 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   2.265 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.831 ms/op
                 getUser·p0.99:   7.234 ms/op
                 getUser·p0.999:  16.433 ms/op
                 getUser·p0.9999: 16.515 ms/op
                 getUser·p1.00:   16.515 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6442
  mean =      4.998 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 4 
    [ 2.500,  3.750) = 116 
    [ 3.750,  5.000) = 3203 
    [ 5.000,  6.250) = 2954 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.265 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      5.521 ms/op
     p(95.0000) =      5.831 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     16.433 ms/op
     p(99.9900) =     16.515 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.515 ms/op
    p(100.0000) =     16.515 ms/op


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
# Warmup Iteration   1: 29.012 ±(99.9%) 1.365 ms/op
Iteration   1: 18.190 ±(99.9%) 0.343 ms/op
                 listUser·p0.00:   9.519 ms/op
                 listUser·p0.50:   16.384 ms/op
                 listUser·p0.90:   25.625 ms/op
                 listUser·p0.95:   27.853 ms/op
                 listUser·p0.99:   31.107 ms/op
                 listUser·p0.999:  34.890 ms/op
                 listUser·p0.9999: 35.193 ms/op
                 listUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1769
  mean =     18.190 ±(99.9%) 0.343 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 287 
    [15.000, 17.500) = 736 
    [17.500, 20.000) = 294 
    [20.000, 22.500) = 145 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      9.519 ms/op
     p(50.0000) =     16.384 ms/op
     p(90.0000) =     25.625 ms/op
     p(95.0000) =     27.853 ms/op
     p(99.0000) =     31.107 ms/op
     p(99.9000) =     34.890 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.058          ops/ms
Client.existUser                       thrpt         6.293          ops/ms
Client.getUser                         thrpt         4.927          ops/ms
Client.listUser                        thrpt         1.530          ops/ms
Client.createUser                       avgt         9.289           ms/op
Client.existUser                        avgt         4.344           ms/op
Client.getUser                          avgt         5.032           ms/op
Client.listUser                         avgt        16.716           ms/op
Client.createUser                     sample  4706   6.858 ± 0.119   ms/op
Client.createUser:createUser·p0.00    sample         5.243           ms/op
Client.createUser:createUser·p0.50    sample         6.316           ms/op
Client.createUser:createUser·p0.90    sample         7.793           ms/op
Client.createUser:createUser·p0.95    sample         9.409           ms/op
Client.createUser:createUser·p0.99    sample        20.152           ms/op
Client.createUser:createUser·p0.999   sample        20.939           ms/op
Client.createUser:createUser·p0.9999  sample        27.394           ms/op
Client.createUser:createUser·p1.00    sample        27.394           ms/op
Client.existUser                      sample  8822   3.639 ± 0.075   ms/op
Client.existUser:existUser·p0.00      sample         0.592           ms/op
Client.existUser:existUser·p0.50      sample         3.023           ms/op
Client.existUser:existUser·p0.90      sample         4.866           ms/op
Client.existUser:existUser·p0.95      sample         7.528           ms/op
Client.existUser:existUser·p0.99      sample        13.726           ms/op
Client.existUser:existUser·p0.999     sample        20.060           ms/op
Client.existUser:existUser·p0.9999    sample        24.216           ms/op
Client.existUser:existUser·p1.00      sample        24.216           ms/op
Client.getUser                        sample  6442   4.998 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample         2.265           ms/op
Client.getUser:getUser·p0.50          sample         4.997           ms/op
Client.getUser:getUser·p0.90          sample         5.521           ms/op
Client.getUser:getUser·p0.95          sample         5.831           ms/op
Client.getUser:getUser·p0.99          sample         7.234           ms/op
Client.getUser:getUser·p0.999         sample        16.433           ms/op
Client.getUser:getUser·p0.9999        sample        16.515           ms/op
Client.getUser:getUser·p1.00          sample        16.515           ms/op
Client.listUser                       sample  1769  18.190 ± 0.343   ms/op
Client.listUser:listUser·p0.00        sample         9.519           ms/op
Client.listUser:listUser·p0.50        sample        16.384           ms/op
Client.listUser:listUser·p0.90        sample        25.625           ms/op
Client.listUser:listUser·p0.95        sample        27.853           ms/op
Client.listUser:listUser·p0.99        sample        31.107           ms/op
Client.listUser:listUser·p0.999       sample        34.890           ms/op
Client.listUser:listUser·p0.9999      sample        35.193           ms/op
Client.listUser:listUser·p1.00        sample        35.193           ms/op
