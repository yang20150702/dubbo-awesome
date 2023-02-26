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
# Warmup Iteration   1: 0.993 ops/ms
Iteration   1: 2.307 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.307 ops/ms


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
# Warmup Iteration   1: 3.044 ops/ms
Iteration   1: 5.039 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.039 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.328 ops/ms
Iteration   1: 3.922 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.922 ops/ms


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
# Warmup Iteration   1: 0.901 ops/ms
Iteration   1: 1.235 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.235 ops/ms


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
# Warmup Iteration   1: 18.932 ±(99.9%) 0.300 ms/op
Iteration   1: 9.473 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.473 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.831 ±(99.9%) 0.122 ms/op
Iteration   1: 4.115 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.115 ms/op


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
# Warmup Iteration   1: 10.031 ±(99.9%) 0.174 ms/op
Iteration   1: 5.276 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.276 ms/op


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
# Warmup Iteration   1: 29.251 ±(99.9%) 0.497 ms/op
Iteration   1: 18.961 ±(99.9%) 0.123 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.961 ms/op


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
# Warmup Iteration   1: 12.368 ±(99.9%) 0.380 ms/op
Iteration   1: 6.354 ±(99.9%) 0.107 ms/op
                 createUser·p0.00:   2.187 ms/op
                 createUser·p0.50:   6.332 ms/op
                 createUser·p0.90:   7.340 ms/op
                 createUser·p0.95:   8.249 ms/op
                 createUser·p0.99:   16.679 ms/op
                 createUser·p0.999:  28.802 ms/op
                 createUser·p0.9999: 29.131 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5030
  mean =      6.354 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 923 
    [ 5.000,  7.500) = 3694 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.187 ms/op
     p(50.0000) =      6.332 ms/op
     p(90.0000) =      7.340 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     16.679 ms/op
     p(99.9000) =     28.802 ms/op
     p(99.9900) =     29.131 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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
# Warmup Iteration   1: 8.057 ±(99.9%) 0.254 ms/op
Iteration   1: 4.380 ±(99.9%) 0.058 ms/op
                 existUser·p0.00:   1.039 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   5.538 ms/op
                 existUser·p0.95:   5.644 ms/op
                 existUser·p0.99:   11.682 ms/op
                 existUser·p0.999:  14.893 ms/op
                 existUser·p0.9999: 14.926 ms/op
                 existUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7499
  mean =      4.380 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 565 
    [ 2.500,  3.750) = 2283 
    [ 3.750,  5.000) = 1551 
    [ 5.000,  6.250) = 2938 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =     11.682 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     14.926 ms/op
     p(99.9990) =     14.926 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 11.316 ±(99.9%) 0.434 ms/op
Iteration   1: 5.082 ±(99.9%) 0.102 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   4.506 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   8.618 ms/op
                 getUser·p0.99:   17.334 ms/op
                 getUser·p0.999:  22.548 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6292
  mean =      5.082 ±(99.9%) 0.102 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 4628 
    [ 5.000,  7.500) = 1261 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.857 ms/op
     p(95.0000) =      8.618 ms/op
     p(99.0000) =     17.334 ms/op
     p(99.9000) =     22.548 ms/op
     p(99.9900) =     27.099 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 28.608 ±(99.9%) 0.953 ms/op
Iteration   1: 19.871 ±(99.9%) 0.372 ms/op
                 listUser·p0.00:   6.185 ms/op
                 listUser·p0.50:   19.350 ms/op
                 listUser·p0.90:   24.871 ms/op
                 listUser·p0.95:   25.461 ms/op
                 listUser·p0.99:   32.126 ms/op
                 listUser·p0.999:  39.022 ms/op
                 listUser·p0.9999: 39.453 ms/op
                 listUser·p1.00:   39.453 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1596
  mean =     19.871 ±(99.9%) 0.372 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 5 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 498 
    [20.000, 22.500) = 210 
    [22.500, 25.000) = 401 
    [25.000, 27.500) = 107 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      6.185 ms/op
     p(50.0000) =     19.350 ms/op
     p(90.0000) =     24.871 ms/op
     p(95.0000) =     25.461 ms/op
     p(99.0000) =     32.126 ms/op
     p(99.9000) =     39.022 ms/op
     p(99.9900) =     39.453 ms/op
     p(99.9990) =     39.453 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.307          ops/ms
Client.existUser                       thrpt         5.039          ops/ms
Client.getUser                         thrpt         3.922          ops/ms
Client.listUser                        thrpt         1.235          ops/ms
Client.createUser                       avgt         9.473           ms/op
Client.existUser                        avgt         4.115           ms/op
Client.getUser                          avgt         5.276           ms/op
Client.listUser                         avgt        18.961           ms/op
Client.createUser                     sample  5030   6.354 ± 0.107   ms/op
Client.createUser:createUser·p0.00    sample         2.187           ms/op
Client.createUser:createUser·p0.50    sample         6.332           ms/op
Client.createUser:createUser·p0.90    sample         7.340           ms/op
Client.createUser:createUser·p0.95    sample         8.249           ms/op
Client.createUser:createUser·p0.99    sample        16.679           ms/op
Client.createUser:createUser·p0.999   sample        28.802           ms/op
Client.createUser:createUser·p0.9999  sample        29.131           ms/op
Client.createUser:createUser·p1.00    sample        29.131           ms/op
Client.existUser                      sample  7499   4.380 ± 0.058   ms/op
Client.existUser:existUser·p0.00      sample         1.039           ms/op
Client.existUser:existUser·p0.50      sample         3.977           ms/op
Client.existUser:existUser·p0.90      sample         5.538           ms/op
Client.existUser:existUser·p0.95      sample         5.644           ms/op
Client.existUser:existUser·p0.99      sample        11.682           ms/op
Client.existUser:existUser·p0.999     sample        14.893           ms/op
Client.existUser:existUser·p0.9999    sample        14.926           ms/op
Client.existUser:existUser·p1.00      sample        14.926           ms/op
Client.getUser                        sample  6292   5.082 ± 0.102   ms/op
Client.getUser:getUser·p0.00          sample         1.329           ms/op
Client.getUser:getUser·p0.50          sample         4.506           ms/op
Client.getUser:getUser·p0.90          sample         5.857           ms/op
Client.getUser:getUser·p0.95          sample         8.618           ms/op
Client.getUser:getUser·p0.99          sample        17.334           ms/op
Client.getUser:getUser·p0.999         sample        22.548           ms/op
Client.getUser:getUser·p0.9999        sample        27.099           ms/op
Client.getUser:getUser·p1.00          sample        27.099           ms/op
Client.listUser                       sample  1596  19.871 ± 0.372   ms/op
Client.listUser:listUser·p0.00        sample         6.185           ms/op
Client.listUser:listUser·p0.50        sample        19.350           ms/op
Client.listUser:listUser·p0.90        sample        24.871           ms/op
Client.listUser:listUser·p0.95        sample        25.461           ms/op
Client.listUser:listUser·p0.99        sample        32.126           ms/op
Client.listUser:listUser·p0.999       sample        39.022           ms/op
Client.listUser:listUser·p0.9999      sample        39.453           ms/op
Client.listUser:listUser·p1.00        sample        39.453           ms/op
