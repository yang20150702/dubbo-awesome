# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.031 ops/ms
Iteration   1: 2.046 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.046 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 2.882 ops/ms
Iteration   1: 6.107 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.107 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.098 ops/ms
Iteration   1: 4.640 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.640 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 0.852 ops/ms
Iteration   1: 1.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.355 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.727 ±(99.9%) 0.249 ms/op
Iteration   1: 7.534 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.534 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ±(99.9%) 0.093 ms/op
Iteration   1: 3.726 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.414 ±(99.9%) 0.144 ms/op
Iteration   1: 5.111 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.111 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 31.370 ±(99.9%) 0.734 ms/op
Iteration   1: 20.416 ±(99.9%) 0.139 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  20.416 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 13.689 ±(99.9%) 0.481 ms/op
Iteration   1: 6.984 ±(99.9%) 0.081 ms/op
                 createUser·p0.00:   2.609 ms/op
                 createUser·p0.50:   6.660 ms/op
                 createUser·p0.90:   7.714 ms/op
                 createUser·p0.95:   8.348 ms/op
                 createUser·p0.99:   16.368 ms/op
                 createUser·p0.999:  22.033 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4603
  mean =      6.984 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 26 
    [ 5.000,  7.500) = 3749 
    [ 7.500, 10.000) = 679 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.609 ms/op
     p(50.0000) =      6.660 ms/op
     p(90.0000) =      7.714 ms/op
     p(95.0000) =      8.348 ms/op
     p(99.0000) =     16.368 ms/op
     p(99.9000) =     22.033 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 6.848 ±(99.9%) 0.221 ms/op
Iteration   1: 4.190 ±(99.9%) 0.077 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.912 ms/op
                 existUser·p0.90:   5.808 ms/op
                 existUser·p0.95:   8.213 ms/op
                 existUser·p0.99:   13.381 ms/op
                 existUser·p0.999:  17.524 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7642
  mean =      4.190 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 1026 
    [ 2.500,  3.750) = 1580 
    [ 3.750,  5.000) = 4042 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 132 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      8.213 ms/op
     p(99.0000) =     13.381 ms/op
     p(99.9000) =     17.524 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.022 ms/op
     p(99.9999) =     18.022 ms/op
    p(100.0000) =     18.022 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.450 ±(99.9%) 0.431 ms/op
Iteration   1: 4.801 ±(99.9%) 0.053 ms/op
                 getUser·p0.00:   1.372 ms/op
                 getUser·p0.50:   4.760 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.951 ms/op
                 getUser·p0.99:   12.304 ms/op
                 getUser·p0.999:  14.080 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   15.450 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 6649
  mean =      4.801 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 46 
    [ 2.500,  3.750) = 476 
    [ 3.750,  5.000) = 4758 
    [ 5.000,  6.250) = 1087 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.951 ms/op
     p(99.0000) =     12.304 ms/op
     p(99.9000) =     14.080 ms/op
     p(99.9900) =     15.450 ms/op
     p(99.9990) =     15.450 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 25.381 ±(99.9%) 0.949 ms/op
Iteration   1: 17.233 ±(99.9%) 0.286 ms/op
                 listUser·p0.00:   6.259 ms/op
                 listUser·p0.50:   17.269 ms/op
                 listUser·p0.90:   20.624 ms/op
                 listUser·p0.95:   23.921 ms/op
                 listUser·p0.99:   31.186 ms/op
                 listUser·p0.999:  43.507 ms/op
                 listUser·p0.9999: 44.368 ms/op
                 listUser·p1.00:   44.368 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1875
  mean =     17.233 ±(99.9%) 0.286 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 31 
    [10.000, 15.000) = 415 
    [15.000, 20.000) = 1220 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 15 
    [35.000, 40.000) = 3 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      6.259 ms/op
     p(50.0000) =     17.269 ms/op
     p(90.0000) =     20.624 ms/op
     p(95.0000) =     23.921 ms/op
     p(99.0000) =     31.186 ms/op
     p(99.9000) =     43.507 ms/op
     p(99.9900) =     44.368 ms/op
     p(99.9990) =     44.368 ms/op
     p(99.9999) =     44.368 ms/op
    p(100.0000) =     44.368 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         2.046          ops/ms
Client.existUser                       thrpt         6.107          ops/ms
Client.getUser                         thrpt         4.640          ops/ms
Client.listUser                        thrpt         1.355          ops/ms
Client.createUser                       avgt         7.534           ms/op
Client.existUser                        avgt         3.726           ms/op
Client.getUser                          avgt         5.111           ms/op
Client.listUser                         avgt        20.416           ms/op
Client.createUser                     sample  4603   6.984 ± 0.081   ms/op
Client.createUser:createUser·p0.00    sample         2.609           ms/op
Client.createUser:createUser·p0.50    sample         6.660           ms/op
Client.createUser:createUser·p0.90    sample         7.714           ms/op
Client.createUser:createUser·p0.95    sample         8.348           ms/op
Client.createUser:createUser·p0.99    sample        16.368           ms/op
Client.createUser:createUser·p0.999   sample        22.033           ms/op
Client.createUser:createUser·p0.9999  sample        22.118           ms/op
Client.createUser:createUser·p1.00    sample        22.118           ms/op
Client.existUser                      sample  7642   4.190 ± 0.077   ms/op
Client.existUser:existUser·p0.00      sample         1.141           ms/op
Client.existUser:existUser·p0.50      sample         3.912           ms/op
Client.existUser:existUser·p0.90      sample         5.808           ms/op
Client.existUser:existUser·p0.95      sample         8.213           ms/op
Client.existUser:existUser·p0.99      sample        13.381           ms/op
Client.existUser:existUser·p0.999     sample        17.524           ms/op
Client.existUser:existUser·p0.9999    sample        18.022           ms/op
Client.existUser:existUser·p1.00      sample        18.022           ms/op
Client.getUser                        sample  6649   4.801 ± 0.053   ms/op
Client.getUser:getUser·p0.00          sample         1.372           ms/op
Client.getUser:getUser·p0.50          sample         4.760           ms/op
Client.getUser:getUser·p0.90          sample         5.333           ms/op
Client.getUser:getUser·p0.95          sample         5.951           ms/op
Client.getUser:getUser·p0.99          sample        12.304           ms/op
Client.getUser:getUser·p0.999         sample        14.080           ms/op
Client.getUser:getUser·p0.9999        sample        15.450           ms/op
Client.getUser:getUser·p1.00          sample        15.450           ms/op
Client.listUser                       sample  1875  17.233 ± 0.286   ms/op
Client.listUser:listUser·p0.00        sample         6.259           ms/op
Client.listUser:listUser·p0.50        sample        17.269           ms/op
Client.listUser:listUser·p0.90        sample        20.624           ms/op
Client.listUser:listUser·p0.95        sample        23.921           ms/op
Client.listUser:listUser·p0.99        sample        31.186           ms/op
Client.listUser:listUser·p0.999       sample        43.507           ms/op
Client.listUser:listUser·p0.9999      sample        44.368           ms/op
Client.listUser:listUser·p1.00        sample        44.368           ms/op
