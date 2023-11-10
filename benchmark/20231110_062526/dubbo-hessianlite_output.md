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
# Warmup Iteration   1: 2.484 ops/ms
Iteration   1: 6.012 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.012 ops/ms


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
# Warmup Iteration   1: 7.274 ops/ms
Iteration   1: 12.355 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.355 ops/ms


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
# Warmup Iteration   1: 5.254 ops/ms
Iteration   1: 8.578 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.578 ops/ms


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
# Warmup Iteration   1: 2.039 ops/ms
Iteration   1: 3.419 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.419 ops/ms


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
# Warmup Iteration   1: 4.987 ±(99.9%) 0.072 ms/op
Iteration   1: 3.084 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.084 ms/op


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
# Warmup Iteration   1: 3.282 ±(99.9%) 0.035 ms/op
Iteration   1: 1.901 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.901 ms/op


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.052 ms/op
Iteration   1: 3.388 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.388 ms/op


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
# Warmup Iteration   1: 12.213 ±(99.9%) 0.178 ms/op
Iteration   1: 8.164 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.164 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.082 ms/op
Iteration   1: 3.020 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   2.720 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   6.022 ms/op
                 createUser·p0.999:  16.819 ms/op
                 createUser·p0.9999: 17.037 ms/op
                 createUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10576
  mean =      3.020 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1523 
    [ 2.500,  3.750) = 7721 
    [ 3.750,  5.000) = 1168 
    [ 5.000,  6.250) = 63 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      2.720 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      6.022 ms/op
     p(99.9000) =     16.819 ms/op
     p(99.9900) =     17.037 ms/op
     p(99.9990) =     17.039 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 2.923 ±(99.9%) 0.071 ms/op
Iteration   1: 1.839 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.302 ms/op
                 existUser·p0.99:   3.293 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 15.205 ms/op
                 existUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17382
  mean =      1.839 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 492 
    [ 1.250,  2.500) = 16405 
    [ 2.500,  3.750) = 366 
    [ 3.750,  5.000) = 22 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.302 ms/op
     p(99.0000) =      3.293 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     15.205 ms/op
     p(99.9990) =     16.040 ms/op
     p(99.9999) =     16.040 ms/op
    p(100.0000) =     16.040 ms/op


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.097 ms/op
Iteration   1: 2.955 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   2.871 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   4.158 ms/op
                 getUser·p0.99:   5.119 ms/op
                 getUser·p0.999:  12.419 ms/op
                 getUser·p0.9999: 12.613 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10858
  mean =      2.955 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 3110 
    [ 2.500,  3.750) = 6562 
    [ 3.750,  5.000) = 1027 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.158 ms/op
     p(99.0000) =      5.119 ms/op
     p(99.9000) =     12.419 ms/op
     p(99.9900) =     12.613 ms/op
     p(99.9990) =     12.616 ms/op
     p(99.9999) =     12.616 ms/op
    p(100.0000) =     12.616 ms/op


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
# Warmup Iteration   1: 12.715 ±(99.9%) 0.422 ms/op
Iteration   1: 8.510 ±(99.9%) 0.136 ms/op
                 listUser·p0.00:   3.060 ms/op
                 listUser·p0.50:   8.028 ms/op
                 listUser·p0.90:   11.665 ms/op
                 listUser·p0.95:   12.665 ms/op
                 listUser·p0.99:   17.142 ms/op
                 listUser·p0.999:  21.531 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.101 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3742
  mean =      8.510 ±(99.9%) 0.136 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 115 
    [ 5.000,  7.500) = 1370 
    [ 7.500, 10.000) = 1318 
    [10.000, 12.500) = 714 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.060 ms/op
     p(50.0000) =      8.028 ms/op
     p(90.0000) =     11.665 ms/op
     p(95.0000) =     12.665 ms/op
     p(99.0000) =     17.142 ms/op
     p(99.9000) =     21.531 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.101 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.012          ops/ms
Client.existUser                       thrpt         12.355          ops/ms
Client.getUser                         thrpt          8.578          ops/ms
Client.listUser                        thrpt          3.419          ops/ms
Client.createUser                       avgt          3.084           ms/op
Client.existUser                        avgt          1.901           ms/op
Client.getUser                          avgt          3.388           ms/op
Client.listUser                         avgt          8.164           ms/op
Client.createUser                     sample  10576   3.020 ± 0.037   ms/op
Client.createUser:createUser·p0.00    sample          1.341           ms/op
Client.createUser:createUser·p0.50    sample          2.720           ms/op
Client.createUser:createUser·p0.90    sample          3.867           ms/op
Client.createUser:createUser·p0.95    sample          4.100           ms/op
Client.createUser:createUser·p0.99    sample          6.022           ms/op
Client.createUser:createUser·p0.999   sample         16.819           ms/op
Client.createUser:createUser·p0.9999  sample         17.037           ms/op
Client.createUser:createUser·p1.00    sample         17.039           ms/op
Client.existUser                      sample  17382   1.839 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.744           ms/op
Client.existUser:existUser·p0.50      sample          1.741           ms/op
Client.existUser:existUser·p0.90      sample          2.154           ms/op
Client.existUser:existUser·p0.95      sample          2.302           ms/op
Client.existUser:existUser·p0.99      sample          3.293           ms/op
Client.existUser:existUser·p0.999     sample         14.107           ms/op
Client.existUser:existUser·p0.9999    sample         15.205           ms/op
Client.existUser:existUser·p1.00      sample         16.040           ms/op
Client.getUser                        sample  10858   2.955 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.751           ms/op
Client.getUser:getUser·p0.50          sample          2.871           ms/op
Client.getUser:getUser·p0.90          sample          3.785           ms/op
Client.getUser:getUser·p0.95          sample          4.158           ms/op
Client.getUser:getUser·p0.99          sample          5.119           ms/op
Client.getUser:getUser·p0.999         sample         12.419           ms/op
Client.getUser:getUser·p0.9999        sample         12.613           ms/op
Client.getUser:getUser·p1.00          sample         12.616           ms/op
Client.listUser                       sample   3742   8.510 ± 0.136   ms/op
Client.listUser:listUser·p0.00        sample          3.060           ms/op
Client.listUser:listUser·p0.50        sample          8.028           ms/op
Client.listUser:listUser·p0.90        sample         11.665           ms/op
Client.listUser:listUser·p0.95        sample         12.665           ms/op
Client.listUser:listUser·p0.99        sample         17.142           ms/op
Client.listUser:listUser·p0.999       sample         21.531           ms/op
Client.listUser:listUser·p0.9999      sample         23.101           ms/op
Client.listUser:listUser·p1.00        sample         23.101           ms/op
