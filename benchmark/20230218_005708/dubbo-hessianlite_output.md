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
# Warmup Iteration   1: 0.503 ops/ms
Iteration   1: 1.758 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.758 ops/ms


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
# Warmup Iteration   1: 2.404 ops/ms
Iteration   1: 6.485 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.485 ops/ms


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
# Warmup Iteration   1: 1.440 ops/ms
Iteration   1: 4.186 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.186 ops/ms


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
# Warmup Iteration   1: 0.795 ops/ms
Iteration   1: 1.176 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.176 ops/ms


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
# Warmup Iteration   1: 18.708 ±(99.9%) 0.537 ms/op
Iteration   1: 9.817 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  9.817 ms/op


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
# Warmup Iteration   1: 7.879 ±(99.9%) 0.097 ms/op
Iteration   1: 4.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.052 ms/op


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
# Warmup Iteration   1: 11.224 ±(99.9%) 0.194 ms/op
Iteration   1: 4.657 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.657 ms/op


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
# Warmup Iteration   1: 32.941 ±(99.9%) 1.040 ms/op
Iteration   1: 21.836 ±(99.9%) 0.236 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  21.836 ms/op


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
# Warmup Iteration   1: 14.315 ±(99.9%) 0.449 ms/op
Iteration   1: 6.573 ±(99.9%) 0.132 ms/op
                 createUser·p0.00:   2.789 ms/op
                 createUser·p0.50:   6.447 ms/op
                 createUser·p0.90:   7.062 ms/op
                 createUser·p0.95:   7.353 ms/op
                 createUser·p0.99:   14.561 ms/op
                 createUser·p0.999:  38.016 ms/op
                 createUser·p0.9999: 38.207 ms/op
                 createUser·p1.00:   38.207 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4927
  mean =      6.573 ±(99.9%) 0.132 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 499 
    [ 5.000,  7.500) = 4203 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      2.789 ms/op
     p(50.0000) =      6.447 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      7.353 ms/op
     p(99.0000) =     14.561 ms/op
     p(99.9000) =     38.016 ms/op
     p(99.9900) =     38.207 ms/op
     p(99.9990) =     38.207 ms/op
     p(99.9999) =     38.207 ms/op
    p(100.0000) =     38.207 ms/op


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
# Warmup Iteration   1: 7.928 ±(99.9%) 0.244 ms/op
Iteration   1: 4.495 ±(99.9%) 0.082 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   4.383 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   8.566 ms/op
                 existUser·p0.99:   13.402 ms/op
                 existUser·p0.999:  17.820 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7185
  mean =      4.495 ±(99.9%) 0.082 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 137 
    [ 1.250,  2.500) = 602 
    [ 2.500,  3.750) = 1754 
    [ 3.750,  5.000) = 3264 
    [ 5.000,  6.250) = 847 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      8.566 ms/op
     p(99.0000) =     13.402 ms/op
     p(99.9000) =     17.820 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


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
# Warmup Iteration   1: 12.933 ±(99.9%) 0.397 ms/op
Iteration   1: 5.226 ±(99.9%) 0.089 ms/op
                 getUser·p0.00:   2.204 ms/op
                 getUser·p0.50:   4.833 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   8.716 ms/op
                 getUser·p0.99:   15.479 ms/op
                 getUser·p0.999:  22.933 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6073
  mean =      5.226 ±(99.9%) 0.089 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 3606 
    [ 5.000,  7.500) = 1991 
    [ 7.500, 10.000) = 259 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.204 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      6.783 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     15.479 ms/op
     p(99.9000) =     22.933 ms/op
     p(99.9900) =     25.166 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 30.400 ±(99.9%) 0.954 ms/op
Iteration   1: 18.854 ±(99.9%) 0.220 ms/op
                 listUser·p0.00:   6.808 ms/op
                 listUser·p0.50:   17.596 ms/op
                 listUser·p0.90:   22.118 ms/op
                 listUser·p0.95:   23.069 ms/op
                 listUser·p0.99:   28.167 ms/op
                 listUser·p0.999:  34.700 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1704
  mean =     18.854 ±(99.9%) 0.220 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 0 
    [ 5.000,  7.500) = 3 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 793 
    [17.500, 20.000) = 293 
    [20.000, 22.500) = 457 
    [22.500, 25.000) = 107 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.808 ms/op
     p(50.0000) =     17.596 ms/op
     p(90.0000) =     22.118 ms/op
     p(95.0000) =     23.069 ms/op
     p(99.0000) =     28.167 ms/op
     p(99.9000) =     34.700 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.758          ops/ms
Client.existUser                       thrpt         6.485          ops/ms
Client.getUser                         thrpt         4.186          ops/ms
Client.listUser                        thrpt         1.176          ops/ms
Client.createUser                       avgt         9.817           ms/op
Client.existUser                        avgt         4.052           ms/op
Client.getUser                          avgt         4.657           ms/op
Client.listUser                         avgt        21.836           ms/op
Client.createUser                     sample  4927   6.573 ± 0.132   ms/op
Client.createUser:createUser·p0.00    sample         2.789           ms/op
Client.createUser:createUser·p0.50    sample         6.447           ms/op
Client.createUser:createUser·p0.90    sample         7.062           ms/op
Client.createUser:createUser·p0.95    sample         7.353           ms/op
Client.createUser:createUser·p0.99    sample        14.561           ms/op
Client.createUser:createUser·p0.999   sample        38.016           ms/op
Client.createUser:createUser·p0.9999  sample        38.207           ms/op
Client.createUser:createUser·p1.00    sample        38.207           ms/op
Client.existUser                      sample  7185   4.495 ± 0.082   ms/op
Client.existUser:existUser·p0.00      sample         0.679           ms/op
Client.existUser:existUser·p0.50      sample         4.383           ms/op
Client.existUser:existUser·p0.90      sample         5.595           ms/op
Client.existUser:existUser·p0.95      sample         8.566           ms/op
Client.existUser:existUser·p0.99      sample        13.402           ms/op
Client.existUser:existUser·p0.999     sample        17.820           ms/op
Client.existUser:existUser·p0.9999    sample        18.022           ms/op
Client.existUser:existUser·p1.00      sample        18.022           ms/op
Client.getUser                        sample  6073   5.226 ± 0.089   ms/op
Client.getUser:getUser·p0.00          sample         2.204           ms/op
Client.getUser:getUser·p0.50          sample         4.833           ms/op
Client.getUser:getUser·p0.90          sample         6.783           ms/op
Client.getUser:getUser·p0.95          sample         8.716           ms/op
Client.getUser:getUser·p0.99          sample        15.479           ms/op
Client.getUser:getUser·p0.999         sample        22.933           ms/op
Client.getUser:getUser·p0.9999        sample        25.166           ms/op
Client.getUser:getUser·p1.00          sample        25.166           ms/op
Client.listUser                       sample  1704  18.854 ± 0.220   ms/op
Client.listUser:listUser·p0.00        sample         6.808           ms/op
Client.listUser:listUser·p0.50        sample        17.596           ms/op
Client.listUser:listUser·p0.90        sample        22.118           ms/op
Client.listUser:listUser·p0.95        sample        23.069           ms/op
Client.listUser:listUser·p0.99        sample        28.167           ms/op
Client.listUser:listUser·p0.999       sample        34.700           ms/op
Client.listUser:listUser·p0.9999      sample        34.931           ms/op
Client.listUser:listUser·p1.00        sample        34.931           ms/op
