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
# Warmup Iteration   1: 1.999 ops/ms
Iteration   1: 5.794 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.794 ops/ms


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
# Warmup Iteration   1: 5.124 ops/ms
Iteration   1: 12.117 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.117 ops/ms


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
# Warmup Iteration   1: 3.861 ops/ms
Iteration   1: 8.957 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.957 ops/ms


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
# Warmup Iteration   1: 2.150 ops/ms
Iteration   1: 3.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.597 ops/ms


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
# Warmup Iteration   1: 5.140 ±(99.9%) 0.058 ms/op
Iteration   1: 3.150 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.150 ms/op


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
# Warmup Iteration   1: 3.207 ±(99.9%) 0.026 ms/op
Iteration   1: 2.026 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.026 ms/op


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
# Warmup Iteration   1: 4.928 ±(99.9%) 0.048 ms/op
Iteration   1: 3.113 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.113 ms/op


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
# Warmup Iteration   1: 12.233 ±(99.9%) 0.168 ms/op
Iteration   1: 7.671 ±(99.9%) 0.086 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.671 ms/op


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.117 ms/op
Iteration   1: 3.274 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   1.188 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   7.260 ms/op
                 createUser·p0.999:  17.168 ms/op
                 createUser·p0.9999: 19.300 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9770
  mean =      3.274 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 1263 
    [ 2.500,  3.750) = 6992 
    [ 3.750,  5.000) = 1206 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      4.002 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.260 ms/op
     p(99.9000) =     17.168 ms/op
     p(99.9900) =     19.300 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 3.017 ±(99.9%) 0.065 ms/op
Iteration   1: 1.889 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   1.735 ms/op
                 existUser·p0.90:   2.351 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  17.531 ms/op
                 existUser·p0.9999: 17.629 ms/op
                 existUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16924
  mean =      1.889 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 15746 
    [ 2.500,  3.750) = 991 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 20 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      1.735 ms/op
     p(90.0000) =      2.351 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.482 ms/op
     p(99.9000) =     17.531 ms/op
     p(99.9900) =     17.629 ms/op
     p(99.9990) =     17.629 ms/op
     p(99.9999) =     17.629 ms/op
    p(100.0000) =     17.629 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.105 ms/op
Iteration   1: 3.307 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.046 ms/op
                 getUser·p0.999:  6.056 ms/op
                 getUser·p0.9999: 7.438 ms/op
                 getUser·p1.00:   7.438 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9686
  mean =      3.307 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 6 
    [1.500, 2.000) = 55 
    [2.000, 2.500) = 859 
    [2.500, 3.000) = 2591 
    [3.000, 3.500) = 2478 
    [3.500, 4.000) = 2235 
    [4.000, 4.500) = 1123 
    [4.500, 5.000) = 230 
    [5.000, 5.500) = 74 
    [5.500, 6.000) = 24 
    [6.000, 6.500) = 7 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      6.056 ms/op
     p(99.9900) =      7.438 ms/op
     p(99.9990) =      7.438 ms/op
     p(99.9999) =      7.438 ms/op
    p(100.0000) =      7.438 ms/op


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
# Warmup Iteration   1: 11.777 ±(99.9%) 0.377 ms/op
Iteration   1: 8.051 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   2.511 ms/op
                 listUser·p0.50:   7.758 ms/op
                 listUser·p0.90:   10.371 ms/op
                 listUser·p0.95:   11.256 ms/op
                 listUser·p0.99:   16.286 ms/op
                 listUser·p0.999:  21.007 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4300
  mean =      8.051 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 112 
    [ 5.000,  7.500) = 1715 
    [ 7.500, 10.000) = 1925 
    [10.000, 12.500) = 419 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.511 ms/op
     p(50.0000) =      7.758 ms/op
     p(90.0000) =     10.371 ms/op
     p(95.0000) =     11.256 ms/op
     p(99.0000) =     16.286 ms/op
     p(99.9000) =     21.007 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     23.200 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.794          ops/ms
Client.existUser                       thrpt         12.117          ops/ms
Client.getUser                         thrpt          8.957          ops/ms
Client.listUser                        thrpt          3.597          ops/ms
Client.createUser                       avgt          3.150           ms/op
Client.existUser                        avgt          2.026           ms/op
Client.getUser                          avgt          3.113           ms/op
Client.listUser                         avgt          7.671           ms/op
Client.createUser                     sample   9770   3.274 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          1.188           ms/op
Client.createUser:createUser·p0.50    sample          3.105           ms/op
Client.createUser:createUser·p0.90    sample          4.002           ms/op
Client.createUser:createUser·p0.95    sample          4.432           ms/op
Client.createUser:createUser·p0.99    sample          7.260           ms/op
Client.createUser:createUser·p0.999   sample         17.168           ms/op
Client.createUser:createUser·p0.9999  sample         19.300           ms/op
Client.createUser:createUser·p1.00    sample         19.300           ms/op
Client.existUser                      sample  16924   1.889 ± 0.020   ms/op
Client.existUser:existUser·p0.00      sample          0.836           ms/op
Client.existUser:existUser·p0.50      sample          1.735           ms/op
Client.existUser:existUser·p0.90      sample          2.351           ms/op
Client.existUser:existUser·p0.95      sample          2.589           ms/op
Client.existUser:existUser·p0.99      sample          3.482           ms/op
Client.existUser:existUser·p0.999     sample         17.531           ms/op
Client.existUser:existUser·p0.9999    sample         17.629           ms/op
Client.existUser:existUser·p1.00      sample         17.629           ms/op
Client.getUser                        sample   9686   3.307 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          1.124           ms/op
Client.getUser:getUser·p0.50          sample          3.301           ms/op
Client.getUser:getUser·p0.90          sample          4.153           ms/op
Client.getUser:getUser·p0.95          sample          4.375           ms/op
Client.getUser:getUser·p0.99          sample          5.046           ms/op
Client.getUser:getUser·p0.999         sample          6.056           ms/op
Client.getUser:getUser·p0.9999        sample          7.438           ms/op
Client.getUser:getUser·p1.00          sample          7.438           ms/op
Client.listUser                       sample   4300   8.051 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          2.511           ms/op
Client.listUser:listUser·p0.50        sample          7.758           ms/op
Client.listUser:listUser·p0.90        sample         10.371           ms/op
Client.listUser:listUser·p0.95        sample         11.256           ms/op
Client.listUser:listUser·p0.99        sample         16.286           ms/op
Client.listUser:listUser·p0.999       sample         21.007           ms/op
Client.listUser:listUser·p0.9999      sample         23.200           ms/op
Client.listUser:listUser·p1.00        sample         23.200           ms/op
