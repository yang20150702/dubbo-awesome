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
# Warmup Iteration   1: 2.384 ops/ms
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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.873 ops/ms
Iteration   1: 13.122 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.122 ops/ms


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
# Warmup Iteration   1: 4.647 ops/ms
Iteration   1: 9.400 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.400 ops/ms


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
# Warmup Iteration   1: 2.345 ops/ms
Iteration   1: 3.980 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.980 ops/ms


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.051 ms/op
Iteration   1: 3.145 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.145 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.040 ms/op
Iteration   1: 1.895 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.895 ms/op


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.050 ms/op
Iteration   1: 2.826 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.826 ms/op


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
# Warmup Iteration   1: 11.396 ±(99.9%) 0.218 ms/op
Iteration   1: 7.805 ±(99.9%) 0.068 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.805 ms/op


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
# Warmup Iteration   1: 5.278 ±(99.9%) 0.115 ms/op
Iteration   1: 3.079 ±(99.9%) 0.051 ms/op
                 createUser·p0.00:   0.595 ms/op
                 createUser·p0.50:   2.798 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   4.250 ms/op
                 createUser·p0.99:   11.324 ms/op
                 createUser·p0.999:  21.856 ms/op
                 createUser·p0.9999: 22.117 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10520
  mean =      3.079 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1676 
    [ 2.500,  5.000) = 8420 
    [ 5.000,  7.500) = 223 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.595 ms/op
     p(50.0000) =      2.798 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      4.250 ms/op
     p(99.0000) =     11.324 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     22.117 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 2.922 ±(99.9%) 0.049 ms/op
Iteration   1: 1.794 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.335 ms/op
                 existUser·p0.99:   3.256 ms/op
                 existUser·p0.999:  14.746 ms/op
                 existUser·p0.9999: 15.761 ms/op
                 existUser·p1.00:   15.761 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17825
  mean =      1.794 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 312 
    [ 1.250,  2.500) = 17010 
    [ 2.500,  3.750) = 397 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.335 ms/op
     p(99.0000) =      3.256 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     15.761 ms/op
     p(99.9990) =     15.761 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 4.130 ±(99.9%) 0.080 ms/op
Iteration   1: 3.102 ±(99.9%) 0.052 ms/op
                 getUser·p0.00:   0.522 ms/op
                 getUser·p0.50:   2.925 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   12.042 ms/op
                 getUser·p0.999:  18.546 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10341
  mean =      3.102 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 2671 
    [ 2.500,  3.750) = 6494 
    [ 3.750,  5.000) = 846 
    [ 5.000,  6.250) = 104 
    [ 6.250,  7.500) = 38 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =     12.042 ms/op
     p(99.9000) =     18.546 ms/op
     p(99.9900) =     19.628 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 12.160 ±(99.9%) 0.348 ms/op
Iteration   1: 8.539 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.101 ms/op
                 listUser·p0.50:   8.233 ms/op
                 listUser·p0.90:   11.043 ms/op
                 listUser·p0.95:   12.354 ms/op
                 listUser·p0.99:   16.581 ms/op
                 listUser·p0.999:  18.560 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3729
  mean =      8.539 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 81 
    [ 5.000,  7.500) = 1111 
    [ 7.500, 10.000) = 1838 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.101 ms/op
     p(50.0000) =      8.233 ms/op
     p(90.0000) =     11.043 ms/op
     p(95.0000) =     12.354 ms/op
     p(99.0000) =     16.581 ms/op
     p(99.9000) =     18.560 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.287          ops/ms
Client.existUser                       thrpt         13.122          ops/ms
Client.getUser                         thrpt          9.400          ops/ms
Client.listUser                        thrpt          3.980          ops/ms
Client.createUser                       avgt          3.145           ms/op
Client.existUser                        avgt          1.895           ms/op
Client.getUser                          avgt          2.826           ms/op
Client.listUser                         avgt          7.805           ms/op
Client.createUser                     sample  10520   3.079 ± 0.051   ms/op
Client.createUser:createUser·p0.00    sample          0.595           ms/op
Client.createUser:createUser·p0.50    sample          2.798           ms/op
Client.createUser:createUser·p0.90    sample          3.564           ms/op
Client.createUser:createUser·p0.95    sample          4.250           ms/op
Client.createUser:createUser·p0.99    sample         11.324           ms/op
Client.createUser:createUser·p0.999   sample         21.856           ms/op
Client.createUser:createUser·p0.9999  sample         22.117           ms/op
Client.createUser:createUser·p1.00    sample         22.118           ms/op
Client.existUser                      sample  17825   1.794 ± 0.017   ms/op
Client.existUser:existUser·p0.00      sample          0.527           ms/op
Client.existUser:existUser·p0.50      sample          1.698           ms/op
Client.existUser:existUser·p0.90      sample          2.167           ms/op
Client.existUser:existUser·p0.95      sample          2.335           ms/op
Client.existUser:existUser·p0.99      sample          3.256           ms/op
Client.existUser:existUser·p0.999     sample         14.746           ms/op
Client.existUser:existUser·p0.9999    sample         15.761           ms/op
Client.existUser:existUser·p1.00      sample         15.761           ms/op
Client.getUser                        sample  10341   3.102 ± 0.052   ms/op
Client.getUser:getUser·p0.00          sample          0.522           ms/op
Client.getUser:getUser·p0.50          sample          2.925           ms/op
Client.getUser:getUser·p0.90          sample          3.793           ms/op
Client.getUser:getUser·p0.95          sample          4.252           ms/op
Client.getUser:getUser·p0.99          sample         12.042           ms/op
Client.getUser:getUser·p0.999         sample         18.546           ms/op
Client.getUser:getUser·p0.9999        sample         19.628           ms/op
Client.getUser:getUser·p1.00          sample         19.628           ms/op
Client.listUser                       sample   3729   8.539 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          3.101           ms/op
Client.listUser:listUser·p0.50        sample          8.233           ms/op
Client.listUser:listUser·p0.90        sample         11.043           ms/op
Client.listUser:listUser·p0.95        sample         12.354           ms/op
Client.listUser:listUser·p0.99        sample         16.581           ms/op
Client.listUser:listUser·p0.999       sample         18.560           ms/op
Client.listUser:listUser·p0.9999      sample         21.889           ms/op
Client.listUser:listUser·p1.00        sample         21.889           ms/op
