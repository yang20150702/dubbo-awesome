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
# Warmup Iteration   1: 2.438 ops/ms
Iteration   1: 5.369 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.369 ops/ms


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
# Warmup Iteration   1: 6.424 ops/ms
Iteration   1: 12.441 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.441 ops/ms


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
# Warmup Iteration   1: 4.132 ops/ms
Iteration   1: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.597 ops/ms


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
# Warmup Iteration   1: 1.837 ops/ms
Iteration   1: 2.916 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.916 ops/ms


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
# Warmup Iteration   1: 5.455 ±(99.9%) 0.089 ms/op
Iteration   1: 3.075 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.075 ms/op


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
# Warmup Iteration   1: 3.335 ±(99.9%) 0.038 ms/op
Iteration   1: 1.990 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.990 ms/op


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
# Warmup Iteration   1: 4.831 ±(99.9%) 0.061 ms/op
Iteration   1: 3.183 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.183 ms/op


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
# Warmup Iteration   1: 12.300 ±(99.9%) 0.279 ms/op
Iteration   1: 8.680 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.680 ms/op


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
# Warmup Iteration   1: 5.045 ±(99.9%) 0.114 ms/op
Iteration   1: 3.076 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   6.588 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 14.379 ms/op
                 createUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10380
  mean =      3.076 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1900 
    [ 2.500,  3.750) = 7289 
    [ 3.750,  5.000) = 1010 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      6.588 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     14.379 ms/op
     p(99.9990) =     14.402 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 3.190 ±(99.9%) 0.073 ms/op
Iteration   1: 1.780 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   1.669 ms/op
                 existUser·p0.90:   2.281 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.386 ms/op
                 existUser·p0.999:  5.489 ms/op
                 existUser·p0.9999: 6.788 ms/op
                 existUser·p1.00:   7.160 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17964
  mean =      1.780 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 104 
    [1.000, 1.500) = 3692 
    [1.500, 2.000) = 10141 
    [2.000, 2.500) = 3190 
    [2.500, 3.000) = 563 
    [3.000, 3.500) = 106 
    [3.500, 4.000) = 67 
    [4.000, 4.500) = 21 
    [4.500, 5.000) = 18 
    [5.000, 5.500) = 46 
    [5.500, 6.000) = 9 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      1.669 ms/op
     p(90.0000) =      2.281 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.386 ms/op
     p(99.9000) =      5.489 ms/op
     p(99.9900) =      6.788 ms/op
     p(99.9990) =      7.160 ms/op
     p(99.9999) =      7.160 ms/op
    p(100.0000) =      7.160 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.096 ms/op
Iteration   1: 3.030 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.904 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   5.500 ms/op
                 getUser·p0.999:  6.562 ms/op
                 getUser·p0.9999: 8.673 ms/op
                 getUser·p1.00:   8.749 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10561
  mean =      3.030 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 8 
    [1.500, 2.000) = 124 
    [2.000, 2.500) = 1869 
    [2.500, 3.000) = 3861 
    [3.000, 3.500) = 2610 
    [3.500, 4.000) = 1431 
    [4.000, 4.500) = 332 
    [4.500, 5.000) = 161 
    [5.000, 5.500) = 58 
    [5.500, 6.000) = 56 
    [6.000, 6.500) = 24 
    [6.500, 7.000) = 21 
    [7.000, 7.500) = 3 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.920 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.500 ms/op
     p(99.9000) =      6.562 ms/op
     p(99.9900) =      8.673 ms/op
     p(99.9990) =      8.749 ms/op
     p(99.9999) =      8.749 ms/op
    p(100.0000) =      8.749 ms/op


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
# Warmup Iteration   1: 12.777 ±(99.9%) 0.435 ms/op
Iteration   1: 8.851 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   3.224 ms/op
                 listUser·p0.50:   8.569 ms/op
                 listUser·p0.90:   11.452 ms/op
                 listUser·p0.95:   12.392 ms/op
                 listUser·p0.99:   16.426 ms/op
                 listUser·p0.999:  21.388 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3672
  mean =      8.851 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 59 
    [ 5.000,  7.500) = 881 
    [ 7.500, 10.000) = 1837 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.224 ms/op
     p(50.0000) =      8.569 ms/op
     p(90.0000) =     11.452 ms/op
     p(95.0000) =     12.392 ms/op
     p(99.0000) =     16.426 ms/op
     p(99.9000) =     21.388 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.369          ops/ms
Client.existUser                       thrpt         12.441          ops/ms
Client.getUser                         thrpt          8.597          ops/ms
Client.listUser                        thrpt          2.916          ops/ms
Client.createUser                       avgt          3.075           ms/op
Client.existUser                        avgt          1.990           ms/op
Client.getUser                          avgt          3.183           ms/op
Client.listUser                         avgt          8.680           ms/op
Client.createUser                     sample  10380   3.076 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.116           ms/op
Client.createUser:createUser·p0.50    sample          2.920           ms/op
Client.createUser:createUser·p0.90    sample          3.805           ms/op
Client.createUser:createUser·p0.95    sample          4.125           ms/op
Client.createUser:createUser·p0.99    sample          6.588           ms/op
Client.createUser:createUser·p0.999   sample         11.239           ms/op
Client.createUser:createUser·p0.9999  sample         14.379           ms/op
Client.createUser:createUser·p1.00    sample         14.402           ms/op
Client.existUser                      sample  17964   1.780 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.523           ms/op
Client.existUser:existUser·p0.50      sample          1.669           ms/op
Client.existUser:existUser·p0.90      sample          2.281           ms/op
Client.existUser:existUser·p0.95      sample          2.478           ms/op
Client.existUser:existUser·p0.99      sample          3.386           ms/op
Client.existUser:existUser·p0.999     sample          5.489           ms/op
Client.existUser:existUser·p0.9999    sample          6.788           ms/op
Client.existUser:existUser·p1.00      sample          7.160           ms/op
Client.getUser                        sample  10561   3.030 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.920           ms/op
Client.getUser:getUser·p0.50          sample          2.904           ms/op
Client.getUser:getUser·p0.90          sample          3.777           ms/op
Client.getUser:getUser·p0.95          sample          4.088           ms/op
Client.getUser:getUser·p0.99          sample          5.500           ms/op
Client.getUser:getUser·p0.999         sample          6.562           ms/op
Client.getUser:getUser·p0.9999        sample          8.673           ms/op
Client.getUser:getUser·p1.00          sample          8.749           ms/op
Client.listUser                       sample   3672   8.851 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          3.224           ms/op
Client.listUser:listUser·p0.50        sample          8.569           ms/op
Client.listUser:listUser·p0.90        sample         11.452           ms/op
Client.listUser:listUser·p0.95        sample         12.392           ms/op
Client.listUser:listUser·p0.99        sample         16.426           ms/op
Client.listUser:listUser·p0.999       sample         21.388           ms/op
Client.listUser:listUser·p0.9999      sample         23.003           ms/op
Client.listUser:listUser·p1.00        sample         23.003           ms/op
