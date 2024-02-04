# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.091 ops/ms
Iteration   1: 5.911 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.911 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.293 ops/ms
Iteration   1: 10.976 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.976 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.231 ops/ms
Iteration   1: 7.579 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.579 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.675 ops/ms
Iteration   1: 3.672 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.672 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.477 ±(99.9%) 0.083 ms/op
Iteration   1: 3.409 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.409 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.039 ms/op
Iteration   1: 1.956 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 5.465 ±(99.9%) 0.102 ms/op
Iteration   1: 3.175 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.175 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.090 ±(99.9%) 0.269 ms/op
Iteration   1: 8.495 ±(99.9%) 0.099 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.495 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.192 ±(99.9%) 0.116 ms/op
Iteration   1: 3.111 ±(99.9%) 0.077 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   13.245 ms/op
                 createUser·p0.999:  35.455 ms/op
                 createUser·p0.9999: 38.404 ms/op
                 createUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10279
  mean =      3.111 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4009 
    [ 2.500,  5.000) = 5863 
    [ 5.000,  7.500) = 201 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =     13.245 ms/op
     p(99.9000) =     35.455 ms/op
     p(99.9900) =     38.404 ms/op
     p(99.9990) =     38.404 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ±(99.9%) 0.068 ms/op
Iteration   1: 2.186 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.101 ms/op
                 existUser·p0.90:   2.822 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  8.641 ms/op
                 existUser·p0.9999: 10.132 ms/op
                 existUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14622
  mean =      2.186 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 32 
    [ 1.000,  2.000) = 5959 
    [ 2.000,  3.000) = 7768 
    [ 3.000,  4.000) = 631 
    [ 4.000,  5.000) = 117 
    [ 5.000,  6.000) = 45 
    [ 6.000,  7.000) = 9 
    [ 7.000,  8.000) = 30 
    [ 8.000,  9.000) = 29 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.101 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      4.817 ms/op
     p(99.9000) =      8.641 ms/op
     p(99.9900) =     10.132 ms/op
     p(99.9990) =     10.715 ms/op
     p(99.9999) =     10.715 ms/op
    p(100.0000) =     10.715 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.733 ±(99.9%) 0.142 ms/op
Iteration   1: 3.039 ±(99.9%) 0.034 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.281 ms/op
                 getUser·p0.999:  16.403 ms/op
                 getUser·p0.9999: 16.725 ms/op
                 getUser·p1.00:   16.728 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10608
  mean =      3.039 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 3267 
    [ 2.500,  3.750) = 5440 
    [ 3.750,  5.000) = 1733 
    [ 5.000,  6.250) = 75 
    [ 6.250,  7.500) = 16 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.281 ms/op
     p(99.9000) =     16.403 ms/op
     p(99.9900) =     16.725 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     16.728 ms/op
    p(100.0000) =     16.728 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.644 ±(99.9%) 0.475 ms/op
Iteration   1: 9.365 ±(99.9%) 0.135 ms/op
                 listUser·p0.00:   2.392 ms/op
                 listUser·p0.50:   9.060 ms/op
                 listUser·p0.90:   12.157 ms/op
                 listUser·p0.95:   13.793 ms/op
                 listUser·p0.99:   17.433 ms/op
                 listUser·p0.999:  20.617 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3402
  mean =      9.365 ±(99.9%) 0.135 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 35 
    [ 5.000,  7.500) = 670 
    [ 7.500, 10.000) = 1561 
    [10.000, 12.500) = 869 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      9.060 ms/op
     p(90.0000) =     12.157 ms/op
     p(95.0000) =     13.793 ms/op
     p(99.0000) =     17.433 ms/op
     p(99.9000) =     20.617 ms/op
     p(99.9900) =     25.100 ms/op
     p(99.9990) =     25.100 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.911          ops/ms
Client.existUser                       thrpt         10.976          ops/ms
Client.getUser                         thrpt          7.579          ops/ms
Client.listUser                        thrpt          3.672          ops/ms
Client.createUser                       avgt          3.409           ms/op
Client.existUser                        avgt          1.956           ms/op
Client.getUser                          avgt          3.175           ms/op
Client.listUser                         avgt          8.495           ms/op
Client.createUser                     sample  10279   3.111 ± 0.077   ms/op
Client.createUser:createUser·p0.00    sample          0.864           ms/op
Client.createUser:createUser·p0.50    sample          2.638           ms/op
Client.createUser:createUser·p0.90    sample          3.850           ms/op
Client.createUser:createUser·p0.95    sample          4.579           ms/op
Client.createUser:createUser·p0.99    sample         13.245           ms/op
Client.createUser:createUser·p0.999   sample         35.455           ms/op
Client.createUser:createUser·p0.9999  sample         38.404           ms/op
Client.createUser:createUser·p1.00    sample         38.404           ms/op
Client.existUser                      sample  14622   2.186 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.748           ms/op
Client.existUser:existUser·p0.50      sample          2.101           ms/op
Client.existUser:existUser·p0.90      sample          2.822           ms/op
Client.existUser:existUser·p0.95      sample          3.047           ms/op
Client.existUser:existUser·p0.99      sample          4.817           ms/op
Client.existUser:existUser·p0.999     sample          8.641           ms/op
Client.existUser:existUser·p0.9999    sample         10.132           ms/op
Client.existUser:existUser·p1.00      sample         10.715           ms/op
Client.getUser                        sample  10608   3.039 ± 0.034   ms/op
Client.getUser:getUser·p0.00          sample          0.847           ms/op
Client.getUser:getUser·p0.50          sample          2.920           ms/op
Client.getUser:getUser·p0.90          sample          3.969           ms/op
Client.getUser:getUser·p0.95          sample          4.325           ms/op
Client.getUser:getUser·p0.99          sample          5.281           ms/op
Client.getUser:getUser·p0.999         sample         16.403           ms/op
Client.getUser:getUser·p0.9999        sample         16.725           ms/op
Client.getUser:getUser·p1.00          sample         16.728           ms/op
Client.listUser                       sample   3402   9.365 ± 0.135   ms/op
Client.listUser:listUser·p0.00        sample          2.392           ms/op
Client.listUser:listUser·p0.50        sample          9.060           ms/op
Client.listUser:listUser·p0.90        sample         12.157           ms/op
Client.listUser:listUser·p0.95        sample         13.793           ms/op
Client.listUser:listUser·p0.99        sample         17.433           ms/op
Client.listUser:listUser·p0.999       sample         20.617           ms/op
Client.listUser:listUser·p0.9999      sample         25.100           ms/op
Client.listUser:listUser·p1.00        sample         25.100           ms/op
