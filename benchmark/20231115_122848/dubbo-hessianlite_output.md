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
# Warmup Iteration   1: 2.556 ops/ms
Iteration   1: 6.287 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.287 ops/ms


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
# Warmup Iteration   1: 7.389 ops/ms
Iteration   1: 13.854 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.854 ops/ms


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
# Warmup Iteration   1: 4.623 ops/ms
Iteration   1: 8.660 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.660 ops/ms


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
# Warmup Iteration   1: 2.107 ops/ms
Iteration   1: 3.647 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.647 ops/ms


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
# Warmup Iteration   1: 5.300 ±(99.9%) 0.067 ms/op
Iteration   1: 2.918 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.918 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.037 ms/op
Iteration   1: 1.824 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.824 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.048 ms/op
Iteration   1: 2.942 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.942 ms/op


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
# Warmup Iteration   1: 13.224 ±(99.9%) 0.475 ms/op
Iteration   1: 8.564 ±(99.9%) 0.120 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.564 ms/op


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
# Warmup Iteration   1: 4.875 ±(99.9%) 0.112 ms/op
Iteration   1: 3.276 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.233 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.270 ms/op
                 createUser·p0.99:   10.682 ms/op
                 createUser·p0.999:  14.041 ms/op
                 createUser·p0.9999: 15.614 ms/op
                 createUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9773
  mean =      3.276 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1511 
    [ 2.500,  3.750) = 6766 
    [ 3.750,  5.000) = 1175 
    [ 5.000,  6.250) = 137 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.270 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     15.614 ms/op
     p(99.9990) =     15.614 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 2.903 ±(99.9%) 0.052 ms/op
Iteration   1: 1.783 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.561 ms/op
                 existUser·p0.50:   1.665 ms/op
                 existUser·p0.90:   2.130 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   4.275 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 12.091 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17953
  mean =      1.783 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 243 
    [ 1.250,  2.500) = 17071 
    [ 2.500,  3.750) = 446 
    [ 3.750,  5.000) = 52 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      1.665 ms/op
     p(90.0000) =      2.130 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      4.275 ms/op
     p(99.9000) =     11.895 ms/op
     p(99.9900) =     12.091 ms/op
     p(99.9990) =     12.534 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.081 ms/op
Iteration   1: 2.876 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   2.650 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.211 ms/op
                 getUser·p0.99:   5.404 ms/op
                 getUser·p0.999:  12.106 ms/op
                 getUser·p0.9999: 13.244 ms/op
                 getUser·p1.00:   13.353 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11111
  mean =      2.876 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 16 
    [ 1.250,  2.500) = 4142 
    [ 2.500,  3.750) = 5854 
    [ 3.750,  5.000) = 956 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      2.650 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.404 ms/op
     p(99.9000) =     12.106 ms/op
     p(99.9900) =     13.244 ms/op
     p(99.9990) =     13.353 ms/op
     p(99.9999) =     13.353 ms/op
    p(100.0000) =     13.353 ms/op


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
# Warmup Iteration   1: 12.249 ±(99.9%) 0.432 ms/op
Iteration   1: 7.835 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   1.913 ms/op
                 listUser·p0.50:   7.438 ms/op
                 listUser·p0.90:   10.535 ms/op
                 listUser·p0.95:   11.567 ms/op
                 listUser·p0.99:   13.693 ms/op
                 listUser·p0.999:  19.497 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4140
  mean =      7.835 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 140 
    [ 5.000,  7.500) = 1991 
    [ 7.500, 10.000) = 1449 
    [10.000, 12.500) = 454 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.913 ms/op
     p(50.0000) =      7.438 ms/op
     p(90.0000) =     10.535 ms/op
     p(95.0000) =     11.567 ms/op
     p(99.0000) =     13.693 ms/op
     p(99.9000) =     19.497 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.287          ops/ms
Client.existUser                       thrpt         13.854          ops/ms
Client.getUser                         thrpt          8.660          ops/ms
Client.listUser                        thrpt          3.647          ops/ms
Client.createUser                       avgt          2.918           ms/op
Client.existUser                        avgt          1.824           ms/op
Client.getUser                          avgt          2.942           ms/op
Client.listUser                         avgt          8.564           ms/op
Client.createUser                     sample   9773   3.276 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.233           ms/op
Client.createUser:createUser·p0.50    sample          3.121           ms/op
Client.createUser:createUser·p0.90    sample          3.916           ms/op
Client.createUser:createUser·p0.95    sample          4.270           ms/op
Client.createUser:createUser·p0.99    sample         10.682           ms/op
Client.createUser:createUser·p0.999   sample         14.041           ms/op
Client.createUser:createUser·p0.9999  sample         15.614           ms/op
Client.createUser:createUser·p1.00    sample         15.614           ms/op
Client.existUser                      sample  17953   1.783 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.561           ms/op
Client.existUser:existUser·p0.50      sample          1.665           ms/op
Client.existUser:existUser·p0.90      sample          2.130           ms/op
Client.existUser:existUser·p0.95      sample          2.355           ms/op
Client.existUser:existUser·p0.99      sample          4.275           ms/op
Client.existUser:existUser·p0.999     sample         11.895           ms/op
Client.existUser:existUser·p0.9999    sample         12.091           ms/op
Client.existUser:existUser·p1.00      sample         12.534           ms/op
Client.getUser                        sample  11111   2.876 ± 0.027   ms/op
Client.getUser:getUser·p0.00          sample          1.083           ms/op
Client.getUser:getUser·p0.50          sample          2.650           ms/op
Client.getUser:getUser·p0.90          sample          3.744           ms/op
Client.getUser:getUser·p0.95          sample          4.211           ms/op
Client.getUser:getUser·p0.99          sample          5.404           ms/op
Client.getUser:getUser·p0.999         sample         12.106           ms/op
Client.getUser:getUser·p0.9999        sample         13.244           ms/op
Client.getUser:getUser·p1.00          sample         13.353           ms/op
Client.listUser                       sample   4140   7.835 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          1.913           ms/op
Client.listUser:listUser·p0.50        sample          7.438           ms/op
Client.listUser:listUser·p0.90        sample         10.535           ms/op
Client.listUser:listUser·p0.95        sample         11.567           ms/op
Client.listUser:listUser·p0.99        sample         13.693           ms/op
Client.listUser:listUser·p0.999       sample         19.497           ms/op
Client.listUser:listUser·p0.9999      sample         21.725           ms/op
Client.listUser:listUser·p1.00        sample         21.725           ms/op
