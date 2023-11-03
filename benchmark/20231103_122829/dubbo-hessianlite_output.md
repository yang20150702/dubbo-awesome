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
# Warmup Iteration   1: 2.586 ops/ms
Iteration   1: 6.214 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.214 ops/ms


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
# Warmup Iteration   1: 6.347 ops/ms
Iteration   1: 13.378 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.378 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.487 ops/ms
Iteration   1: 9.217 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.217 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.317 ops/ms
Iteration   1: 4.084 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  4.084 ops/ms


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
# Warmup Iteration   1: 5.932 ±(99.9%) 0.079 ms/op
Iteration   1: 3.074 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.074 ms/op


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
# Warmup Iteration   1: 3.155 ±(99.9%) 0.037 ms/op
Iteration   1: 1.705 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.705 ms/op


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
# Warmup Iteration   1: 4.616 ±(99.9%) 0.067 ms/op
Iteration   1: 3.123 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.123 ms/op


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
# Warmup Iteration   1: 11.607 ±(99.9%) 0.242 ms/op
Iteration   1: 8.317 ±(99.9%) 0.112 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.317 ms/op


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.088 ms/op
Iteration   1: 3.111 ±(99.9%) 0.042 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.025 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   8.872 ms/op
                 createUser·p0.999:  14.942 ms/op
                 createUser·p0.9999: 15.138 ms/op
                 createUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10248
  mean =      3.111 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2177 
    [ 2.500,  3.750) = 7025 
    [ 3.750,  5.000) = 719 
    [ 5.000,  6.250) = 110 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.025 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      8.872 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     15.138 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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
# Warmup Iteration   1: 2.930 ±(99.9%) 0.057 ms/op
Iteration   1: 2.021 ±(99.9%) 0.032 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   1.898 ms/op
                 existUser·p0.90:   2.367 ms/op
                 existUser·p0.95:   2.544 ms/op
                 existUser·p0.99:   4.537 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 20.838 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15823
  mean =      2.021 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14906 
    [ 2.500,  5.000) = 760 
    [ 5.000,  7.500) = 27 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.898 ms/op
     p(90.0000) =      2.367 ms/op
     p(95.0000) =      2.544 ms/op
     p(99.0000) =      4.537 ms/op
     p(99.9000) =     20.120 ms/op
     p(99.9900) =     20.838 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.091 ms/op
Iteration   1: 2.900 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   2.855 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  12.165 ms/op
                 getUser·p0.9999: 12.725 ms/op
                 getUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11043
  mean =      2.900 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 3731 
    [ 2.500,  3.750) = 6230 
    [ 3.750,  5.000) = 893 
    [ 5.000,  6.250) = 144 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     12.165 ms/op
     p(99.9900) =     12.725 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


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
# Warmup Iteration   1: 11.327 ±(99.9%) 0.385 ms/op
Iteration   1: 8.566 ±(99.9%) 0.118 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   8.421 ms/op
                 listUser·p0.90:   11.248 ms/op
                 listUser·p0.95:   12.292 ms/op
                 listUser·p0.99:   15.634 ms/op
                 listUser·p0.999:  18.739 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3734
  mean =      8.566 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1 
    [ 2.500,  3.750) = 12 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 809 
    [ 7.500,  8.750) = 819 
    [ 8.750, 10.000) = 869 
    [10.000, 11.250) = 410 
    [11.250, 12.500) = 203 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.363 ms/op
     p(50.0000) =      8.421 ms/op
     p(90.0000) =     11.248 ms/op
     p(95.0000) =     12.292 ms/op
     p(99.0000) =     15.634 ms/op
     p(99.9000) =     18.739 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.214          ops/ms
Client.existUser                       thrpt         13.378          ops/ms
Client.getUser                         thrpt          9.217          ops/ms
Client.listUser                        thrpt          4.084          ops/ms
Client.createUser                       avgt          3.074           ms/op
Client.existUser                        avgt          1.705           ms/op
Client.getUser                          avgt          3.123           ms/op
Client.listUser                         avgt          8.317           ms/op
Client.createUser                     sample  10248   3.111 ± 0.042   ms/op
Client.createUser:createUser·p0.00    sample          0.794           ms/op
Client.createUser:createUser·p0.50    sample          3.025           ms/op
Client.createUser:createUser·p0.90    sample          3.752           ms/op
Client.createUser:createUser·p0.95    sample          4.399           ms/op
Client.createUser:createUser·p0.99    sample          8.872           ms/op
Client.createUser:createUser·p0.999   sample         14.942           ms/op
Client.createUser:createUser·p0.9999  sample         15.138           ms/op
Client.createUser:createUser·p1.00    sample         15.139           ms/op
Client.existUser                      sample  15823   2.021 ± 0.032   ms/op
Client.existUser:existUser·p0.00      sample          0.616           ms/op
Client.existUser:existUser·p0.50      sample          1.898           ms/op
Client.existUser:existUser·p0.90      sample          2.367           ms/op
Client.existUser:existUser·p0.95      sample          2.544           ms/op
Client.existUser:existUser·p0.99      sample          4.537           ms/op
Client.existUser:existUser·p0.999     sample         20.120           ms/op
Client.existUser:existUser·p0.9999    sample         20.838           ms/op
Client.existUser:existUser·p1.00      sample         21.201           ms/op
Client.getUser                        sample  11043   2.900 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          0.901           ms/op
Client.getUser:getUser·p0.50          sample          2.855           ms/op
Client.getUser:getUser·p0.90          sample          3.740           ms/op
Client.getUser:getUser·p0.95          sample          4.129           ms/op
Client.getUser:getUser·p0.99          sample          5.562           ms/op
Client.getUser:getUser·p0.999         sample         12.165           ms/op
Client.getUser:getUser·p0.9999        sample         12.725           ms/op
Client.getUser:getUser·p1.00          sample         12.730           ms/op
Client.listUser                       sample   3734   8.566 ± 0.118   ms/op
Client.listUser:listUser·p0.00        sample          2.363           ms/op
Client.listUser:listUser·p0.50        sample          8.421           ms/op
Client.listUser:listUser·p0.90        sample         11.248           ms/op
Client.listUser:listUser·p0.95        sample         12.292           ms/op
Client.listUser:listUser·p0.99        sample         15.634           ms/op
Client.listUser:listUser·p0.999       sample         18.739           ms/op
Client.listUser:listUser·p0.9999      sample         19.399           ms/op
Client.listUser:listUser·p1.00        sample         19.399           ms/op
