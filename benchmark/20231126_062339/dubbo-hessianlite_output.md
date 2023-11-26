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
# Warmup Iteration   1: 1.958 ops/ms
Iteration   1: 5.158 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.158 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 13.463 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.463 ops/ms


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
# Warmup Iteration   1: 3.904 ops/ms
Iteration   1: 7.774 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.774 ops/ms


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
# Warmup Iteration   1: 2.112 ops/ms
Iteration   1: 3.916 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.916 ops/ms


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
# Warmup Iteration   1: 4.849 ±(99.9%) 0.056 ms/op
Iteration   1: 2.824 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.824 ms/op


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
# Warmup Iteration   1: 3.147 ±(99.9%) 0.038 ms/op
Iteration   1: 1.893 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.893 ms/op


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
# Warmup Iteration   1: 4.294 ±(99.9%) 0.050 ms/op
Iteration   1: 2.943 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.943 ms/op


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
# Warmup Iteration   1: 10.436 ±(99.9%) 0.157 ms/op
Iteration   1: 7.968 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.968 ms/op


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.094 ms/op
Iteration   1: 2.869 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.287 ms/op
                 createUser·p0.99:   7.410 ms/op
                 createUser·p0.999:  12.976 ms/op
                 createUser·p0.9999: 13.121 ms/op
                 createUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11273
  mean =      2.869 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 4272 
    [ 2.500,  3.750) = 5940 
    [ 3.750,  5.000) = 630 
    [ 5.000,  6.250) = 180 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.674 ms/op
     p(95.0000) =      4.287 ms/op
     p(99.0000) =      7.410 ms/op
     p(99.9000) =     12.976 ms/op
     p(99.9900) =     13.121 ms/op
     p(99.9990) =     13.124 ms/op
     p(99.9999) =     13.124 ms/op
    p(100.0000) =     13.124 ms/op


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
# Warmup Iteration   1: 3.079 ±(99.9%) 0.065 ms/op
Iteration   1: 1.880 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.548 ms/op
                 existUser·p0.50:   1.688 ms/op
                 existUser·p0.90:   2.380 ms/op
                 existUser·p0.95:   2.548 ms/op
                 existUser·p0.99:   3.660 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 19.778 ms/op
                 existUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17083
  mean =      1.880 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 156 
    [ 1.250,  2.500) = 15873 
    [ 2.500,  3.750) = 886 
    [ 3.750,  5.000) = 87 
    [ 5.000,  6.250) = 16 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      1.688 ms/op
     p(90.0000) =      2.380 ms/op
     p(95.0000) =      2.548 ms/op
     p(99.0000) =      3.660 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     19.778 ms/op
     p(99.9990) =     19.825 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.086 ms/op
Iteration   1: 3.057 ±(99.9%) 0.044 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.875 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   4.202 ms/op
                 getUser·p0.99:   6.820 ms/op
                 getUser·p0.999:  18.728 ms/op
                 getUser·p0.9999: 19.627 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10461
  mean =      3.057 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 2515 
    [ 2.500,  3.750) = 6911 
    [ 3.750,  5.000) = 744 
    [ 5.000,  6.250) = 122 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.820 ms/op
     p(99.9000) =     18.728 ms/op
     p(99.9900) =     19.627 ms/op
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
# Warmup Iteration   1: 11.132 ±(99.9%) 0.350 ms/op
Iteration   1: 7.124 ±(99.9%) 0.081 ms/op
                 listUser·p0.00:   3.047 ms/op
                 listUser·p0.50:   6.889 ms/op
                 listUser·p0.90:   9.000 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   13.290 ms/op
                 listUser·p0.999:  17.612 ms/op
                 listUser·p0.9999: 18.842 ms/op
                 listUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4536
  mean =      7.124 ±(99.9%) 0.081 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 14 
    [ 3.750,  5.000) = 209 
    [ 5.000,  6.250) = 1163 
    [ 6.250,  7.500) = 1633 
    [ 7.500,  8.750) = 960 
    [ 8.750, 10.000) = 325 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      3.047 ms/op
     p(50.0000) =      6.889 ms/op
     p(90.0000) =      9.000 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     13.290 ms/op
     p(99.9000) =     17.612 ms/op
     p(99.9900) =     18.842 ms/op
     p(99.9990) =     18.842 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.158          ops/ms
Client.existUser                       thrpt         13.463          ops/ms
Client.getUser                         thrpt          7.774          ops/ms
Client.listUser                        thrpt          3.916          ops/ms
Client.createUser                       avgt          2.824           ms/op
Client.existUser                        avgt          1.893           ms/op
Client.getUser                          avgt          2.943           ms/op
Client.listUser                         avgt          7.968           ms/op
Client.createUser                     sample  11273   2.869 ± 0.034   ms/op
Client.createUser:createUser·p0.00    sample          0.881           ms/op
Client.createUser:createUser·p0.50    sample          2.621           ms/op
Client.createUser:createUser·p0.90    sample          3.674           ms/op
Client.createUser:createUser·p0.95    sample          4.287           ms/op
Client.createUser:createUser·p0.99    sample          7.410           ms/op
Client.createUser:createUser·p0.999   sample         12.976           ms/op
Client.createUser:createUser·p0.9999  sample         13.121           ms/op
Client.createUser:createUser·p1.00    sample         13.124           ms/op
Client.existUser                      sample  17083   1.880 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.548           ms/op
Client.existUser:existUser·p0.50      sample          1.688           ms/op
Client.existUser:existUser·p0.90      sample          2.380           ms/op
Client.existUser:existUser·p0.95      sample          2.548           ms/op
Client.existUser:existUser·p0.99      sample          3.660           ms/op
Client.existUser:existUser·p0.999     sample         19.431           ms/op
Client.existUser:existUser·p0.9999    sample         19.778           ms/op
Client.existUser:existUser·p1.00      sample         19.825           ms/op
Client.getUser                        sample  10461   3.057 ± 0.044   ms/op
Client.getUser:getUser·p0.00          sample          0.908           ms/op
Client.getUser:getUser·p0.50          sample          2.875           ms/op
Client.getUser:getUser·p0.90          sample          3.731           ms/op
Client.getUser:getUser·p0.95          sample          4.202           ms/op
Client.getUser:getUser·p0.99          sample          6.820           ms/op
Client.getUser:getUser·p0.999         sample         18.728           ms/op
Client.getUser:getUser·p0.9999        sample         19.627           ms/op
Client.getUser:getUser·p1.00          sample         19.628           ms/op
Client.listUser                       sample   4536   7.124 ± 0.081   ms/op
Client.listUser:listUser·p0.00        sample          3.047           ms/op
Client.listUser:listUser·p0.50        sample          6.889           ms/op
Client.listUser:listUser·p0.90        sample          9.000           ms/op
Client.listUser:listUser·p0.95        sample         10.043           ms/op
Client.listUser:listUser·p0.99        sample         13.290           ms/op
Client.listUser:listUser·p0.999       sample         17.612           ms/op
Client.listUser:listUser·p0.9999      sample         18.842           ms/op
Client.listUser:listUser·p1.00        sample         18.842           ms/op
