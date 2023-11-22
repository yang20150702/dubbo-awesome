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
# Warmup Iteration   1: 2.297 ops/ms
Iteration   1: 6.080 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.080 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.123 ops/ms
Iteration   1: 13.721 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.721 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.535 ops/ms
Iteration   1: 8.511 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.511 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.009 ops/ms
Iteration   1: 3.560 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.560 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.793 ±(99.9%) 0.075 ms/op
Iteration   1: 2.841 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.841 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.537 ±(99.9%) 0.032 ms/op
Iteration   1: 2.065 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.065 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.376 ±(99.9%) 0.057 ms/op
Iteration   1: 3.026 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.026 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.801 ±(99.9%) 0.185 ms/op
Iteration   1: 7.885 ±(99.9%) 0.087 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.885 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ±(99.9%) 0.091 ms/op
Iteration   1: 3.443 ±(99.9%) 0.040 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   6.154 ms/op
                 createUser·p0.999:  17.686 ms/op
                 createUser·p0.9999: 17.793 ms/op
                 createUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9276
  mean =      3.443 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 606 
    [ 2.500,  3.750) = 6661 
    [ 3.750,  5.000) = 1677 
    [ 5.000,  6.250) = 247 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.154 ms/op
     p(99.9000) =     17.686 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     17.793 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.976 ±(99.9%) 0.068 ms/op
Iteration   1: 1.889 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.706 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.294 ms/op
                 existUser·p0.95:   2.466 ms/op
                 existUser·p0.99:   5.332 ms/op
                 existUser·p0.999:  13.374 ms/op
                 existUser·p0.9999: 14.032 ms/op
                 existUser·p1.00:   14.123 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16912
  mean =      1.889 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 377 
    [ 1.250,  2.500) = 15799 
    [ 2.500,  3.750) = 477 
    [ 3.750,  5.000) = 54 
    [ 5.000,  6.250) = 84 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.294 ms/op
     p(95.0000) =      2.466 ms/op
     p(99.0000) =      5.332 ms/op
     p(99.9000) =     13.374 ms/op
     p(99.9900) =     14.032 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.498 ±(99.9%) 0.116 ms/op
Iteration   1: 2.997 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.810 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.165 ms/op
                 getUser·p0.999:  14.942 ms/op
                 getUser·p0.9999: 17.439 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10680
  mean =      2.997 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 3225 
    [ 2.500,  3.750) = 6459 
    [ 3.750,  5.000) = 791 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      6.165 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     17.439 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.291 ±(99.9%) 0.393 ms/op
Iteration   1: 8.352 ±(99.9%) 0.129 ms/op
                 listUser·p0.00:   1.538 ms/op
                 listUser·p0.50:   7.930 ms/op
                 listUser·p0.90:   11.462 ms/op
                 listUser·p0.95:   12.686 ms/op
                 listUser·p0.99:   16.504 ms/op
                 listUser·p0.999:  18.944 ms/op
                 listUser·p0.9999: 32.702 ms/op
                 listUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3833
  mean =      8.352 ±(99.9%) 0.129 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 148 
    [ 5.000,  7.500) = 1455 
    [ 7.500, 10.000) = 1403 
    [10.000, 12.500) = 609 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      7.930 ms/op
     p(90.0000) =     11.462 ms/op
     p(95.0000) =     12.686 ms/op
     p(99.0000) =     16.504 ms/op
     p(99.9000) =     18.944 ms/op
     p(99.9900) =     32.702 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.080          ops/ms
Client.existUser                       thrpt         13.721          ops/ms
Client.getUser                         thrpt          8.511          ops/ms
Client.listUser                        thrpt          3.560          ops/ms
Client.createUser                       avgt          2.841           ms/op
Client.existUser                        avgt          2.065           ms/op
Client.getUser                          avgt          3.026           ms/op
Client.listUser                         avgt          7.885           ms/op
Client.createUser                     sample   9276   3.443 ± 0.040   ms/op
Client.createUser:createUser·p0.00    sample          1.116           ms/op
Client.createUser:createUser·p0.50    sample          3.297           ms/op
Client.createUser:createUser·p0.90    sample          4.252           ms/op
Client.createUser:createUser·p0.95    sample          4.669           ms/op
Client.createUser:createUser·p0.99    sample          6.154           ms/op
Client.createUser:createUser·p0.999   sample         17.686           ms/op
Client.createUser:createUser·p0.9999  sample         17.793           ms/op
Client.createUser:createUser·p1.00    sample         17.793           ms/op
Client.existUser                      sample  16912   1.889 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.706           ms/op
Client.existUser:existUser·p0.50      sample          1.765           ms/op
Client.existUser:existUser·p0.90      sample          2.294           ms/op
Client.existUser:existUser·p0.95      sample          2.466           ms/op
Client.existUser:existUser·p0.99      sample          5.332           ms/op
Client.existUser:existUser·p0.999     sample         13.374           ms/op
Client.existUser:existUser·p0.9999    sample         14.032           ms/op
Client.existUser:existUser·p1.00      sample         14.123           ms/op
Client.getUser                        sample  10680   2.997 ± 0.037   ms/op
Client.getUser:getUser·p0.00          sample          0.864           ms/op
Client.getUser:getUser·p0.50          sample          2.810           ms/op
Client.getUser:getUser·p0.90          sample          3.711           ms/op
Client.getUser:getUser·p0.95          sample          4.002           ms/op
Client.getUser:getUser·p0.99          sample          6.165           ms/op
Client.getUser:getUser·p0.999         sample         14.942           ms/op
Client.getUser:getUser·p0.9999        sample         17.439           ms/op
Client.getUser:getUser·p1.00          sample         17.498           ms/op
Client.listUser                       sample   3833   8.352 ± 0.129   ms/op
Client.listUser:listUser·p0.00        sample          1.538           ms/op
Client.listUser:listUser·p0.50        sample          7.930           ms/op
Client.listUser:listUser·p0.90        sample         11.462           ms/op
Client.listUser:listUser·p0.95        sample         12.686           ms/op
Client.listUser:listUser·p0.99        sample         16.504           ms/op
Client.listUser:listUser·p0.999       sample         18.944           ms/op
Client.listUser:listUser·p0.9999      sample         32.702           ms/op
Client.listUser:listUser·p1.00        sample         32.702           ms/op
