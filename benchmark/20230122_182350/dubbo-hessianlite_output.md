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
# Warmup Iteration   1: 1.053 ops/ms
Iteration   1: 3.116 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.116 ops/ms


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
# Warmup Iteration   1: 3.367 ops/ms
Iteration   1: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  7.755 ops/ms


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
# Warmup Iteration   1: 2.127 ops/ms
Iteration   1: 4.373 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.373 ops/ms


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
# Warmup Iteration   1: 0.976 ops/ms
Iteration   1: 1.452 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.452 ops/ms


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
# Warmup Iteration   1: 15.710 ±(99.9%) 0.173 ms/op
Iteration   1: 6.785 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.785 ms/op


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
# Warmup Iteration   1: 6.353 ±(99.9%) 0.069 ms/op
Iteration   1: 3.259 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  3.259 ms/op


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
# Warmup Iteration   1: 8.955 ±(99.9%) 0.196 ms/op
Iteration   1: 5.098 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.098 ms/op


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
# Warmup Iteration   1: 31.715 ±(99.9%) 0.631 ms/op
Iteration   1: 18.852 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  18.852 ms/op


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
# Warmup Iteration   1: 10.875 ±(99.9%) 0.443 ms/op
Iteration   1: 5.481 ±(99.9%) 0.086 ms/op
                 createUser·p0.00:   2.298 ms/op
                 createUser·p0.50:   5.677 ms/op
                 createUser·p0.90:   6.283 ms/op
                 createUser·p0.95:   6.849 ms/op
                 createUser·p0.99:   15.391 ms/op
                 createUser·p0.999:  18.785 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 5864
  mean =      5.481 ±(99.9%) 0.086 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 2 
    [ 2.500,  3.750) = 936 
    [ 3.750,  5.000) = 1228 
    [ 5.000,  6.250) = 2966 
    [ 6.250,  7.500) = 457 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      5.677 ms/op
     p(90.0000) =      6.283 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =     15.391 ms/op
     p(99.9000) =     18.785 ms/op
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
# Warmup Iteration   1: 6.733 ±(99.9%) 0.176 ms/op
Iteration   1: 3.503 ±(99.9%) 0.067 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   3.977 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   13.681 ms/op
                 existUser·p0.999:  24.928 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 9129
  mean =      3.503 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1364 
    [ 2.500,  5.000) = 7387 
    [ 5.000,  7.500) = 186 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =     13.681 ms/op
     p(99.9000) =     24.928 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 8.064 ±(99.9%) 0.302 ms/op
Iteration   1: 4.474 ±(99.9%) 0.061 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   4.309 ms/op
                 getUser·p0.90:   5.300 ms/op
                 getUser·p0.95:   6.942 ms/op
                 getUser·p0.99:   11.739 ms/op
                 getUser·p0.999:  15.939 ms/op
                 getUser·p0.9999: 16.187 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 7282
  mean =      4.474 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 138 
    [ 2.500,  3.750) = 1748 
    [ 3.750,  5.000) = 4161 
    [ 5.000,  6.250) = 831 
    [ 6.250,  7.500) = 59 
    [ 7.500,  8.750) = 134 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.942 ms/op
     p(99.0000) =     11.739 ms/op
     p(99.9000) =     15.939 ms/op
     p(99.9900) =     16.187 ms/op
     p(99.9990) =     16.187 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 28.112 ±(99.9%) 0.884 ms/op
Iteration   1: 16.505 ±(99.9%) 0.333 ms/op
                 listUser·p0.00:   5.079 ms/op
                 listUser·p0.50:   15.942 ms/op
                 listUser·p0.90:   19.628 ms/op
                 listUser·p0.95:   27.083 ms/op
                 listUser·p0.99:   34.636 ms/op
                 listUser·p0.999:  41.104 ms/op
                 listUser·p0.9999: 45.089 ms/op
                 listUser·p1.00:   45.089 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1949
  mean =     16.505 ±(99.9%) 0.333 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 0 
    [ 5.000, 10.000) = 64 
    [10.000, 15.000) = 386 
    [15.000, 20.000) = 1336 
    [20.000, 25.000) = 54 
    [25.000, 30.000) = 38 
    [30.000, 35.000) = 65 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      5.079 ms/op
     p(50.0000) =     15.942 ms/op
     p(90.0000) =     19.628 ms/op
     p(95.0000) =     27.083 ms/op
     p(99.0000) =     34.636 ms/op
     p(99.9000) =     41.104 ms/op
     p(99.9900) =     45.089 ms/op
     p(99.9990) =     45.089 ms/op
     p(99.9999) =     45.089 ms/op
    p(100.0000) =     45.089 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         3.116          ops/ms
Client.existUser                       thrpt         7.755          ops/ms
Client.getUser                         thrpt         4.373          ops/ms
Client.listUser                        thrpt         1.452          ops/ms
Client.createUser                       avgt         6.785           ms/op
Client.existUser                        avgt         3.259           ms/op
Client.getUser                          avgt         5.098           ms/op
Client.listUser                         avgt        18.852           ms/op
Client.createUser                     sample  5864   5.481 ± 0.086   ms/op
Client.createUser:createUser·p0.00    sample         2.298           ms/op
Client.createUser:createUser·p0.50    sample         5.677           ms/op
Client.createUser:createUser·p0.90    sample         6.283           ms/op
Client.createUser:createUser·p0.95    sample         6.849           ms/op
Client.createUser:createUser·p0.99    sample        15.391           ms/op
Client.createUser:createUser·p0.999   sample        18.785           ms/op
Client.createUser:createUser·p0.9999  sample        19.071           ms/op
Client.createUser:createUser·p1.00    sample        19.071           ms/op
Client.existUser                      sample  9129   3.503 ± 0.067   ms/op
Client.existUser:existUser·p0.00      sample         0.798           ms/op
Client.existUser:existUser·p0.50      sample         3.449           ms/op
Client.existUser:existUser·p0.90      sample         3.977           ms/op
Client.existUser:existUser·p0.95      sample         4.514           ms/op
Client.existUser:existUser·p0.99      sample        13.681           ms/op
Client.existUser:existUser·p0.999     sample        24.928           ms/op
Client.existUser:existUser·p0.9999    sample        25.657           ms/op
Client.existUser:existUser·p1.00      sample        25.657           ms/op
Client.getUser                        sample  7282   4.474 ± 0.061   ms/op
Client.getUser:getUser·p0.00          sample         0.516           ms/op
Client.getUser:getUser·p0.50          sample         4.309           ms/op
Client.getUser:getUser·p0.90          sample         5.300           ms/op
Client.getUser:getUser·p0.95          sample         6.942           ms/op
Client.getUser:getUser·p0.99          sample        11.739           ms/op
Client.getUser:getUser·p0.999         sample        15.939           ms/op
Client.getUser:getUser·p0.9999        sample        16.187           ms/op
Client.getUser:getUser·p1.00          sample        16.187           ms/op
Client.listUser                       sample  1949  16.505 ± 0.333   ms/op
Client.listUser:listUser·p0.00        sample         5.079           ms/op
Client.listUser:listUser·p0.50        sample        15.942           ms/op
Client.listUser:listUser·p0.90        sample        19.628           ms/op
Client.listUser:listUser·p0.95        sample        27.083           ms/op
Client.listUser:listUser·p0.99        sample        34.636           ms/op
Client.listUser:listUser·p0.999       sample        41.104           ms/op
Client.listUser:listUser·p0.9999      sample        45.089           ms/op
Client.listUser:listUser·p1.00        sample        45.089           ms/op
