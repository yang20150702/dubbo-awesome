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
# Warmup Iteration   1: 2.310 ops/ms
Iteration   1: 5.716 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.716 ops/ms


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
# Warmup Iteration   1: 6.533 ops/ms
Iteration   1: 12.995 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.995 ops/ms


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
# Warmup Iteration   1: 4.743 ops/ms
Iteration   1: 9.839 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.839 ops/ms


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
# Warmup Iteration   1: 2.553 ops/ms
Iteration   1: 3.991 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.991 ops/ms


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
# Warmup Iteration   1: 5.536 ±(99.9%) 0.080 ms/op
Iteration   1: 3.232 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.232 ms/op


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
# Warmup Iteration   1: 3.283 ±(99.9%) 0.043 ms/op
Iteration   1: 1.861 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.083 ms/op
Iteration   1: 2.830 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.830 ms/op


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
# Warmup Iteration   1: 12.317 ±(99.9%) 0.192 ms/op
Iteration   1: 8.576 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.576 ms/op


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
# Warmup Iteration   1: 5.963 ±(99.9%) 0.144 ms/op
Iteration   1: 3.219 ±(99.9%) 0.068 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.814 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   12.566 ms/op
                 createUser·p0.999:  29.037 ms/op
                 createUser·p0.9999: 29.491 ms/op
                 createUser·p1.00:   29.491 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9937
  mean =      3.219 ±(99.9%) 0.068 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2094 
    [ 2.500,  5.000) = 7462 
    [ 5.000,  7.500) = 142 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =     12.566 ms/op
     p(99.9000) =     29.037 ms/op
     p(99.9900) =     29.491 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 3.250 ±(99.9%) 0.077 ms/op
Iteration   1: 1.996 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.913 ms/op
                 existUser·p0.90:   2.318 ms/op
                 existUser·p0.95:   2.552 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  16.646 ms/op
                 existUser·p0.9999: 16.954 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16008
  mean =      1.996 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 260 
    [ 1.250,  2.500) = 14829 
    [ 2.500,  3.750) = 685 
    [ 3.750,  5.000) = 104 
    [ 5.000,  6.250) = 95 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.913 ms/op
     p(90.0000) =      2.318 ms/op
     p(95.0000) =      2.552 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =     16.646 ms/op
     p(99.9900) =     16.954 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.101 ms/op
Iteration   1: 3.136 ±(99.9%) 0.051 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.939 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   7.905 ms/op
                 getUser·p0.999:  25.067 ms/op
                 getUser·p0.9999: 25.951 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10142
  mean =      3.136 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2537 
    [ 2.500,  5.000) = 7402 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.939 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     25.067 ms/op
     p(99.9900) =     25.951 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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
# Warmup Iteration   1: 12.134 ±(99.9%) 0.419 ms/op
Iteration   1: 8.956 ±(99.9%) 0.180 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   8.389 ms/op
                 listUser·p0.90:   12.567 ms/op
                 listUser·p0.95:   14.107 ms/op
                 listUser·p0.99:   20.699 ms/op
                 listUser·p0.999:  31.398 ms/op
                 listUser·p0.9999: 34.734 ms/op
                 listUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3563
  mean =      8.956 ±(99.9%) 0.180 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 134 
    [ 5.000,  7.500) = 1027 
    [ 7.500, 10.000) = 1523 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 2 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.388 ms/op
     p(50.0000) =      8.389 ms/op
     p(90.0000) =     12.567 ms/op
     p(95.0000) =     14.107 ms/op
     p(99.0000) =     20.699 ms/op
     p(99.9000) =     31.398 ms/op
     p(99.9900) =     34.734 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.716          ops/ms
Client.existUser                       thrpt         12.995          ops/ms
Client.getUser                         thrpt          9.839          ops/ms
Client.listUser                        thrpt          3.991          ops/ms
Client.createUser                       avgt          3.232           ms/op
Client.existUser                        avgt          1.861           ms/op
Client.getUser                          avgt          2.830           ms/op
Client.listUser                         avgt          8.576           ms/op
Client.createUser                     sample   9937   3.219 ± 0.068   ms/op
Client.createUser:createUser·p0.00    sample          0.976           ms/op
Client.createUser:createUser·p0.50    sample          2.814           ms/op
Client.createUser:createUser·p0.90    sample          4.043           ms/op
Client.createUser:createUser·p0.95    sample          4.522           ms/op
Client.createUser:createUser·p0.99    sample         12.566           ms/op
Client.createUser:createUser·p0.999   sample         29.037           ms/op
Client.createUser:createUser·p0.9999  sample         29.491           ms/op
Client.createUser:createUser·p1.00    sample         29.491           ms/op
Client.existUser                      sample  16008   1.996 ± 0.021   ms/op
Client.existUser:existUser·p0.00      sample          0.616           ms/op
Client.existUser:existUser·p0.50      sample          1.913           ms/op
Client.existUser:existUser·p0.90      sample          2.318           ms/op
Client.existUser:existUser·p0.95      sample          2.552           ms/op
Client.existUser:existUser·p0.99      sample          4.112           ms/op
Client.existUser:existUser·p0.999     sample         16.646           ms/op
Client.existUser:existUser·p0.9999    sample         16.954           ms/op
Client.existUser:existUser·p1.00      sample         16.974           ms/op
Client.getUser                        sample  10142   3.136 ± 0.051   ms/op
Client.getUser:getUser·p0.00          sample          0.586           ms/op
Client.getUser:getUser·p0.50          sample          2.986           ms/op
Client.getUser:getUser·p0.90          sample          3.939           ms/op
Client.getUser:getUser·p0.95          sample          4.211           ms/op
Client.getUser:getUser·p0.99          sample          7.905           ms/op
Client.getUser:getUser·p0.999         sample         25.067           ms/op
Client.getUser:getUser·p0.9999        sample         25.951           ms/op
Client.getUser:getUser·p1.00          sample         25.952           ms/op
Client.listUser                       sample   3563   8.956 ± 0.180   ms/op
Client.listUser:listUser·p0.00        sample          2.388           ms/op
Client.listUser:listUser·p0.50        sample          8.389           ms/op
Client.listUser:listUser·p0.90        sample         12.567           ms/op
Client.listUser:listUser·p0.95        sample         14.107           ms/op
Client.listUser:listUser·p0.99        sample         20.699           ms/op
Client.listUser:listUser·p0.999       sample         31.398           ms/op
Client.listUser:listUser·p0.9999      sample         34.734           ms/op
Client.listUser:listUser·p1.00        sample         34.734           ms/op
